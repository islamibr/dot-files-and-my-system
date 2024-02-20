I use dual boot system on 2 hard disks, on include the two system (250G SSD) and other include data (1T HDD), the reasons to do that are
- Learn Unix/Linux as Key Skill
    -- (almost every professional hardware program works only on RedHat)
- Build Automation for Some Process
- Customize my system as I need

So, I use Windows 11 and Arch Linux (after bad trys for ubuntu, debian, centos, kali) /* you can use void still a nice choice.
- Using the windows as secondry system to do some tasks on all softwares that doesn't supported on linux such (office, altuim, matlab, proteus, allegro, questa, labview, simulink, vivado, comsol, quartus, lumerical, tcad, cst, etc...) /*fun fact it takes more tha 2/3 of the hard.
- Using the arch as the main system to do coding and every other thing.

Before dive deep in the arch i want to note that i use more cloud sync apps to acess it from both systems to avoid wasting times switching systems every time i want to take note, searching, listening to lecture or do something else, so let's go for arch

I will not talk much about arch here; you can search for it and more on linux systems but what i will talk is on higher level after understanding the basics /* installing arch is one of most educational things to understand linux and one of most enjoyable thing */ 

The philosphy which i choose the system compenet is the next:
- Achieve the highest productivity by limiting the wasted time as distruction so 
-- Using rolling release
-- Package Avalibilty
-- Minimization
  
- I really get a lot problem in grub and kernel in the other distros so i deciade
-- Base Image
-- Advanced Debugging
-- SystemD 'Secuirty'

- Also, I choosed the programs categories i need before the distro
-- Text
-- Keyboard
-- GUI
-- Vim
-- Applications

So, here is the programs in hierachy of system:
- Display Manager (to start the gui from tty):
-- xorg /* xdm */

- Window Manager (to give me the needed frame of gui:
-- dwm /* top layer */
-- patches: stacking, gaps, systray, center, push, noborders, extrabar
-- compositor: picom /* animations */

- Terminal (to control everthing i need:
-- st /* top terminal */
-- patches: newterm, gruvbox, scrollback
-- tmux /* better experience */
-- alacritty /* GPU for terminal */
-- Shell: fzy /* research and find */, zsh /* instead of bash because of its better experince */
 
- Menu (to facialte getting apps and building interface for other things:
-- dmenu /* top menu */
-- patches: center, gruvbox, numbers, xyw, border, alpha

- Panel & Widget(to get more facilation and feel the device & system compenat) :
-- dunst /* notifcations */
-- sxhkd /* shortcuts */
-- bspwm /* advanced shortcuts */
-- slstatus /* status bar */
-- htop /* mointoring dashboard */

- File & Disk Manager (to control space and acess protal disks and the stoarge disk in the dual system):
-- nautilus /* gnome */
-- mount

- Text Editor (it's the everthing i build the system for!):
-- neovim /* nvim is better than normal vim */
-- plugins: ultisnips

small note here: you can install nvchad if you want full IDE but in my case i want to learn more so i use vim as it for educational purpose

actually everything ends here but i need things that arch doesn't provide xD

- Audio Manager:
-- pavucontrol /* gui */
-- pulseaudio /* non-gui */
-- asla /* driver */

- Package Manager:
-- pacman /* main come with the system */
-- yay /* some apps i need like brave becuase i hate ads */
-- snap /* gnome apps i need i will disscus in the end of document */

- System Admin:
-- doas /* instead of sudo becuase i hate passwords */
-- setxkbmap /* keyboard layout becuase i chat in arabic */

and unfortnully, i am using labtop so i need more things to activate nearlly everthing in my device
- Touchpad Manager:
-- synaptics

- Power Manager:
-- acpid

- Bluetooth Manager:
-- bluez-utils

- Internet Manager:
-- network-manager

that's not everthing, there are some other general tools i need such (git, wget, meson, libararies & depancencies as needed, etc...)

now we finished the first phase of the system building linux and windows! but i need to build more to make the system beneficial otherwise that is learning linux only not using it!

my productivity system is build using the following apps:
- Brave as main broswer (ad blocking agian, i saved 1M seconds because of that)
- Notion and it utalites (Notion calander and Notion clipper) as top layer (everything sync to this at the end to make my focus at one place)
- G-Keep, G-Calander (becuase notion is only online app, i need offline in sometimes so i use this apps and those sync to notion when i be online)
- Thunderbird (Using one email box for all emails and it include teams as my university work on it, sometimes in freetime i look /notify for other boxes but my main is this )
- What'sapp, Telegram and Linkedin (in free time, i spend sometimes to see what new and notify my friends)
- all previous are nice but let's go for the core (my note taking system), I build the notes using LaTeX and for that I build IDE using:
  -- Zathura (to see the results of compiles)
  -- Inkscape (to go for figure build as engineer you do alot of figures)
  -- SageMath (instead of matlab as i need some math funcations)
  -- Zotero (to collect and manage the things i study from in one place and it sync with notion and for ciations in my paper i export in BibTeX)
  -- Github (to control the version and read it letter in my phone futher more sync to notion)
  -- Mathpix (ocr to make faster notes with the snipets i have too in the nvim)

and that is everything!
