 # Rushi technologies web application.

 ## Build application Package
mvn clean package
 Pre Requisties to deploy

- Java 11+
- Tomcat 9.x
## Deployment instruction
copy application package that is built using mvn clean package from build server to deployment server.
```bash
scp -i  target/rushitechapp.war ec2-suer@10.89.45.90:/opt/tomcat/webapps/rushitech.war
```


