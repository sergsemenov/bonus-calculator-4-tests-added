## What's new

* surefire plugin renewed in pom.xml from 2.22.2 to 3.0.0-M4
```xml                
<dependencies>

//some code skipped

<!-- https://mvnrepository.com/artifact/org.apache.maven.plugins/maven-surefire-plugin -->
  <dependency>
      <groupId>org.apache.maven.plugins</groupId>
      <artifactId>maven-surefire-plugin</artifactId>
      <version>3.0.0-M4</version>
  </dependency>
</dependencies>
<build>
        <plugins>
            <plugin>
                <artifactId>maven-surefire-plugin</artifactId>
                <version>3.0.0-M4</version>
            </plugin>
        </plugins>
    </build>
```
* two tests for unregistered users added
