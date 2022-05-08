# Getting Started

### Reference Documentation
Aplicação desenvolvida em java com springboot de um sistema simples de extrato bancário.

### Configurando banco de dados no Docker

 - Acessar a pasta docker_db e alterar arquivo docker-compose.yml
######db:
 - [x] POSTGRES_USER (_nome de usuário_)
 - [x] POSTGRES_PASSWORD (_senha de usuário_)
 - [x] POSTGRES_DB (_nome do banco de dados_)
######pgadmin:
- [x] PGADMIN_DEFAULT_EMAIL(_email a escolha do usuário_)
- [x] PGADMIN_DEFAULT_PASSWORD (_senha  a escolha do usuário_)
- _Esse imagem poderá ser acessada pelo browser através da porta 8889 para visualização de forma gráfica do db_

######Rodando o bando:
- Acessar a pasta  docker_db pelo terminal e rodar comando : *docker-compose up* 
- Parar parar o servico basta rodar comando : *docker-compose down*
- os dados nãos erão perdidos, pois uma pasta de volume é criada.

### Configurando JAVA

- Alterar dados do arquivo [*application.properties*] com os dados configurados no arquivo docker-compose.yml
- Agora basta rodar a aplicação

### FAZENDO TESTES ATRAVÉS DO SWAGGER
 - No browser digitar - (http://localhost:8080/swagger-ui/index.html)
* [Spring Boot + Spring data JPA + PostgreSQL](https://mkyong.com/spring-boot/spring-boot-spring-data-jpa-postgresql/)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.6.7/maven-plugin/reference/html/)


