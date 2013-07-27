
To include closure-stylesheets into you're maven project make these changes to you're pom.xml file:



Add a entry into the `<repositories>` section:

    <repositories>
      <repository>
        <id>StefanLiebenberg-ClosureStylesheets</id>
          <name>ClosureStylesheets</name>
          <releases>
            <enabled>true</enabled>
          </releases>
          <url>https://raw.github.com/StefanLiebenberg/closure-stylesheets/releases</url>
      </repository>
    </repositories>

Add a entry into the `<dependencies>` section:

    <dependencies>
      <dependency>
        <groupId>com.google.javascript</groupId>
        <artifactId>closure-compiler</artifactId>
        <version>v20130722</version>
      </dependency>
    </dependencies>



