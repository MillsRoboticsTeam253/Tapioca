# Tapioca

[![Build Status][GHAction-image]][GHAction-link]
[![LICENSE][LICENSE-image]][LICENSE-link]
[![JitPack][JitPack-image]][JitPack-link]
[![docs][javadocs-image]][javadocs-link]

Ingredients for a Boba Bot.

Javadocs can be found [here][javadocs-link]

## Usage

Gradle is the current build system for WPILib robot projects.

To install, add the following to the root `build.gradle`
```groovy
repositories {
    maven { url 'https://jitpack.io' }
}
```
Then, add Tapioca as a dependency
```groovy
dependencies {
    implementation 'org.bobabots253:Tapioca:2021.1.1' // Replace tag with the latest release if needed
    
    // Alternatively, for the latest version on github
    implementation 'org.bobabots253:Tapioca:master-SNAPSHOT'
}

```

## Contributing

Before you get started with contributing to Tapioca, make sure you read [CONTRIBUTING.md](CONTRIBUTING.md).

Now you can get started:
```shell
# clone the repository
git clone https://github.com/bobabots253/Tapioca.git
# cd into Tapioca
cd Tapioca
# Run tests and build:
./gradlew build
```

[GHAction-image]: https://github.com/bobabots253/Tapioca/workflows/CI/badge.svg?branch=master&event=push
[GHAction-link]: https://github.com/bobabots253/Tapioca/actions?query=event%3Apush+branch%3Amaster
[LICENSE-image]: https://img.shields.io/github/license/bobabots253/Tapioca
[LICENSE-link]: https://github.com/bobabots253/Tapioca/blob/master/LICENSE
[JitPack-image]: https://jitpack.io/v/org.bobabots253/Tapioca.svg
[JitPack-link]: https://jitpack.io/#org.bobabots253/Tapioca
[javadocs-image]: https://github.com/bobabots253/Tapioca/workflows/docs/badge.svg?branch=master&event=push
[javadocs-link]: https://bobabots253.github.io/Tapioca/
