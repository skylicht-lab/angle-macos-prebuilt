# ANGLE Prebuilt for Skylicht Engine

This repository provides pre-built [ANGLE](https://github.com/google/angle) (Almost Native Graphics Layer Engine) binaries specifically configured for use with the [Skylicht Engine](https://github.com/skylicht-lab/skylicht-engine).

## Supported Platforms

The binaries are built for Apple platforms with **Apple Silicon (arm64)** architecture:

- **macOS** (arm64)
- **iOS** (arm64)
- **iOS Simulator** (arm64)

## Build Configuration

- **Backend**: Metal (optimized for Apple platforms)
- **Target Libraries**: `libEGL`, `libGLESv2`
- **Build Type**: Release

## Usage

These binaries are used in Skylicht Engine projects to provide OpenGL ES support on top of the Metal backend. For implementation details, refer to the [Skylicht Engine Angle projects](https://github.com/skylicht-lab/skylicht-engine/tree/master/Projects/Angle).