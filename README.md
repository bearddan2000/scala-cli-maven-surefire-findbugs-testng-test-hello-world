# scala-cli-maven-surefire-findbugs-testng-test-hello-world

## Description
Analyze source code for potential bugs.
A POC for maven app using testNg
framework with surefire plugin.

## Tech stack
- scala
- maven
	- findbugs
  - testNg
  - surefire

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/testng)
