[![Build Status](https://travis-ci.org/Gjum/MCProtocolLib.svg?branch=1.12.2-LTS)](https://travis-ci.org/Gjum/MCProtocolLib) [![JitPack](https://jitpack.io/v/Gjum/MCProtocolLib.svg)](https://jitpack.io/#Gjum/MCProtocolLib)

# MCProtocolLib 1.12.2 LTS

This repository offers Long-Term Support for 1.12.2 of MCProtocolLib
by cherry-picking any compatible mainline fixes onto the last official 1.12.2 version.

It's only maintained every so often, so if you see a fix that applies to 1.12.2 please [open an issue][new-issue]. Thanks!

[new-issue]: https://github.com/Gjum/MCProtocolLib/issues/new

## How to use this repository

Builds are available through [jitpack.io][jitpack-mcpl]'s Maven repository under group id `com.github.Gjum` and artifact id `MCProtocolLib`.

[jitpack-mcpl]: https://jitpack.io/#Gjum/MCProtocolLib

Instead of `1.12.2-LTS-SNAPSHOT` (always the latest) you can depend on a fixed version by referring to its tag, for example `1.12.2-LTS-1.0`.
You can see all available versions on the [releases page](https://github.com/Gjum/MCProtocolLib/releases).

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
