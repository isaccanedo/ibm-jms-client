# IBM JMS demo
A simple demo application to show connection between a Spring Boot application and an IBM MQ Server, via queues.

## construção

`mvn clean package`
`docker-compose build`

(também crie dependências separadas)

## Executando
`docker-compose up`


MQ docker:
https://github.com/ibm-messaging/mq-container

MQ JMS spring starter: 
https://github.com/ibm-messaging/mq-jms-spring

Documentação do IBM JMS Spring: 
https://developer.ib m.com/technologies/java/tutorials/mq-jms-application-development-with-spring-boot/#
