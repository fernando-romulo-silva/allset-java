# allset-java

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Project status](https://img.shields.io/badge/Project%20status-Maintenance-orange.svg)](https://img.shields.io/badge/Project%20status-Maintenance-orange.svg)

Set of build tools ([maven](https://github.com/apache/maven)) configurations for different types of projects that I already worked on.
The idea is to reuse build tools and their plugin (pmd, spotbugs, compiler, etc.) configurations to speed up the development.
This project prevents the developer from reconfiguring the same basic features that most projects have.

## Project status

I use this project to learn new technologies maven.

# Technologies
- Git
- Java >= 7 
- Maven >= 3


# Install

To install just execute on terminal:
 
```bash
$ git clone https://github.com/fernando-romulo-silva/allset-java
```

Access the project folder:

```bash
$ cd allset-java
```

Then execute execute:

```bash
$ mvn install
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

# Modules

## allset-java-ee-coreprofile

Configurations used on maven plugins for Jakarta EE core profile.

## allset-java-ee-microprofile

Configurations used on maven plugins for Jakarta EE micro profile.

## allset-java-ee-webprofile

Configurations used on maven plugins for Jakarta EE web profile.

## allset-java-ee-full

Configurations used on maven plugins for Jakarta EE full profile.

## allset-java-se

Configurations used on maven plugins for Java SE.

