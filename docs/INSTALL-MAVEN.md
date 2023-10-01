# Install Maven Version

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
