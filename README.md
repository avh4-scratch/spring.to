## Project structure

Use maven, not gradle.
`$JAVA_HOME` **must** be set!

pom.xml parent: `org.springframework.boot:spring-boot-start-parent:1.0.0.RC1`

Repository: `http://repo.spring.io/milestone`

Dependencies:

 - `org.springframework.boot:spring-boot-starter-web` Web stuff
 - `javax.inject:javax.inject:1`

## "Integration tests"

 - `org.assertj:assertj-core:1.5.0` Fluent assert syntax
 - `org.springframework:spring-test` test

## Controllers

## Views

 - ~~`org.springframework.boot:spring-boot-starter-thymeleaf`~~ NOT IN 1.0.0.RC1
 - `org.thymeleaf:thymeleaf-spring4` (until spring-boot-starter-thymeleaf is released)

## Models (and database)

 - `org.springframework.boot:spring-boot-starter-data-jpa` Database stuff
 - `com.h2database:h2` runtime

## API endpoints

`@RequestBody`, or `@RestController`

## Running the server

 - `org.springframework.boot:spring-boot-starter-actuator` Diagnostic endpoints

```bash
mvn spring-boot:run
open http://localhost:8080
```

## Deploying

## Code coverage / PIT
