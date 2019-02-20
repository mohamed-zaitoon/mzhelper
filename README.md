
# mzlibs


[![](https://jitpack.io/v/io.github.mohamed-zaitoon/mzlibs.svg)](http://gestyy.com/wBTPXi)


An Android library that provides most of used in one Class.


## Download

```java
android {
    /* Android Gradle Plugin 3.0.0+ is required to support Java 8 desugaring */
    compileOptions {
        sourceCompatibility JavaVersion.VERSION_1_8
        targetCompatibility JavaVersion.VERSION_1_8
    }
}
repositories {
    maven { url 'https://jitpack.io' }
}
dependencies {


 implementation 'io.github.mohamed-zaitoon:mzlibs:4.2.3'
 
}
```
## Tutorial
 For Tutorial Visit:
 [Docs](docs)
 
## Progaurd
 In progaurd-rules.pro add this lines:
 ```txt
-keepclassmembers class com.tony.** {*; }
-keep public class com.tony.** { *;}
-keepclassmembers interface com.tony.** {*;}
-keep public interface com.tony.** {*;}
 
```

## License 
```txt
   Copyright © 2018 Tony, Inc. 

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

 
 

