# Lojinha Web Performance com JMeter
Esse é um repositório que contém testes de performance de um software denominado Lojinha Web via JMeter. Os sub-tópicos abaixo descrevem algumas decisões tomadas na estruturação do projeto.

## Tecnologias Utilizadas
- Java
https://www.oracle.com/java/technologies/javase/jdk18-archive-downloads.html
- JMeter
https://jmeter.apache.org/download_jmeter.cgi
- JMeter Plugins Manager
https://jmeter-plugins.org/wiki/PluginsManager/

## Testes de Performance
Testes para validar a performance da Lojinha Web com 50 usuários simultâneos que: acessam à página da Lojinha, fazem login, adicionam um novo produto e fazem logoff.


## Notas Gerais
- Utilizamos um arquivo csv para controle externo das variáveis.
- Utilizamos um temporizador aleatório gaussiano para simular o usuário final que utiliza a aplicação.
- Utilziamos os seguintes plugins para melhor analisar o resultado do teste: Relatório de Sumário; Relatório Agregado; Active Threads Over Time; Response Times Over Time; Transactions per Second.