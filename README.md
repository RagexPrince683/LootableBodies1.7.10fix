# DrCyano's Lootable Bodies
A death-chest mod for Minecraft

## Requirements
This branch requires Minecraft 1.7.10 with Forge 10.13.4.1614.

## Installing
After you have successfully installed Forge, simply place the file *lootable-bodies-#.#.jar* in your *mods* folder. You can get the lootable-bodies-#.#.jar file from the Releases tab of this repository page.

## Building from source
This Minecraft 1.7.10 branch uses ForgeGradle 1.2, which requires the Gradle
2.x API. Use Java 8 and the included wrapper rather than a system Gradle
installation:

```text
gradlew.bat build
```

On Linux or macOS, use `./gradlew build`. The wrapper downloads Gradle 2.14.1,
the newest Gradle 2.x release, so ForgeGradle can read the configured Minecraft
version while applying the `forge` plugin.
