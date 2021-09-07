# allset-java

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Project status](https://img.shields.io/badge/Project%20status-Maintenance-orange.svg)](https://img.shields.io/badge/Project%20status-Maintenance-orange.svg)

Set of [maven](https://github.com/apache/maven) configurations for types of projects that I already worked on.
On the main pom.xml, there are a lot of plugin configurations used on my projects.


## Project status

I use this project to learn new technologies maven.

# Technologies
- Java
- Maven

# Modules

## allset-java-ee-full

Configurations used on maven plugins for Jakarta EE full profile.

## allset-java-ee-webprofile

Configurations used on maven plugins for Jakarta EE web profile.

## allset-java-ee-se

Configurations used on maven plugins for Java SE.

## allset-java-ee-web

Configurations used on maven plugins for Jakarta EE Web.

# Install

requirements (environment variables configured): 
 - Java 11
 - Maven 3
 - Git
 
 ```bash
# clone it
git clone https://github.com/fernando-romulo-silva/allset-java

# access the project folder
cd allset-java

# execute
mvn install
```

# How to Use

In the pom.xml, add the following xml between `<project> ... </project>`

```xml
<parent>
	<groupId>org.allset.java</groupId>
	<artifactId>allset-java</artifactId>
	<version>${allset-java-version}</version>
</parent>
```


mvn install:install-file -DgroupId=com.sun -DartifactId=tools -Dpackaging=jar -Dversion=1.8 -Dfile="$JAVA_HOME/lib/tools.jar"
