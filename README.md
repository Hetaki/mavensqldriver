# Maven SQL JDBC connecter
Library jdbc sql server

How to use:

1. Import repository in pom.xml

```
  <repository>
    <id>Hetaki-releases</id>
    <url>https://raw.github.com/Hetaki/mavensqldriver/master/releases</url>
  </repository>
```

2. Add dependency

```
  <dependency>
      <groupId>com.microsoft.sqlserver</groupId>
      <artifactId>sqljdbc4</artifactId>
      <version>4.0</version>
  </dependency>
```

3. Maven install dependency

```
  mvn clean install
```
