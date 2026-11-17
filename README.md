# Matrix Maven Mirror

Public static Maven fallback mirror for third-party Android ad SDK artifacts (e.g. `com.pangle.global:pag-sdk:8.2.0.4`).

## Gradle Usage (`settings.gradle.kts`)

```kotlin
maven {
    url = uri("https://raw.githubusercontent.com/ylai18117-gif/matrix-maven-mirror/main/m2")
    content {
        includeGroupByRegex("com\\.pangle.*")
    }
}
```
