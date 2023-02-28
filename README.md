# Grails Admin Plugin

A powerful and flexible, extensible administration framework and management console for Grails.

## Grails Version

- Grails **4.1.2**

## Usage

### Adding `grails-plugin-admin`

Adding `grails-plugin-admin` plugin to the `build.gradle`,

```gradle

apply plugin: "org.grails.grails-gsp"

repositories {
    maven {
        url "https://s01.oss.sonatype.org/content/repositories/snapshots/"
        mavenContent {
            snapshotsOnly()
        }
    }
}

dependencies {

    // Grails 4
    compile "org.rainboyan.plugins:grails-plugin-dynamic-modules:0.0.1"
    compile "org.rainboyan.plugins:grails-plugin-admin:0.0.1-SNAPSHOT"

    // Grails 5
    implementation "org.rainboyan.plugins:grails-plugin-dynamic-modules:0.0.1"
    implementation "org.rainboyan.plugins:grails-plugin-admin:0.0.1-SNAPSHOT"
}

```

## Development

### Build from source

```
git clone https://github.com/rainboyan/grails-plugin-admin.git
cd grails-plugin-admin
./gradlew publishToMavenLocal
```

## What's New

### 0.0.1-SNAPSHOT

* Support Grails 4.0+


## Known issues


## Links

- [Grails](https://grails.org)
- [Grails Github](https://github.com/grails)
- [Grails Dynamic Modules Plugin](https://github.com/rainboyan/grails-plugin-dynamic-modules)
- [Grails View Components Plugin](https://github.com/rainboyan/grails-plugin-view-components)
