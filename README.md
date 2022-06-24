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

#### [Json 2 Pojo](https://www.jsonschema2pojo.org/)
 - [CLI](https://github.com/joelittlejohn/jsonschema2pojo/wiki/Getting-Started#the-command-line-interface)

```shell
jsonschema2pojo --source address --target java-gen
```

<br/>

#### [Spring Roo](https://spring.io/projects/spring-roo#overview)
 - Ancient but has some use:
     - [Reverse Engineer A Database to a Spring Web App](http://rburawes.github.io/)
     - Throwaway Rapid App Development
     - Create a Throwaway back office from a domain model
     - Generate a monolith from a schema then rip out the good code

#### [Lombok](https://projectlombok.org/setup/maven)
 - Boiler Plate Java

<br/>

#### [MapStruct](https://mapstruct.org/documentation/installation/)
 - Object Mapping, use for throwaway projects.

<br/>
<br/>

> 🤖 Background Jobs
> 
> Create scalable scheduled tasks, backed by persistence with a backoffice for managing them.

- [JobRunr - Lambda to Job](https://github.com/jobrunr/jobrunr)

 ```java
 BackgroundJob.enqueue(() -> System.out.println("This is all you need for distributed jobs!"));
 ```

<br/>
<br/> 
 
> 🛡️ Security
> 
> 15 Minute Security

 - [Auth0-Boot](https://auth0.com/docs/quickstart/backend/java-spring-security5/01-authorization)
 
