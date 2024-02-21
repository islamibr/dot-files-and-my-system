# Dot Files and My System

## Introduction

Welcome to the repository housing my dot files and the intricate architecture of my dual-boot system, featuring Windows 11 and Arch Linux. In this README, I'll provide you with an in-depth look at the choices, philosophies, and tools that power my productivity.

## Dual Boot Setup

My system is strategically set up on two hard disks: one for the operating systems (a snappy 250G SSD) and another for data storage (a capacious 1T HDD). The reasons behind this setup are multi-fold:

1. **Learn Unix/Linux as a Key Skill:**
   - A crucial skill, especially for professional hardware, which predominantly utilizes RedHat.

2. **Build Automation for Streamlined Processes:**
   - Automation reduces time wastage, enhancing overall efficiency.

3. **Customization for a Tailored Experience:**
   - Crafting my system according to my unique needs and preferences.

## Operating Systems of Choice

After experimenting with various distributions (including Ubuntu, Debian, CentOS, Kali), I settled on:

- **Windows 11:**
  - Secondary system for tasks requiring software not supported on Linux (e.g., Office, Altium, MATLAB).

- **Arch Linux:**
  - Main system for coding and daily activities.

## Cloud Sync for Seamless Integration

To minimize the hassle of switching systems, I employ cloud sync apps e.g., search, lectures, quick notes.

## Architectural Philosophy

### Productivity Optimization

My system architecture adheres to these key principles:

1. **Achieving Highest Productivity:**
   - Utilizing a rolling release for continuous updates.
   - Ensuring package availability.
   - Embracing minimization for enhanced efficiency.

2. **Grub and Kernel Solutions:**
   - Base image, advanced debugging, and SystemD security for system stability.

3. **Program Categorization:**
   - Organizing programs into text, keyboard, GUI, Vim, and applications.

## Components of the System

### Display and Window Management

- **Display Manager:**
  - Xorg with xdm for GUI initiation.

- **Window Manager:**
  - dwm with various patches for a customizable experience.
  - Compositor: picom for smooth animations.
  - nitrogen for background setting.

- **Terminal:**
  - st terminal with patches for enhanced functionality.
  - tmux for a better terminal experience.
  - alacritty for GPU-accelerated terminal.
  - Shell: fzy and zsh for improved usability.

### Menu, Panel, and Widgets

- **Menu:**
  - dmenu for a user-friendly application launcher.

- **Panel & Widget:**
  - dunst for notifications.
  - sxhkd and bspwm for advanced shortcuts.
  - htop for monitoring.

### File and Disk Management

- **File & Disk Manager:**
  - nautilus for file management with GUI.
  - mount for disk management.

### Text Editing

- **Text Editor:**
  - neovim with UltiSnips for efficient text editing.

## Beyond Arch Linux

For functionalities not provided by Arch, additional components include:

- **Audio Manager:**
  - pavucontrol, pulseaudio, and asla for audio management.

- **Package Management:**
  - yay for additional apps.
  - snap for specific GNOME apps.

- **System Administration:**
  - doas instead of sudo.
  - setxkbmap for keyboard layout adjustments.
    
- **Sharing Items:**
  - xclip clipboard for text and screenshots.
  - maim for taking screenshots.
  - OBS stuido for recording youtube videos.
    
## Laptop-Specific Additions

- **Touchpad Manager:**
  - synaptics for touchpad management.

- **Power Manager:**
  - acpid for power management.

- **Bluetooth Manager:**
  - bluez-utils for Bluetooth functionality.

- **Internet Manager:**
  - network-manager for internet management.

## General Tools

Including git, wget, meson, libraries, and dependencies as needed.

## Productivity Apps

My productivity revolves around essential applications:

- **Browsing:**
  - Brave as the primary browser (saving 1M seconds).

- **Note-Taking and Organization:**
  - Notion as a top layer, syncing all data for seamless access.
  - G-Keep, G-Calendar for offline organization.
  - Thunderbird, WhatsApp, Telegram, LinkedIn for communication.

- **Note-Taking System:**
  - LaTeX for building comprehensive notes.
  - Zathura, Inkscape, SageMath for visualization.
  - Zotero and GitHub for management and syncretization.
  - Mathpix for OCR snippets to nvim.

## Conclusion

And there you have it – the intricate web of my dual-boot system. It's not just about learning Linux; it's about crafting an environment that maximizes productivity and seamlessly integrates into my workflow. From window managers to productivity apps, each component plays a vital role in creating a harmonious computing experience.

Feel free to explore the dot files and configurations to get insights into how this system is tailored to meet my unique needs. If you have any questions or suggestions, don't hesitate to reach out. Happy exploring!
