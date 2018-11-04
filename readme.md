## Deploy app Heroku
## Using Postegre



### Build and run

#### Configurations

Open file `application.properties` file contains informations for conections.

#### Requirements

- Java 8
- Maven > 3.0
- Spring 2.0.3.RELEASE `pom.xml`

#### From terminal

Go on the project's root folder, then type:

    $ mvn spring-boot:run

#### From Eclipse (Spring Tool Suite)

Import as *Existing Maven Project* and run it as *Spring Boot App*.

### Usage

Comando Heroku

-- heroku login
-> douglasmarquesdias@hotmail.com
-> Senha

####Criando projeto
heroku create aw-contatos-api (nome projeto)

####Configurando banco
heroku addons:create heroku-postgresql:hobby-dev

####Enviado para o git do heroku
git push heroku master

####Visualizar logs
Heroku logs --tails

####Abrir aplicação
heroku open

