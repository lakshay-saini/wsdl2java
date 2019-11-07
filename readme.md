#Generate Stubs through wsdl

## Generate through wsdl url
enable 'JAX-WS' Maven plugin to parse a WSDL URL in pom.xml
mvn clean install -Purl

## Generate through wsdl file
enable 'JAX-WS' Maven plugin to parse a WSDL File in pom.xml
mvn clean install -Ppath