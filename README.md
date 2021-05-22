# QAzando Web Test Automation

Projeto de automação de testes web com selenium webdriver + java.

# Tecnologias & Ferramentas:
- [x] Java 8<br>
- [x] Selenium WebDriver
- [x] Cucumber
- [x] Apache Maven 


# Reports
Usando o cluecumber
```
mvn test -Dtest=**/*RunCucumberTest cluecumber-report:reporting
```

Sobrescrevendo tags
```
mvn test -Dtest=**/*RunCucumberTest cluecumber-report:reporting -Dcucumber.options="--tags @teste"
```
