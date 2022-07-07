---
description: Introduction to the application
---

# Getting Started

Primate (formerly named as KongDash) is a desktop client for Kong Admin API.

![Screenshot](https://www.getprimate.xyz/image/ft-dashboard-dark.png)

## Install Primate

Primate binaries are available for all major desktop operating systems including Windows, macOS and Linux.

The latest version can be obtained from [https://www.getprimate.xyz/download](https://www.getprimate.xyz/download)

Alternatively, you can browse all releases here [https://github.com/getprimate/primate/releases](https://github.com/getprimate/primate/releases)

#### **Windows**

Download the executable installer for Windows and run it.

Follow the instructions in the setup wizard.

#### **macOS**

Download the DMG image and open it.

Once the image is mounted, the finder window will pop-up. Simply drag the primate icon to the Applications folder.

#### Linux

On Linux based distributions, Primate can be installed as an AppImage, a Snap package or by downloading and extracting the tarball (tar.gz) archive.

**AppImage**

Download the latest AppImage, move it to a desired location - preferably the `/opt` directory.

Make the AppImage excecutable and run it.

```bash
sudo mv Primate-v1.0.0-x64.AppImage /opt
sudo chmod a+x /opt/Primate-v1.0.0-x64.AppImage
./opt/Primate-v1.0.0-x64.AppImage
```

**Snapcraft**

Primate is available in Snapcraft. Most of the recent Ubuntu releases, KDE Neon, Manjaro and Zorin OS comes with Snap pre-installed. If your operating system does not have Snap setup, please read [https://snapcraft.io/docs/installing-snapd](https://snapcraft.io/docs/installing-snapd)

```bash
sudo snap install primate
```

**Tarball Archive**

Alternatively, you can get Primate via tar.gz archive.

Download the latest tarball archive, extract it and move the contents to a desired location - preferably the `/opt` directory.
