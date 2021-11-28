# RackMonthPicker
Fork for fixing unmaintained library - https://github.com/kal72/RackMonthPicker

Check the official library for documentation/how to use

Download
--------
Download via Maven:

Add the JitPack repository to your build file
```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>
```
Add the dependency
```xml
<dependency>
        <groupId>com.github.dario-traceon</groupId>
        <artifactId>RackMonthPicker</artifactId>
        <version>1.6.2</version>
</dependency>
```

via Gradle:

Add it in your root build.gradle at the end of repositories
```groovy
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```
Add the dependency
```groovy
dependencies {
        implementation 'com.github.dario-traceon:RackMonthPicker:1.6.2'
}
```
