# GoofyAddons

## Setup

This project targets Minecraft **26.2** with Fabric Loader **0.19.5** and Fabric API **0.161.0+26.2**. Development uses JDK **25**, Fabric Loom **1.17.21**, and the Gradle **9.5.1** wrapper.

In IntelliJ IDEA, reload the Gradle project after pulling changes, select JDK 25 for the project SDK and Gradle JVM, and use the Gradle wrapper.

Build on Windows with PowerShell:

```powershell
.\gradlew.bat build
```

The installable mod is `build/libs/goofyaddons-1.0.4-STABLE+mc26.2.jar`. Use it in a Minecraft 26.2 instance with Fabric Loader 0.19.5 or newer and Fabric API 0.161.0+26.2. The `-sources.jar` is for development.

Launch the development client with:

```powershell
.\gradlew.bat runClient
```

DevAuth is a development runtime dependency and is not bundled in the mod jar. It remains disabled unless explicitly configured.

This port updates Minecraft compatibility; the existing automation still needs the planned refactor and gameplay validation.

## License

This template is available under the CC0 license. Feel free to learn from it and incorporate it in your own projects.
