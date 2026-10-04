# UofSdkJava Maven repository

Public Maven repository for the Unified Odds SDK (`com.testinzone.unifiedodds.sdk:unified-feed-sdk`).
It contains only the compiled jar and POM. No GitHub token is needed to consume it.

## Maven

```xml
<repositories>
  <repository>
    <id>testinzone</id>
    <url>https://testinzone.github.io/UofSdkJava-maven-repo</url>
    <snapshots><enabled>true</enabled></snapshots>
  </repository>
</repositories>

<dependency>
  <groupId>com.testinzone.unifiedodds.sdk</groupId>
  <artifactId>unified-feed-sdk</artifactId>
  <version>3.3.0-SNAPSHOT</version>
</dependency>
```

## Gradle

```groovy
repositories {
    mavenCentral()
    maven { url 'https://testinzone.github.io/UofSdkJava-maven-repo' }
}

dependencies {
    implementation 'com.testinzone.unifiedodds.sdk:unified-feed-sdk:3.3.0-SNAPSHOT'
}
```

If GitHub Pages is not enabled, `https://raw.githubusercontent.com/testinzone/UofSdkJava-maven-repo/main` works as the URL too.
