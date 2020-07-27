# Liferay - Demo Portlet
Demonstration Portlet for Liferay Portal 6.2 CE GA3
### Development
- IntelliJ IDEA Community 2020.1
- Java version: 1.8.0_261 (or OpenJDK-14.0.2)
- Maven version: 3.6.1
- Tomcat version: 7.0.42
### Maven Archetype
```
<archetype>
    <groupId>com.liferay.maven.archetypes</groupId>
    <artifactId>liferay-portlet-archetype</artifactId>
    <version>6.2.1</version>
    <description>Provides an archetype to create Liferay portlets.</description>
</archetype>
```
### Build
```
$ mvn clean install (or mvn package)
```
### Deploy
Liferay Portal must be up and running
```
$ mvn clean install (or mvn package)
$ mvn liferay:deploy
```
