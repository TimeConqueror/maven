# Time_Conqueror's Maven

How to connect it with build.gradle:

Quite simply, add this repository to your `build.gradle` as following:
```gradle
repositories {
    maven {
        name = "TimeConqueror's Maven"
        url = "https://raw.github.com/TimeConqueror/maven/master"
    }
}
```