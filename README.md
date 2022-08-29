# java-cli-bloop-sbt-jacoco-testng-hello-world

## Description
A POC for bloop-sbt app using testng and jacoco.
Writes test results to console
and html.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- java
- bloop-sbt
  - testng
  - jacoco

## Docker stack
- hseeberger/scala-bloop-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Build code concept](https://github.com/bloop-sbt/sbt-jacoco)
