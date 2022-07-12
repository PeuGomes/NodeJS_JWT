# NodeJS_JWT

# Observem todas instruções antes de tentar por si so. falo isso aos iniciantes.

Node.Js e JWT

Trabalhando falhas de segurança e protegendo as senhas no banco de dados.

precisara do node.js instalado
instalar o npm install no terminal 

como consultar? atraves do postman ou insomnia

instale o npm instal bcrypt@3.0.8

delete o db.sqlite e reinicie  com o npm run start

Para teste crie no insomnia um novo usuario...

localhost:3000/usuario

depois va em listar usuario

get localhost:3000/usuario

Criando um sistema de login.

No caso utilizado sera guardado o login no cliente

Utilizado no projeto o metodo Json Web Token (JWT)

No terminal sera instlado dois npms.

1 - npm install passport@0.4.1

2- npm install passport-local@1.0.0

Foi feita a estrategia de configuração 

consultar atraves do POST localhost:3000/usuario/login

Implementação da criação do token para o envio do usuario 

instale o npm install jsonwebtoken@8.5.1

rode no terminal uma biblioteca do node que ja vem com crypto 

node -e "console.log( require('crypto').randomBytes(256).toString('base64'))"

pegue a senha e crie uma variavel de ambiente ou seja crie um novo arquivo na raiz do projeto chamando .env ai você cria a variavel com a senha.

Para usar essa chave contendo a senha instale npm install dotenv@8.2.0

No arquivo .gitignore coloque o arquivo .env assim o projeto publico não vai com a chave privada

Instale o npm install passport-http-bearer@1.0.1

Precisara ter o redis.

Instale o npm install redis@3.0.2


caminhos para consulta no insomnia

localhost:3000/usuario/logout   (Efetua logout) metodo GET

localhost:3000/usuario/login  (Efetua login) metodo POST

localhost:3000/usuario       (Listar usuarios) metodo GET

localhost:3000/usuario/2      (Deletar usuario) metodo DELETE

localhost:3000/post         (listar post) metodo GET

localhost:3000/post         (Cria Post) metodo POST

localhost:3000/usuario  (Criar usuario) metodo POST
