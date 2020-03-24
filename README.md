# Dremio ARP Teradata Connector

## Building and Installation

1. In root directory with the pom.xml file run `mvn clean install`
2. Take the resulting .jar file in the target folder and put it in the \dremio\jars folder in Dremio
3. Take the SQLite JDBC driver from (https://downloads.teradata.com) and put in in the \dremio\jars\3rdparty folder
4. Restart Dremio
