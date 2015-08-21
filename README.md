# Maven repository for Geocore Android API

To use Geocore Client API for Android, add the following repository to the `build.gradle` file:
```groovy
repositories {
    mavenCentral()
    // other repos...
    
    maven { url "https://github.com/geocore/geocore-android-mvn-repo/raw/master/releases" }
}
```
Then add the dependency:
```groovy
dependencies {
    // other dependencies...
    
    compile 'jp.geocore.android:geocore-api-android:0.3.3@aar'
}
```
