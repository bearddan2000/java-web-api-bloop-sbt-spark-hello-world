# java-web-api-bloop-sbt-spark-hello-world

## Description
A POC for java spark webframework.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- java
- bloop-sbt
  - spark

## Docker stack
- openjdk:8-jdk-alpine

## To run
`sudo ./install.sh -u`
- Available at http://localhost

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- [Building an API With the Spark Java Framework](https://www.baeldung.com/spark-framework-rest-api)
