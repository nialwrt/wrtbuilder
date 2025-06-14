# WRTBUILDER

## Overview
**WRTBUILDER** is a versatile OpenWrt build script supporting multiple distributions: OpenWrt and ImmortalWrt. It provides a streamlined, user-friendly experience for building custom firmware images.

## Features
- **Multi-Distribution Support:** Build firmware for OpenWrt and ImmortalWrt.
- **Automated Build Process:** Handles everything from dependency installation to generating the final firmware image.
- **Smart Feed Management:** Automatically manages package feeds.
- **Branch/Tag Selection:** Build from specific branches or tags.
- **Customizable via Menuconfig:** Full control over build configurations.

## Requirements
- Internet connection
- Ubuntu 22.04 LTS or newer
- Adequate disk space and RAM
- Basic terminal usage knowledge

## Quick Installation
```bash
wget https://github.com/nialwrt/wrtbuilder.git && chmod +x wrtbuilder.sh && ./wrtbuilder.sh
