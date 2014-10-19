android-support-v4-preferencefragment
=====================================

Unofficial PreferenceFragment compatibility layer for Android 1.6 and up. Includes resources so add this as a library project to your project.

How to use
==========

Simply add the repository to your build.gradle file:

```groovy
repositories {
    maven {
        url 'http://maven.arcao.com/'
    }
    mavenCentral()
}
```

And you can use the artifact like this:

```groovy
dependencies {
    compile 'com.android.support:support-v4-preferencefragment:1.0.0-1@aar'
}
```

Then follow the [Settings developer guide](http://developer.android.com/guide/topics/ui/settings.html) but use:

```java
import android.support.v4.preference.PreferenceFragment;
```

instead of

```java
import android.preference.PreferenceFragment;
```

