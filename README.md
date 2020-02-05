<h1 align="center">
GoStack-Gobarber  
 </h1>

<h4 align="center">App para gerenciamento de barbearias</h4>

<h2 align="center">Back-End</h2>
<p align="center">
 <a href="#mega-Tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
 <a href="#mega-Pré-requisitos">Pré-requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
 <a href="#mega-Como-usar">Como usar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
 <a href="#memo-licença">Licença</a>
</p>

<h2 align="center">Front-End</h2>
<p align="center">
 <a href="#mega-Tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
 <a href="#mega-Pré-requisitos">Pré-requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
 <a href="#mega-Como-usar">Como usar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
 <a href="#memo-licença">Licença</a>
</p>

# Back-End

## :small_blue_diamond: Tecnologias
 - [ Nodejs ]( https://nodejs.org/en/ )
 - [ Expressjs ]( https://expressjs.com/pt-br/ )
 - [ PostgreSQL ]( https://www.postgresql.org/ )
 - [ MongoDB ]()
 - [ Redis ]()
 
 ## :small_blue_diamond: Dependências
|       |    |     |    | 
| ------|-----|-----|-----|
| **bcryptjs** 	| https://www.npmjs.com/package/bcrypt	|  **multer** 	| https://github.com/expressjs/multer |
| **express**  	| https://www.npmjs.com/package/express 	| **bee-queue**	| https://github.com/bee-queue/bee-queue |
| **express-async-erros** 	| https://www.npmjs.com/package/express-async-errors 	| **date-fns** 	| https://date-fns.org/docs/Getting-Started |
| **express-handlebars** 	|  https://www.npmjs.com/package/express-handlebars|  **@sentry/node** | https://www.npmjs.com/package/@sentry/node |
| **jsonwebtoken** 	|https://www.npmjs.com/package/jsonwebtoken  	|   **dotenv**	| https://www.npmjs.com/package/dotenv |  
| **pg-hstore** 	| https://www.npmjs.com/package/pg-hstore 	|  **mongoose** | https://www.npmjs.com/package/mongoose |
| **sequelize**  	| https://sequelize.org/ 	| **nodemailer** 	| https://www.npmjs.com/package/nodemailer |
| **yup**	| https://github.com/jquense/yup	| **nodemailer-express-handlebars** 	| https://www.npmjs.com/package/nodemailer-express-handlebars |
| **youch** | https://www.npmjs.com/package/youch |

## :small_blue_diamond: Pré-requisitos
 Esse projeto faz uso de algumas tecnologias de uso obrigario e que são necessarias serem instaldas no sistema. São elas:
  **Nodejs** na versão **12.14.1** ou superior, **postgreSql**, **MongoDB** e o **Redis**.

## :mega: Como Usar

* **Download**
  
  Para fazer o download do projeto abra o **```terminal```** e execute o comando abaixo: 
  ```
  git clone https://github.com/bhyago/Fast-feet.git
  ```
* **Instalando as Dependências** 

  Para instalar as dependências necessarias e gerar a pasta **```node_modules```** execute o comando:
  ```
  yarn
  ```
  
* **Incializando as variaveis de ambiente**

  Dentro do diretorio **``` ./gobarber/.env.example```**, altere os dados de acordo com a configuração das suas variaveis de ambiente e depois renomeie o arquivo para **```.env```**.

* **Inicialização do servidor**

  Para inicializar o servidor, no terminal execute o comando:
  ```
  yarn dev
  ```
  Se desejar iniciar o servidor juntamente com **```degub```** do **```vscode```**, execute o seguinte comando:
  ```
  yarn dev:degub
  ```
 #### :memo: Licença

  Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

  
 ##### **Feito com :heart: by Hyago Braga**
