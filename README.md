# ZibNode Installer Packages

This repository contains the latest packages for ZibNode Installer.

## Available Packages

- **Linux**: Latest Linux installers (AppImage, deb, rpm formats)
- **macOS**: Latest DMG installer for macOS ARM
- **Source**: Source code and build artifacts

## Package Index

The latest package information is available in [packages/index.json](packages/index.json).

## Installation

### Linux

#### AppImage (Recommended)
1. Download the appropriate AppImage from the [packages/linux](packages/linux) directory
2. Make it executable: `chmod +x filename.AppImage`
3. Run the installer: `./filename.AppImage`

#### Debian/Ubuntu (.deb)
1. Download the appropriate .deb file from the [packages/linux](packages/linux) directory
2. Install: `sudo dpkg -i filename.deb`
3. Fix dependencies: `sudo apt-get install -f`

#### Red Hat/Fedora (.rpm)
1. Download the appropriate .rpm file from the [packages/linux](packages/linux) directory
2. Install: `sudo rpm -i filename.rpm`

### macOS
1. Download the latest DMG from the [packages/macos](packages/macos) directory
2. Mount the DMG file
3. Drag the application to your Applications folder

## Build Information

- **Last Updated**: 2025-08-27 08:25:12 UTC
- **Commit SHA**: 7977695870581ea3d2291e055c725b90c71fab71
- **Repository**: mediadriveio/electron-app

## GitHub Pages

This repository is configured to serve packages via GitHub Pages at:
https://mediadriveio.github.io/zibnode-packages/
