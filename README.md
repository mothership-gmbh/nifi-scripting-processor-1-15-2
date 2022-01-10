# nifi-scripting-processor-1-15-2

Basic shell project to reproduce an error during running "mvn clean install" when having the dependency 
``nifi-scripting-processors``.

## Relevant changes

* nifi-de.mothership-nar/pom.xml -> Added `nifi-nar-maven-plugin`
* nifi-de.mothership-processors/pom.xml -> Added `nifi-scripting-processors`