icon-version
============

Android gradle plugin that adds version and flavor name to all debug icons.

```groovy
buildscript {
  repositories {
    mavenCentral()
    jcenter()
  }

  dependencies {
    classpath 'pl.itako:icon-version:1.0.0'
  }
}

apply plugin: 'com.android.application'
apply plugin: 'icon-version'
```

When you apply the plugin and install an app all debug version icons will have flavour, build type and version name.

![Screenshot](doc/icon-version-screenshot.png)

License
--------

Copyright 2014 Arkadiusz Konior

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
