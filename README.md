# Building a Productive Dual Boot System: A Journey into Arch Linux and Windows 11

## Introduction

In the realm of operating systems, I've embarked on a quest to create an optimal dual-boot setup utilizing Windows 11 and Arch Linux. My motivation stems from a desire to acquire essential Unix/Linux skills, automate various processes, and tailor my system to maximize productivity.

## System Architecture

I've partitioned my hard disks strategically, with one SSD hosting both operating systems (Windows 11 and Arch Linux) and another HDD reserved for data. This configuration allows me to harness the power of Windows for specific software applications while utilizing Arch Linux for coding and other tasks.

## Operating System Selection

After exploring various distributions, I settled on Windows 11 for compatibility with hardware-intensive applications and Arch Linux for its educational value, customization options, and efficiency.

## Cloud Synchronization

To streamline my workflow and eliminate the need to switch between systems constantly, I employ cloud sync applications for note-taking, searching, and other tasks.

## Arch Linux Configuration Philosophy

My approach to configuring Arch Linux revolves around achieving peak productivity by minimizing wasted time and distractions. Key elements of this philosophy include:

- **Rolling Release**: Ensures my system is always up-to-date.
- **Package Availability**: Easy access to a vast repository of packages.
- **Minimization**: Striving for efficiency and simplicity.

## System Components

### Base Components

- **Base Image**
- **Advanced Debugging**
- **SystemD Security**

### Program Categories

1. **Text**
2. **Keyboard**
3. **GUI**
4. **Vim**
5. **Applications**

### Programs Hierarchy

#### Display Manager
- **xorg (xdm)**

#### Window Manager
- **dwm (with patches)**
- **picom (compositor for animations)**

#### Terminal
- **st (with patches)**
- **tmux**
- **alacritty**
- **zsh (Shell)**

#### Menu
- **dmenu (with patches)**

#### Panel & Widget
- **dunst (notifications)**
- **sxhkd (shortcuts)**
- **bspwm (advanced shortcuts)**
- **slstatus (status bar)**
- **htop (monitoring dashboard)**

#### File & Disk Manager
- **nautilus (gnome)**
- **mount**

#### Text Editor
- **neovim (with ultisnips plugin)**

### Additional Utilities

- **Audio Manager**: pavucontrol, pulseaudio, alsa
- **Package Manager**: pacman, yay, snap
- **System Admin**: doas, setxkbmap
- **Laptop-Specific Tools**: synaptics (Touchpad), acpid (Power Manager), bluez-utils (Bluetooth Manager), network-manager (Internet Manager)

### General Tools
- **git, wget, meson, libraries & dependencies**

## Productivity Stack

1. **Brave** as the main browser (ad-blocking for improved efficiency).
2. **Notion** and its utilities (calendar and clipper) as a centralized productivity hub.
3. **G-Keep, G-Calendar** for offline note-taking and syncing with Notion.
4. **Thunderbird** for managing emails.
5. **Messaging Platforms**: WhatsApp, Telegram, LinkedIn for staying connected.
6. **Note-Taking System** built using LaTeX with tools like Zathura, Inkscape, SageMath, Zotero, Github, and Mathpix for OCR.

In conclusion, my dual-boot system is not just about learning Linux; it's about using it efficiently. Through thoughtful customization, strategic application selection, and integration of cloud services, I've crafted a powerful environment that aligns with my workflow and maximizes productivity.
