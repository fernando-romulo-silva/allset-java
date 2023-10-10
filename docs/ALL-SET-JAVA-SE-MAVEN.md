# allset-java-se

## Install

In the pom.xml, add the following xml between `<project> ... </project>`

```xml
<parent>
	<groupId>org.allset.java</groupId>
	<artifactId>allset-java-se</artifactId>
	<version>${allset-java-version}</version>
</parent>
```

Since it is configured on 'build.pluginManagement.plugins' section, you have to add the plugins on build.plugins:

```xml
<build>
	<plugins>
		<plugin>
			<groupId>org.apache.maven.plugins</groupId>
			<artifactId>maven-compiler-plugin</artifactId>
		</plugin>

		<plugin>
			<groupId>org.apache.maven.plugins</groupId>
			<artifactId>maven-dependency-plugin</artifactId>
		</plugin>
	</plugins>
</build>
```

## Use

Replace the property 'maven.jar.plugin.main.class' to your application main class:

```xml
<properties>

	<maven.jar.plugin.main.class>org.yourProject.MainClass</maven.jar.plugin.main.class>
	
</properties>
```

These are the plugins configured:

- maven-jar-plugin (Generate a executable jar)
- maven-dependency-plugin (Put the projects jars in 'libs' folder)