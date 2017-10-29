Files that need to be created in a Gradle based project
```
build.gradle        => Basic gradle build file
gradle.properties   => Add properties to the gradle build file
settings.gradle     => Used as a top level file (along with another build.gradle file) for multi-project builds
```
Cache location for all files downloaded for Gradle
```
~/.gradle/caches    => Local caches of all downloads from repositories.  SHA1 based for checking for re-downloads
```