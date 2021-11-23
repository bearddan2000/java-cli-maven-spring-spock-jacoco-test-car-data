# java-cli-maven-spring-spock-jacoco-test-car-data

## Description
A POC for spring app using spock framework
and jacoco plugin.

## Tech stack
- java
- groovy
- maven
  - spring
  - spock
  - jacoco

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- jacoco report under bin/target/site/jacoco

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept] (https://www.petrikainulainen.net/programming/testing/writing-unit-tests-with-spock-framework-creating-a-maven-project/)
- [Code build model] (https://github.com/christoph-frick/spock-test-logging)
- [Jacoco config] (https://www.baeldung.com/jacoco)
