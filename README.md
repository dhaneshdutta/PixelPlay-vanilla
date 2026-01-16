# Pixel Player (Vanilla)

A clean, ad-free, and privacy-focused music player. This is a degoogled fork of Pixel Player, minimalised to focus purely on providing a beautiful music listening experience without any AI or GMS dependencies.

## Features
- **Privacy Focused**: No tracking, no internet permissions required for core functionality.
- **De-googled**: Completely removed all Google Mobile Services (GMS) dependencies.
- **Minimalist**: Removed "Smart" AI features for a lightweight, faster experience.
- **Beautiful UI**: Modern Material Design 3 interface with dynamic colors.

## Installation
You can install the latest release APK from the [Releases](url-to-releases) page or build it yourself.

## Build Instructions

### Prerequisites
- JDK 17 or higher
- Android SDK

### Build
1. Clone the repository:
   ```bash
   git clone https://github.com/dhaneshdutta/PixelPlayer-vanilla.git
   cd PixelPlayer-vanilla
   ```

2. Build the release APK:
   ```bash
   ./gradlew assembleRelease
   ```

The APK will be located at `app/build/outputs/apk/release/app-release.apk`.
