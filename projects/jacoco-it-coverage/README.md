This example demonstrates how to collect code coverage by integration tests, which located in a separate module.

Prerequisites
=============

* Sonar 2.12 or higher

Execution
=========

1.  Build project and execute all tests:

        mvn clean install

2.  Analyse by Sonar :

        mvn sonar:sonar
