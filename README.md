# JOML Mod

[JOML](https://github.com/JOML-CI/JOML) repackaged as a Fabric mod for easy inclusion. 

JOML and this mod are both licensed under the MIT License.

To include JOML, add the following (or similar) to your build.gradle.

```gradle
repositories {
 	maven {
    name = "grondag"
    url = "https://grondag-repo.appspot.com"
    credentials {
      username "guest"
       password ""
	  }
  }
}

dependencies {
  modImplementation "grondag:joml-mod:1.0+"
  include "grondag:joml-mod:1.0+"
}
```
