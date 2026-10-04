# KingNet

KingNet is an Android WireGuard client built with Jetpack Compose.

## Features
- Import real WireGuard `.conf` files through Android's document picker.
- Validate and normalize imported configurations with the WireGuard tunnel library.
- Request Android VPN permission before connecting.
- Start and stop a real WireGuard userspace tunnel using `GoBackend`.
- Persist imported profiles locally for later use.

## Build on GitHub
The repository includes `.github/workflows/build-apk.yml`. Push the project files to GitHub, open **Actions**, run **Build KingNet APK**, and download the APK from the workflow artifact.

The project uses the official WireGuard Android tunnel library published on Maven Central.
