# allset-java

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Project status](https://img.shields.io/badge/Project%20status-Maintenance-orange.svg)](https://img.shields.io/badge/Project%20status-Maintenance-orange.svg)

# Project status

I change this project constantly improving and adding new plugins, click [here](docs/STATUS.md) to follow up.

# About

Set of build tools ([maven](https://github.com/apache/maven)) configurations for different types of projects that I already worked on.
The idea is to reuse build tools and their plugins (pmd, spotbugs, compiler, etc.) configurations to speed up the development.
This project prevents the developer from reconfiguring the same basic features that most projects have.

# Technologies

- Java
- Ant (optional)
- Maven
- Gradle

# Requirements

- Git
- Java version >= 17 
- Ant version >= 1.10
- Maven version >= 3.9


# Install

To install just execute on terminal:
 
```bash
git clone https://github.com/fernando-romulo-silva/allset-java
```

Access the project folder:

```bash
cd allset-java
```

Then execute execute:

```bash
mvn install
```

# How to Use

To use follow the instructions.

## Maven

In the pom.xml, add the following xml between `<project> ... </project>`

```xml
<parent>
	<groupId>org.allset.java</groupId>
	<artifactId>allset-java</artifactId>
	<version>${allset-java-version}</version>
</parent>
```

This is the list of plugins configured:

Basic plugins:

- maven compiler
- maven javadoc
- maven jar
- maven release
- maven source
- maven resources
- maven dependency

Plugins for tests:
- maven failsake
- maven surefire
- jacoco maven

Plugins for SCM:
- maven scm
- maven scm publish

Plugins for project reports:
- maven site
- maven project info report
- maven jxr
- taglist maven
- jdepend maven

Plugins for tools:
- pmd maven
- spotbugs maven
- checkstyle maven

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

