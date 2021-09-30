<h1>Cucumber-BDD-Automation-Framework</h1>
<h2>Behavior Driven Development Cucumber - Selenium based automation framework including Allure reports</h2>

_Framework used WebDriverManager to initialise driver , to eliminate need to store driver binaries locally

## Prerequisite
Java, Maven, Intellij/Eclipse with Gherkin & Cucumber Plugin 

## How to run
```cmd
cd <project-directory>
mvn clean test
```

## Feature File
> ..\src\test\resources\features\todoMVC.feature

## Generate Allure Report
```cmd
mvn allure:serve
```
* report will automatically open up at http//:127.0.0.1:13021/index.html (port number may change)