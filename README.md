
To include closure-stylesheets into you're maven project make these changes to you're pom.xml file:



Add a entry into the `<repositories>` section:

    <repository>
      <name>Github - Stefan Liebenberg</name>
      <id>github-StefanLiebenberg</id>
      <releases>
        <enabled>true</enabled>
      </releases>
      <url>https://raw.github.com/StefanLiebenberg/maven/releases</url>
    </repository>


Add a entry into the `<dependencies>` section:

    <dependencies>
      <dependency>
        <groupId>com.google.javascript</groupId>
        <artifactId>closure-compiler</artifactId>
        <version>v20130722</version>
      </dependency>
    </dependencies>



