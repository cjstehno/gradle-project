# Gradle Site Plugin


[![Build Status](https://travis-ci.org/cjstehno/gradle-site.svg?branch=master)](https://travis-ci.org/cjstehno/gradle-site) [![Coverage Status](https://coveralls.io/repos/github/cjstehno/gradle-site/badge.svg?branch=master)](https://coveralls.io/github/cjstehno/gradle-site?branch=master)

Gradle plugin providing helpful tools and configuration used to create and manage a project website.

## Quick Links

* Site: http://stehno.com/gradle-site/
* API Docs: http://stehno.com/gradle-site/docs/groovydoc/
* User Guide: http://stehno.com/gradle-site/asciidoc/html5/

## Install

Build script snippet for use in all Gradle versions:

```groovy
buildscript {
  repositories {
    maven {
      url "https://plugins.gradle.org/m2/"
    }
  }
  dependencies {
    classpath "gradle.plugin.com.stehno.gradle:site:0.0.2"
  }
}

apply plugin: "com.stehno.gradle.site"
```

Build script snippet for new, incubating, plugin mechanism introduced in Gradle 2.1:

```groovy
plugins {
  id "com.stehno.gradle.site" version "0.0.2"
}
```

## Usage

See the http://stehno.com/gradle-site/asciidoc/html5/[User Guide] for configuration and usage information.
