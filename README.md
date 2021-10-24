# OpenCore-ASUS-MAXIMUS-VI-HERO

This repository contains:

- OpenCore configuration for ASUS ROG MAXIMUS VI HERO
- EFI folder archive

## Table of Contents

- [Hardware list](#hardware-list)
- [macOS](#macos)
- [OpenCore](#opencore)
  - [Known Issues](#known-issues)
  - [ACPI](#acpi)
  - [USB](#usb)
  - [Drivers](#drivers)
  - [Kext](#kext)
  - [Resources](#resources)
  - [Tools](#tools)
- [BIOS Settings](#bios-settings)
- [Installation](#installation)
  - [Download EFI folder archive from repository releases page](#download-efi-folder-archive-from-repository-releases-page)
  - [Create EFI directory and files helper script](#create-efi-directory-and-files-with-helper-script)

## Hardware list

| Type | Item |
| ---- | ---- |
| Motherboard | [Asus ROG MAXIMUS XI HERO ATX LGA1151 Motherboard](https://pcpartpicker.com/product/PGTPxr/asus-rog-maximus-xi-hero-atx-lga1151-motherboard-rog-maximus-xi-hero) |
| CPU | [Intel - Core i9-9900K 3.6 GHz 8-Core Processor](https://pcpartpicker.com/product/jHZFf7/intel-core-i9-9900k-36ghz-8-core-processor-bx80684i99900k) |
| CPU Cooler | [Corsair H60 (2018) 57.2 CFM Liquid CPU Cooler](https://pcpartpicker.com/product/F2rmP6/corsair-h60-2018-572-cfm-liquid-cpu-cooler-cw-9060036-ww) |
| Thermal paste | [ARCTIC MX-4 2019 Edition 4 g Thermal Paste](https://pcpartpicker.com/product/JmYLrH/arctic-mx-4-2019-edition-4-g-thermal-paste-actcp00002b) |
| Memory | [Ballistix Sport LT 64G DDR4, 2400 MHz CL16, BLS4C16G4D240FSB](https://www.amazon.com/gp/product/B01B4F3MNQ) |
| Video Card | [Sapphire Radeon RX 580 8 GB PULSE Video Card](https://pcpartpicker.com/product/y2DzK8/sapphire-radeon-rx-580-8gb-pulse-video-card-11265-05) |
| Wi-Fi + Bluetooth Adapter PCI-E x1 Card | [Fenvi HB1200 WiFi + Bluetooth 4.0 BCM4360](https://www.amazon.com/gp/product/B07T9JD93Y/) |
| HDD 1,2 | [Samsung 860 Evo 500 GB 2.5" Solid State Drive](https://pcpartpicker.com/product/6yKcCJ/samsung-860-evo-500gb-25-solid-state-drive-mz-76e500bam) |
| HDD 3 | [Seagate Barracuda 6 TB 3.5" 5400RPM Internal Hard Drive](https://pcpartpicker.com/product/ByL48d/seagate-barracuda-6tb-35-5400rpm-internal-hard-drive-st6000dm003) |
| Camera | [Logitech C920S HD Pro Webcam](https://www.amazon.com/gp/product/B07K95WFWM) |

Other accessories:

| Type | Item |
| ---- | ---- |
| Keyboard | [Magic Keyboard with Numeric Keypad](https://www.apple.com/shop/product/MRMH2LL/A/magic-keyboard-with-numeric-keypad-us-english-space-gray) |

## macOS

macOS Big Sur version 11.6 (20G165) with FileVault 2 enabled.

You may find great installation guide [here](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/).

## OpenCore

- [OpenCore 0.7.4](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.7.4)
- [Dortania OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
- [Desktop Coffee Lake](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html)
- [OpenCanopy](https://dortania.github.io/OpenCore-Post-Install/cosmetic/gui.html)
- [FileVault](https://dortania.github.io/OpenCore-Post-Install/universal/security/filevault.html)

### Known issues

**Open**: None.
- [x] OSX runs great, but the OS freezes sometimes on a randomly moment.

**Resolved**:
