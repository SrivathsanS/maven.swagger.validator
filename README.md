# maven.swagger.validator

This is a sample Maven project that shows how Swagger documents can be validated against Swagger specification v2.0. Swagger documents located under `${basedir}/src/main/resources/swagger` will be validated against the spec.
Right now, this sample project only supports JSON Swagger documents but can be easily changed to support YAML files as well by converting YAML to JSON before the validation step.

Building
--------

Prerequisites:
* [JDK8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
* [Maven 3.3.3+](http://maven.apache.org/download.cgi)

Building:

   ```sh
   $ mvn verify
   ```