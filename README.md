# ACI Android
Agile Computing Infrastructure Releases for Android

You can find source code and more information on the [nomads](https://github.com/ihmc/nomads) repo.

If building for the JDK please refer to the [ACI repository](https://github.com/ihmc/aci)

## Gradle
Add [jitpack](https://jitpack.io/) repository:
```
repositories {
    ...
    maven { url "https://jitpack.io" }
}
```
Include dependency:
```
dependencies {
   ...
   compile 'com.github.ihmc:aci-android:v1.1'
}
```
## Dependencies
If not included already you will also need
- slf4j (`'org.slf4j', name: 'slf4j-api', version: '1.7.25'`)

If using OpenDocument chunking features you need to include the dependencies as follows:
- robolectric-0 ('org.robolectric:android-all:7.1.0_r7-robolectric-0'`)
- poi-android.jar
