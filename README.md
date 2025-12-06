# pixelplay vanilla

this is a fork of pixelplay that works entirely without google play services.
more features are coming soon, including the removal of ai features.

you can install the apk from the [releases](https://github.com/dhaneshdutta/PixelPlay-vanilla/releases) tab.

## installation

### prerequisites
- jdk 17
- android studio iguana or newer

### build instructions

1. clone the repo
   ```bash
   git clone https://github.com/dhaneshdutta/PixelPlay-vanilla.git
   cd PixelPlay-vanilla
   ```

2. build the apk
   ```bash
   ./gradlew assembleDebug -Dorg.gradle.java.home="/path/to/your/jdk-17"
   ```

3. install
   ```bash
   adb install app/build/outputs/apk/debug/app-debug.apk
   ```
