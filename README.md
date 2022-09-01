# Spring Boot Sample Applications

This repository contains very simple and hence basic Spring Boot sample applications that expose actuator endpoints. The
main purpose of this repository is to deploy different versions of Spring Boot apps to a k8s cluster to check
compatibility with different Spring Boot Admin versions.

To build docker images run `mvn verify`,
`mvn install` will run `docker dploy` internally.