[![license](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg?style=flat)](http://www.apache.org/licenses/LICENSE-2.0)
[![Build Status](https://travis-ci.org/balvi/translation-de.svg?branch=master)](https://travis-ci.org/balvi/translation-de.svg?branch=master)

# translation-de
German translation of CUBA Platform implemented as application component

## Installation

1. Add the following maven repository `https://dl.bintray.com/balvi/cuba-components` to the build.gradle of your CUBA application:

```groovy
    buildscript {
        
        //...
        
        repositories {
        
            // ...
        
            maven {
                url  "https://dl.bintray.com/balvi/cuba-components"
            }
        }
        
        // ...
    }
```

2. Select a version of the add-on which is compatible with the platform version used in your project:

| Platform Version | Add-on Version |
| ---------------- | -------------- |
| 6.8.x            | 1.1.x          |
| 6.7.x            | 1.0.x          |

The latest version is: `1.1.0`

Add custom application component to your project:

* Artifact group: `de.balvi.cuba.translationde`
* Artifact name: `translation-de-global`
* Version: *add-on version*

```groovy
dependencies {
  appComponent("de.balvi.cuba.translationde:translation-de-global:1.0.2")
  [...]
}
```
