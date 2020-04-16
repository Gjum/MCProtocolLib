[![Build Status](https://travis-ci.com/Gjum/MCProtocolLib-1.12.2-LTS.svg?branch=master)](https://travis-ci.com/Gjum/MCProtocolLib-1.12.2-LTS) [![JCenter/Bintray](https://api.bintray.com/packages/gjum/minecraft/MCProtocolLib-1.12.2-LTS/images/download.svg)](https://bintray.com/gjum/minecraft/MCProtocolLib-1.12.2-LTS/_latestVersion)

# MCProtocolLib 1.12.2 LTS

This repository offers Long-Term Support for 1.12.2 of MCProtocolLib
by cherry-picking any compatible mainline fixes onto the last official 1.12.2 version.

It's only maintained every so often, so if you see a fix that applies to 1.12.2 please [open an issue][new-issue]. Thanks!

[new-issue]: https://github.com/Gjum/MCProtocolLib-1.12.2-LTS/issues/new

## How to use this repository

Builds are available through the [JCenter Maven repository][jcenter-mcpl] under group id `com.github.Gjum` and artifact id `MCProtocolLib-1.12.2-LTS`.

[jcenter-mcpl]: https://bintray.com/gjum/minecraft/MCProtocolLib-1.12.2-LTS

Instead of `1.0.0` you can depend on any tag or get the latest snapshot of a branch, for example `master-SNAPSHOT`.
You can see all available versions on the [releases page](https://github.com/Gjum/MCProtocolLib-1.12.2-LTS/releases)
and all branches on the [branches page](https://github.com/Gjum/MCProtocolLib-1.12.2-LTS/branches).

### Maven

```xml
<repositories>
    <repository>
        <id>jcenter</id>
        <url>https://jcenter.bintray.com</url>
    </repository>
</repositories>
```

```xml
<dependency>
    <groupId>com.github.Gjum</groupId>
    <artifactId>MCProtocolLib-1.12.2-LTS</artifactId>
    <version>1.0.0</version>
</dependency>
```

### Gradle

```groovy
allprojects {
    repositories {
        maven { url 'https://jcenter.bintray.com' }
    }
}
```

```groovy
dependencies {
    implementation 'com.github.Gjum:MCProtocolLib-1.12.2-LTS:1.0.0'
}
```

## License

MCProtocolLib is licensed under the **[MIT license](http://www.opensource.org/licenses/mit-license.html)**.
