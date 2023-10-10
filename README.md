# allset-java

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Project status](https://img.shields.io/badge/Project%20status-Maintenance-orange.svg)](https://img.shields.io/badge/Project%20status-Maintenance-orange.svg)

# Project status

I change this project constantly improving and adding new plugins, click [here](docs/STATUS.md) to follow up.

# About

This is a build tools ([maven](https://github.com/apache/maven)) configurations for different types of projects that I already worked on.
The idea is to reuse build tools and their plugins (pmd, spotbugs, compiler, etc.) configurations to speed up the development.
This project prevents the developer from reconfiguring the same basic features that most projects have.

# Technologies

Technologies used on this project:

- Git
- Java
- Ant (optional)
- Maven
- Gradle

# Requirements

These are the requirements:

- Git

```bash
# check the git version
git --version
```

- Java version >= 17 

```bash
# check the Java version
java --version
```

- Maven version >= 3.8.8

```bash
# check the Maven version
mvn --version
```

- Ant version >= 1.10 (Optional)

```bash
# check the Ant version
ant -version
```

# Install

To install just execute on terminal:
 
```bash
git clone https://github.com/fernando-romulo-silva/allset-java
```

Access the project folder:

```bash
cd allset-java
```

To install maven version:

```bash
mvn install
```

# How to Use

You can use it with [Maven](docs/INSTALL-MAVEN.md) or [Gradle](docs/INSTALL-GRADLE.md).

# Modules

The main pom deals with all Java application types, but for specific application types, these POMs was created:

## allset-java-se

Configurations used on maven plugins for executable Java SE, please check [here](docs/ALL-SET-JAVA-SE-MAVEN.md) for Maven user or here for Gradle users.
