# Spring-Boots-training

Learning Spring-boots step by step documentation.

# Installs and getting ready
* installing Java corretto 17
> java 17 has long term support, 18 does not. 
[Click here to check java corretto downloads](https://aws.amazon.com/corretto/?filtered-posts.sort-by=item.additionalFields.createdDate&filtered-posts.sort-order=desc)
* **OPTIONAL** installing Maven
trough homebrew(Mac):<br/>
``brew install maven`` <br/>
* for checking version run: 
    * `` mvn -v `` or `` mvn -help `` for options 
* extensions for VsCode: 
    * Extension pack for java
    * Spring Boot extension pack.

# creating a Spring Boot project

>command-shift-p and click on 
>> **Group id**: identifies the organization (ex: com.example) <br/>
>> **Artifact id**: Name the application (ex: hello-springboots) <br/>
>> Choose **JAR** as the file packaging type.
>> **Dependency**: Software that your application depends on.

# breaking down project
* src/main/java: source code
* src/main/resources: recources
* src/test/java: appication tests

# running spring boot app

command to compile the code(Mac): <br/>
`` ./mvnw spring-boot:run `` <br/> or:
`` ./mvnw clean spring-boot:run `` => Removes previously compiled code and runs it.


# dependencies

a **dependency** is a packaged library of files(i.e **JAR**).
> when you need a dependency Maven looks for it in the Local Repository. If it doesnt find them, Maven will download all the dependencies that it needs from the cental repository and store them in your local repository.