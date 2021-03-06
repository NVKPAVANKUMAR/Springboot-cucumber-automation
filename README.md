# Cucumber + Selenium + Spring Boot example

This repository contains the base setup of an UI testing project, using Cucumber + Selenium (Page Factory Model) +
Spring Boot

A simple search in DuckDuckGo to check that results are displayed is used as example

# Requirements

* JDK 8
* Maven 3.6

# Test Execution

1. Download or clone the repository
2. Open a terminal
3. From the project root directory run:  `mvn clean test`

# Configuration

By default, tests will be executed in Chrome (headless mode). Preferences can be changed in "application.properties"
file

# Results

To check the report, open the '/test-output' file once the execution has finished.

# Links

[Cucumber](<https://docs.cucumber.io/>)

[Gherkin](<https://cucumber.io/docs/gherkin/>)

[Selenium](<https://github.com/SeleniumHQ/selenium>)

[Page Object & Page Factory](<https://www.tutorialselenium.com/2019/02/05/page-object-model-selenium-webdriver/>)

[Spring Boot](<https://spring.io/projects/spring-boot>)

[WebDriverManager](<https://github.com/bonigarcia/webdrivermanager>)

[Extentreports-Cucumber7-Adapter](<https://github.com/grasshopper7/extentreports-cucumber7-adapter.git>)
   