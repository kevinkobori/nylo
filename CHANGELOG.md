# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1+1] - 2025-08-25

### Added
- FVM (Flutter Version Management) support with `.fvmrc` file for Flutter `3.29.2`.
- VS Code launch configurations (`launch.json`) for web and mobile debugging.
- VS Code settings (`settings.json`) for code formatting, file nesting, and other developer experience improvements.
- `.cxx` directory to `android/.gitignore`.

### Changed
- **Project Renaming & Configuration:**
    - Default `APP_NAME` changed to `YourAppName` in `.env`.
    - Android `applicationId` updated to `com.example.bundleId`.
    - iOS `PRODUCT_BUNDLE_IDENTIFIER` updated to `com.example.bundleId`.
    - App display name updated to `YourAppName` in `AndroidManifest.xml` and `Info.plist`.
- **Dependencies:**
    - `nylo_framework` upgraded to `~6.8.6`.
    - `nylo_support` upgraded to `~6.28.3`.
- **Code & Features:**
    - Reorganized imports in `home_page.dart`.
    - Updated `PushNotification.sendNotification` call to include a `subtitle`.
