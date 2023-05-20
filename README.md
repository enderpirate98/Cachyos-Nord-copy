# How to Install the Nord Theme Manually on Your Linux Distro!

If you're using CachyOS, you may be happy with its current functionality but looking for a more stable distribution that doesn't use a bleeding-edge approach. Perhaps you're considering switching to a distribution like OpenSUSE Tumbleweed, but you want to make sure you can still use your favorite Nord theme, which is not available in the KDE theme store.

Not to worry! In this guide, we'll show you how to install the Nord theme manually on your KDE-based Linux distribution, so you can enjoy its beautiful aesthetic without any issues. With these simple steps, you'll be able to customize your desktop with the Nord theme, no matter which distro you choose.

# Installation

This guide provides instructions on how to install the CachyOS Nord KDE theme manually.

## Prerequisites

Before proceeding with the installation, ensure that you have the following prerequisites:

- KDE Plasma desktop environment
- Git (to clone the repository)

## Installation Steps

Follow these steps to install the CachyOS Nord KDE theme:

```shell
# Clone the repository
git clone https://github.com/CachyOS/CachyOS-Nord-KDE.git

# Change into the cloned directory
cd CachyOS-Nord-KDE

# Review the PKGBUILD file located at https://github.com/CachyOS/CachyOS-PKGBUILDS/blob/master/cachyos-nord-kde/PKGBUILD#L24-L46
# Note: Pay attention to the uncommented lines in the PKGBUILD file

# Copy the necessary paths from the uncommented lines in the PKGBUILD file

# Open the terminal and navigate to your local theme installation directory. By default, this is ~/.local/share/plasma/desktoptheme/

# Create the necessary folders
mkdir -p ~/.local/share/color-schemes
mkdir -p ~/.local/share/plasma/desktoptheme
mkdir -p ~/.local/share/plasma/look-and-feel

# Paste the copied paths into the terminal to copy the theme files to the appropriate installation directories
# Note: You may need administrative privileges (sudo) to copy files to system directories

# Once the files are copied, open the KDE Plasma System Settings

# In the "Look and Feel" section, select "Desktop Theme"

# Choose the "CachyOS Nord" theme from the available options

# Apply the changes, and the CachyOS Nord KDE theme will be applied to your KDE Plasma desktop environment
