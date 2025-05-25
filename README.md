![Screenshot from 2025-05-11 07-08-38](https://github.com/user-attachments/assets/a2609ec0-e390-4090-98ec-73cac5060836)
[![Status](https://img.shields.io/badge/Status-Stable-green.svg)](https://github.com/nialwrt/UNIVERSAL-NIALWRT)
[![License](https://img.shields.io/badge/License-GPLv2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.html)
[![Maintenance](https://img.shields.io/badge/Maintained-Yes-brightgreen.svg)](https://github.com/nialwrt/UNIVERSAL-NIALWRT)
# UNIVERSAL-NIALWRT Firmware Builder

## Overview
UNIVERSAL-NIALWRT is a versatile OpenWrt build script offering support for multiple distributions: OpenWrt, and ImmortalWrt. It aims to provide a streamlined and user-friendly experience for building custom firmware.

## Features
* **Multi-Distribution Support:** Enables building firmware for OpenWrt and ImmortalWrt.
* **Automated Build Process:** Simplifies the entire build from dependency installation to the final firmware image.
* **Smart Feed Management:** Includes automated handling of package feeds.
* **Branch/Tag Selection:** Supports building from specific branches or tags of the chosen distribution.
* **Customizable via Menuconfig:** Allows full customization of the build configuration.

## Requirements
* Internet connection
* Ubuntu 22.04 LTS or newer
* Adequate disk space and RAM
* Basic terminal usage knowledge

## Quick Installation
```bash
wget https://raw.githubusercontent.com/nialwrt/UNIVERSAL-NIALWRT/main/universal-nialwrt.sh && chmod +x universal-nialwrt.sh && ./universal-nialwrt.sh
