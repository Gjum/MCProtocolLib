[![Build Status](https://travis-ci.org/Gjum/MCProtocolLib.svg?branch=1.12.2-LTS)](https://travis-ci.org/Gjum/MCProtocolLib) [![JitPack](https://jitpack.io/v/Gjum/MCProtocolLib.svg)](https://jitpack.io/#Gjum/MCProtocolLib)

# MCProtocolLib 1.12.2 LTS

This repository offers Long-Term Support for 1.12.2 of MCProtocolLib
by cherry-picking any compatible mainline fixes onto the last official 1.12.2 version.

It's only maintained every so often, so if you see a fix that applies to 1.12.2 please open an issue. Thanks!

## How to use this repository

Builds are available through jitpack.io.

Instead of `1.12.2-LTS-SNAPSHOT` (always the latest) you can use any versioned tag.

### Maven

```xml
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>
```

```xml
<dependency>
    <groupId>com.github.Gjum</groupId>
    <artifactId>MCProtocolLib</artifactId>
    <version>1.12.2-LTS-SNAPSHOT</version>
</dependency>
```

### Gradle

```groovy
allprojects {
    repositories {
        // ...
        maven { url 'https://jitpack.io' }
    }
}
```

```groovy
dependencies {
    implementation 'com.github.Gjum:MCProtocolLib:1.12.2-LTS-SNAPSHOT'
}
```

## License

MCProtocolLib is licensed under the **[MIT license](http://www.opensource.org/licenses/mit-license.html)**.
