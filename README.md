# arch-scripts

A collection of my scripts that I use when installing Arch Linux.
### default-install.sh - To be run after system is setup
(Run this file as root)

tl,dr: Installs lxqt (still needs configuring), audio, office suite, and other small packages.

Installs:
- Xorg (Window Manager)
- lxqt (Minimal desktop manager)
- Breeze Icons (Icons for lxqt)
- gnome (For application support)
- Evolution (Email, Calendar & Tasks)
- pipewire (Audio)
- Libreoffice (MS Office Substitute)
- nano (Terminal text editor)
- htop (System utilization tool [terminal])
- xsecurelock (Lock Screen)

  Add line
  ```
  lock_command=xsecurelock
  ```
  to ~/.config/lxqt/lxqt.conf under [General]

### packstrap-install.sh (TODO) - Specific file setup to load and initialize firmware for my Samsung XE310XBA

Includes base packages, linux, video firmware, cpu fixes and audio firmware for system.

Installs:
- Linux
- Base
- Linux Firmware
- Intel Ucode
- Intel Video Drivers
- NetworkManager (For Network connections)
