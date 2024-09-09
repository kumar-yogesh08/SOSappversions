Make sure your java version is UpToDate
TroubleShooters:-
./gradlew app:dependencies
./gradlew clean build
important updates:-
Javaversion in app build.gradel.kts javaversion_11
In case of pedro ossrs is deprecated 
pluginManagement {
    repositories {
        google()
        mavenCentral()
        maven { url = uri("https://jitpack.io") }  // Add JitPack here
    }
}

dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
        maven { url = uri("https://jitpack.io") }  // Add JitPack here as well
    }
}
