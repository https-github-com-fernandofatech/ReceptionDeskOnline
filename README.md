![ReceptionDeskOnline](https://user-images.githubusercontent.com/39699305/153957299-8496d3a8-97d4-4100-a986-53e43f9a491d.png)

# Java Web project using Maven repository

###### Make your reception area smart!
###### Sleek tab sign-in brings the delightful experience to your reception and smart features enhance your security and manage your visitor logs in a swift.

 # Why? 
 
 This project is part of my personal portfolio, so, I'll be happy if you could provide me any feedback about the project, code, structure or anything that you can report that could make me a better developer!
 
Email-me: Fernando.tech@icloud.com

Connect with me at [LinkedIn](https://www.linkedin.com/in/fernando-francisco-azevedo/).

www.linkedin.com/in/fernando-francisco-azevedo

Also, you can use this Project as you wish, could it be to study, make improvements or even earn money with it.

It's free!

----------------------------------------------------------------------------
* choose an IDE
1. configure the servers (Toncat or glassfish)

###### to work, just clone the repository then enter the repository configure hibernate.cfg.xml to configure your local mysql bank password. next step is to create a database in mysql (create database ordinance;), then run hibernateTeste.ja to create the tables in the bank, to finish run the project.
----------------------------------------------------------------------------

**Technologies used** 
1. Maven
2. Hibernate
3. PrimeFace
4. JSP

----------------------------------------------------------------------------

```
mvn archetype:generate \
  -DarchetypeGroupId=org.apache.maven.archetypes \
  -DarchetypeArtifactId=maven-archetype-quickstart \
  -Dversion=1.0-SNAPSHOT \
  -DgroupId=com.erkobridee.exemplo.mvn \
  -DartifactId=ExemploMavenDesktop
```

The route to open in eclipse eclipse

```
mvn eclipse:eclipse 
```


### web java

```
mvn archetype:generate \
    -DarchetypeGroupId=org.apache.maven.archetypes \
    -DarchetypeArtifactId=maven-archetype-webapp \
    -Dversion=1.0-SNAPSHOT \
    -DgroupId=com.erkobridee.exemplo.mvn \
    -DartifactId=ExemploMavenWeb
```

The route to open in eclipse eclipse

```
mvn eclipse:eclipse -Dwtpversion=2.0
```

## Commands to use in project

show the dependency tree(.jar)

	mvn depedency:tree 

copy the jar(dependencies) to the target/dependency folder [avoids any environment problems]

	mvn dependency:copy-dependencies

compile the project

	mvn compile

run the tests

	mvn test 

gerar os .jars , often used in ear projects

	mvn package 

clear all dependencies(.jars)

	mvn clean 

find all the commands you gave to maven

	history | grep mvn 

best practice adopted to generate the project's deployment package

	mvn clean install


## Useful links

* [Introduction to the Build Lifecycle](http://maven.apache.org/guides/introduction/introduction-to-the-lifecycle.html)

* [maven em 5 minutos](http://maven.apache.org/guides/getting-started/maven-in-five-minutes.html)

* [iniciando com maven](http://maven.apache.org/guides/getting-started/index.html)


* [Introduction to Archetypes](http://maven.apache.org/guides/introduction/introduction-to-archetypes.html)


* [Archetypes List](http://docs.codehaus.org/display/MAVENUSER/Archetypes+List)

* [repositório do Maven](http://mvnrepository.com/)


## FLEX MOJOS

Flex : Creates a simple SWC project

```    
mvn \
    archetype:generate \
    -DarchetypeRepository=http://repository.sonatype.org/content/groups/flexgroup/ \
    -DarchetypeGroupId=org.sonatype.flexmojos \
    -DarchetypeArtifactId=flexmojos-archetypes-library \
    -DarchetypeVersion=3.6.1 \
    -Dversion=1.0-SNAPSHOT \
    -DgroupId=com.erkobridee.exemplo.mvn \
    -DartifactId=ExemploMavenFlexLib
```    
    
Flex : Creates a simple SWF project

```
mvn \
    archetype:generate \
    -DarchetypeRepository=http://repository.sonatype.org/content/groups/flexgroup/ \
    -DarchetypeGroupId=org.sonatype.flexmojos \
    -DarchetypeArtifactId=flexmojos-archetypes-application \
    -DarchetypeVersion=3.6.1 \
    -Dversion=1.0-SNAPSHOT \
    -DgroupId=com.erkobridee.exemplo.mvn \
    -DartifactId=ExemploMavenFlexApp
```

Flex : Creates a modular project containing one SWC, one SWF and one WAR

```
mvn \
    archetype:generate \
    -DarchetypeRepository=http://repository.sonatype.org/content/groups/flexgroup/ \
    -DarchetypeGroupId=org.sonatype.flexmojos \
    -DarchetypeArtifactId=flexmojos-archetypes-modular-webapp \
    -DarchetypeVersion=3.6.1 \
    -Dversion=1.0-SNAPSHOT \
    -DgroupId=com.erkobridee.exemplo.mvn \
    -DartifactId=ExemploMavenFlexModular
```    


useful commands

```
mvn clean install -DskipTests=true

mvn flexmojos:flexbuilder
``` 

* [Flexmojos - Available archetypes](https://docs.sonatype.org/display/FLEXMOJOS/Available+archetypes)

* [Compiling flex with maven 2](http://mayboroda.blogspot.com/2009/07/compiling-flex-with-maven-2-flexmojos.html)


```
MIT License

Copyright (c) 2021 Fernando Azevedo

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

