# Java-Productivity
##### A list of Productivity tools for rapid app development

<img    src="https://lh4.googleusercontent.com/_nn0TBN3Qrxqc7ZkOD9xTd5zJCG9KGgvsDXE8PHUwj1ujXxZMJ2aIrGSDyKA3k3H0VysTy5i2VYCtO_8X1INBHI1AbzCnRK_vwmvVE_63STs4tH1uaOuiROJJPXnQbwxsE3m6lHD" 
 alt="banner" 
 width="200"/>
---

## Contents
 - 📘 [Code Generators](#code-generators)
 - 🤖 [Background Jobs](#background-jobs)
 - 🛡️ [Security](#security)
 - 🛠️ [Development And Testing](#development-and-testing)
 - 📚 [Helpful Lists](#helpful-lists)
 - 🌌 [Steal Some Code](#steal-some-code)
 - 🎨 [Content And Artwork](#content-and-artwork)
 - 📔 [Tutorials](#tutorials)

### Code Generators
> 📘 
> 
> Quick / Dirty Code

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

### Background Jobs
> 🤖
> 
> Create scalable scheduled tasks, backed by persistence with a backoffice for managing them.

- [JobRunr - Lambda to Job](https://github.com/jobrunr/jobrunr)

 ```java
 BackgroundJob.enqueue(() -> System.out.println("This is all you need for distributed jobs!"));
 ```

<br/>
<br/> 
 
### Security
> 🛡️ 
> 
> 15 Minute Security

 - [Auth0-Boot](https://auth0.com/docs/quickstart/backend/java-spring-security5/01-authorization)

<br/>
<br/>

### Development And Testing
> 🛠️ 
> 
> Dependancies that speed up testing / development
 
 - [Spring Boot Dev Tools](https://www.baeldung.com/spring-boot-devtools)
   - Start your Spring app, re-build project for 1-10 second builds.
 
 ```xml
 <dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-devtools</artifactId>
</dependency>
```

<br/>

 - [Fake Data](https://github.com/DiUS/java-faker)
 
<br/>
<br/>

### Helpful Lists 
> 📚 
> 
> Public API's / Ultimate Java Library List

- [Public API's](https://github.com/public-apis/public-apis)
- [Awesome Java](https://github.com/akullpp/awesome-java)

<br/>
<br/>

### Steal Some Code
> 🌌 
> 
> Code Examples

- [Program Creek](https://www.programcreek.com/java-api-examples/?action=search)
- [TabNine](https://www.tabnine.com/code)
- [Just Cheat](https://github.com/features/copilot/)

<br/>
<br/>

### Content And Artwork
> 🎨 
> 
> Web Assets / Reference Material
- [3D Shapes](https://www.shapefest.com/)
- [ASCII Art](https://patorjk.com/software/taag/#p=display&f=Graffiti&t=Type%20Something%20)
- [Web Design Trends](https://abduzeedo.com/)
- [UX Check List](https://www.checklist.design/)

<br/>
<br/>

### Tutorials
> 📔 
> 
> Java / Spring Samples

 - [Spring](https://github.com/eugenp/tutorials)
 - [Algorithms / Sorting / Searching](https://github.com/eugenp/tutorials/tree/master/algorithms-modules)
