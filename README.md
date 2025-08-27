# ZibNode Packages

This repository contains the latest packages for ZibNode Installer, automatically built and published from the [electron-app](https://github.com/mediadriveio/electron-app) repository.

## 📦 Available Packages

- **Linux**: Latest Linux installers (AppImage, deb, rpm formats)
- **macOS**: Latest DMG installer for macOS ARM
- **Source**: Source code and build artifacts

## 🚀 Installation

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

## 📋 Package Information

The latest package information is available in [packages/index.json](packages/index.json).

## 🔗 Links

- **GitHub Pages**: https://mediadriveio.github.io/zibnode-packages/
- **Source Repository**: https://github.com/mediadriveio/electron-app
- **Latest Releases**: https://github.com/mediadriveio/zibnode-packages/releases

## 🔄 Automatic Updates

This repository is automatically updated when:
1. Code is pushed to the `main` branch in the [electron-app](https://github.com/mediadriveio/electron-app) repository
2. Build workflows complete successfully
3. Packages are pushed to the `gh-pages` branch
4. GitHub releases are automatically created with all packages

## 📊 Build Information

- **Last Updated**: See [packages/index.json](packages/index.json) for the latest build information
- **Source Repository**: [mediadriveio/electron-app](https://github.com/mediadriveio/electron-app)
- **Build Status**: [![Build Status](https://github.com/mediadriveio/electron-app/workflows/Build%20Linux%20Package/badge.svg)](https://github.com/mediadriveio/electron-app/actions)

---

*This repository is automatically maintained by GitHub Actions workflows.*
