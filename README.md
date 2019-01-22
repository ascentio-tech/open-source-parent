# open-source-parent [![](https://jitpack.io/v/ascentio-tech/open-source-parent.svg)](https://jitpack.io/#ascentio-tech/open-source-parent)

Maven parent for Open Source projects 

## How to use it?

1. Add the JitPack [repository](https://maven.apache.org/guides/introduction/introduction-to-repositories.html) to your build file

```xml
  <repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
  </repositories>
```

2. Configure parent on your build file

```xml
  <parent>
    <groupId>io.github.ascentio-tech</groupId>
    <artifactId>open-source-parent</artifactId>
    <version>master-SNAPSHOT</version>
  </parent>
```

The example is using `master-SNAPSHOT` which points to `master` branch. You could also use any sha1 revision, branch or tag as version.


3. Test it: `mvn package`

