# Java-Productivity
Productivity tools for rapid app development
---
<br/>
<br/>

> 📘 Code Generators
> 
> Quick & Dirty Code

#### [Open Fiegn Client Code Gen](https://github.com/swagger-api/swagger-codegen/tree/master/modules/swagger-codegen/src/main/resources/JavaSpring/libraries/spring-cloud)

```
java -jar modules/swagger-codegen-cli/target/swagger-codegen-cli.jar generate \
    -i http://petstore.swagger.io/v2/swagger.json \
    -l spring \
    --library spring-cloud \
    -o samples/client/petstore/java
```
<br/>
<br/>

#### [Json 2 Pojo](https://www.jsonschema2pojo.org/)
 > [CLI](https://github.com/joelittlejohn/jsonschema2pojo/wiki/Getting-Started#the-command-line-interface)
 
<br/>
<br/>
#### [Data Base to Crud App - Spring Roo](https://spring.io/projects/spring-roo#overview)
 - Super out dated good for:
     - (Reverse Engineer A Database to a Spring Web App)[http://rburawes.github.io/]
     - Rapid App Development
          - Create a Throwaway back office from a domain model
<br/>
<br/>

> 🤖 Background Jobs
> 
> Create scalable scheduled tasks

- [JobRunr - Lambda to Job](https://github.com/jobrunr/jobrunr)
 ```java
 BackgroundJob.enqueue(() -> System.out.println("This is all you need for distributed jobs!"));
 ```
