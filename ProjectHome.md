A slightly more "open" and flexible telnetd build which adds to the open source telnetd library.

Source code is mavenised.

This version fixes the thread read/write blocking of the original telnetd 2.0 component.

Original project on sourceforge.

**You can now add this dependency via Maven**

Add the following maven repository to your pom.xml:
```
  <repositories>
    ...
    <repository>
      <id>maven2-repository.dev.java.net</id>
      <name>Java.net Repository for Maven</name>
      <url>http://download.java.net/maven/2/</url>
    </repository>
  </repositories>

```

And then add the following dependency:

```
    <dependency>
	<groupId>net.wimpi</groupId>
	<artifactId>telnetd-x</artifactId>
	<version>2.1.1</version>
    </dependency>

```