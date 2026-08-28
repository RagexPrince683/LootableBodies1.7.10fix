# DrCyano's Lootable Bodies
A death-chest mod for Minecraft

## Requirements
This branch requires Minecraft 1.7.10 with Forge 10.13.4.1614.

## Installing
After you have successfully installed Forge, simply place the file *lootable-bodies-#.#.jar* in your *mods* folder. You can get the lootable-bodies-#.#.jar file from the Releases tab of this repository page.

## Building from source
This Minecraft 1.7.10 branch uses RetroFuturaGradle so that it can build with
the included Gradle 8.11.1 wrapper. Run Gradle itself with Java 17 or newer;
RetroFuturaGradle configures the Minecraft source compilation appropriately.
Use the wrapper rather than a system Gradle installation:

```text
gradlew.bat build
```

On Linux or macOS, use `./gradlew build`. The first run downloads the Gradle
distribution, RetroFuturaGradle, and the Minecraft/Forge development
dependencies.
