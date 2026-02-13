### backend develeopment
1. create git repo
  git init

2. add .gitignore file

3. create .env file for environment variables& read data from .env
 with dotenv
 npm i dotenv
 use process.env to acess

4.Generate package.json
 npm init -y

5. create express npm

6. connect to databae
func decalaration vs function expression
7. add middleware(bodyparser,er handling middlewares)
8. design schemas and create models
9.creation of protected route
//how to make protected route'
/*client ======="1.post"========>login route====="2.store token in cookies storage"====>token(cookie)
 client<========"3.login success"==================login route
 token=="4.check cookie storage
 5.read token"======>client==========="6.req with token"====================>public routes
 check token ==> protected route*/