## <h3 style="color: #48c;">**Automação de Testes - Ambiente Demo/Qed**</h3>

<br>

#### **Objetivo**

<br>
Este projeto tem como objetivo executar uma automação de testes nas principais aplicações dos Sistemas Internos.

<br>

#### **Tecnologias usadas**

<br>

- Java 21
- Maven
- Selenium
- JUnit
- TestNG

<br>

#### **Estrutura do Projeto**

<br>

```
    github
    allure-results
    docs
    
    ├── src
    │   ├── main
    │   │   ├── java
    │   │   │   ├── core
    │   │   │   ├── database
    │   │   │   ├── docusign
    │   │   │   ├── gmail    
    │   │   │   ├── helpers
    │   │   │   ├── onvio
    │   │   │   ├── pages
    │   │   │   ├── rest
    │   │   │   ├── testCases
    │   │   │   ├── Application.java
    │   │   │   ├── SuiteManager.java
    │   │   ├── resources
    │   │   │   ├── data
    │   │   │   ├── hibernate
    │   │   │   ├── configDemo.properties
    │   │   │   ├── configQed.properties
    │   ├── test
    │   │   ├── java
    │   │   ├── resources

    pom.xml
    README.md
```

<br>

#### **Execução**

<br>
Para executar a automação, basta executar o arquivo `Application.java` que está localizado em `src/main/java`.

<br>
É necessário setar a variável `environment` e `execution` no arquivo `Config` com base no ambiente que irá rodar os testes.

<br>
Exemplo:

```java
    private static final String environment = "DEMO";
    private static final String execution = "SERVIDOR";
```

<br>

#### **Relatórios**

<br>
Os relatórios de execução são gerados na pasta `allure-results` e podem ser visualizados através dos seguintes comandos:

<br>

**Limpar a pasta allure-results antes de gerar um novo relatório:**

`Get-ChildItem -Path allure-results -Recurse | Remove-Item -Recurse -Force`

<br>

**Gerar o relatório:**

`allure serve allure-results`.

<br>

Também existe um outro formato de envio de relatórios para o Teams ou Slack, que são gerados e enviados após a execução dos testes na `Application.java`.

<br>

#### **Observações**

<br>
A automação é executada em um ambiente de Demo/Qed, portanto, é necessário que o ambiente esteja disponível para a execução dos testes.

<br>
Os dados utilizados são fictícios e não afetam o ambiente de produção.

<br>
Por conta dos processamentos e processos dentro do ambiente, a execução dos testes pode demorar um pouco mais do que o esperado.
