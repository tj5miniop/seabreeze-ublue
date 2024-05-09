# Welcome to My Custom Aurora-DX and Bazzite Builds

********NOTICE - If you are looking for the Steam Deck Gaming image - it has now been moved to https://github.com/tj5miniop/seabreeze-gamer-deck due to the images collectively using up to much storage on GitHub*******


## Overview

This repo contains my custom builds of Universal Blue's Aurora-DX and Bazzite atomic desktops. Each have been made to suit my needs and may suit yours as well!

### Key Features 

- Virtualization with QEMU available on all editions, except for the Steam Deck image
- Tools pre-installed on the Aurora-based images
- Papirus icon theme and Kvantum included across all images for consistent aesthetics
- Stock KDE Plasma 6 desktop on Kinoite-based images, providing a customizable foundation
- Seamless containerization using Podman and Distrobox ,with the GUI app Box Buddy,to run Linux distros within other distros

## Installation
## Installation

Get started with my custom builds:

1. **Choose Your Edition**: Select the edition that best suits your hardware and preferences:
   - **Seabreeze OS**: Main image based on Kinoite for AMD and Intel users.
   - **Seabreeze Nvidia**: Variant for users with NVIDIA graphics cards.
   - **Seabreeze Gamer**: Edition optimized for gaming enthusiasts.
   - **Seabreeze Gamer Deck**: Specifically tailored for gaming on handheld devices.
   - **Seabreeze Gamer Nvidia**: Gaming edition for users with NVIDIA GPUs.


2. **Rebase Using rpm-ostree**:

To install this on your system, you will already need to have a fedora immutable distro on it already. I doesn't matter which one it is!

You can also rebase to any of these images whenever you like, all your data will be saved. It is reccomended to put the stock KDE plasma "Breeze" or "Breeze Dark" theme on as custom themes may be deleted/corrupted during the upgrade

Here are the editions you can use - just open your terminal and run these commands - 

   - For Seabreeze OS (Kinoite-based):
     ```bash
     rpm-ostree rebase ostree-unverified-registry:ghcr.io/tj5miniop/seabreeze-os:latest
     systemctl reboot
     ```

   - For Seabreeze OS for NVIDIA users:
     ```bash
     rpm-ostree rebase ostree-unverified-registry:ghcr.io/tj5miniop/seabreeze-nvidia:latest
     systemctl reboot
     ```

   - For Seabreeze OS (Based on Bazzite):
     ```bash
     rpm-ostree rebase ostree-unverified-registry:ghcr.io/tj5miniop/seabreeze-gamer:latest
     systemctl reboot
     ```

   - For Seabreeze OS (Based on Bazzite) for Steam Deck:
     ```bash
     rpm-ostree rebase ostree-unverified-registry:ghcr.io/tj5miniop/seabreeze-gamer-deck:latest
     systemctl reboot
     ```

   - For Seabreeze OS (Based on Bazzite) for NVIDIA users:
     ```bash
     rpm-ostree rebase ostree-unverified-registry:ghcr.io/tj5miniop/seabreeze-gamer-nvidia:latest
     systemctl reboot
     ```


## Get Involved

Contributions, feedback, and suggestions are welcome! Feel free to [open an issue](https://github.com/tj5miniop/seabreeze-ublue-images/issues) or submit a pull request to improve these builds.

## Verification

All images are digitally signed to ensure authenticity and integrity. For verification instructions, refer to the documentation provided by Universal Blue 
