# 🐭👾🖲️ Virtual Multi-Mouse 1.0.6 🖲️👾🐭
The best zero-config solution for combining your usb spinner, trackball, mouse and lightguns into one virtual mouse! Written from the ground up, MM is aim is to remove the barriers to entry when it comes to physical mouse device management. Plus it's so easy to install, anyone can do it!

## 🐭👾🖲️ What does Multi-Mouse run on?
Multi-Mouse supports with Batocera v35 or later. There are plans to make it work with RecalBox and other gaming Linux distros that can run EmulationStation and Retroarch. Multi-Mouse is completely open.

## 🐭👾🖲️ Get Ready Player One!
Ready to dive in for some golden age Arcade gaming? Multi-Mouse is the magic mouse solution for combining multiple mouse inputs into a single virtual device. Supports any combination of spinners trackball, mouse or trackpads. We made Multi-Mouse so you can just play. Requires no editing. MM is designed to configure itself as one device.

Get ready player one. No hard encoded, hard to type event-mouse names. MM will hunt them down for you making the setup ultra easy. There's no editing after you swap out new mouse, trackball or spinner. No need to configure the mouse input for a single 1 player game.
 
Like Batocera it's plug and play. Need to change your hardware configuration? Simply reboot or restart your game. Multi-Mouse aims to be hotswappable as well. We made some progress with this release, but there's still more work to be done. We plan to make it work like any other usb device. Log scrapping may eventually be removed or used only as a checksum in the near future. 

## 🐭👾🖲️ Ready to Enter the Multi-Verse?

1.  Insert a thumb drive to a Mac or PC
2.  Format it using ExFat, name the disk `install`
3.  Copy the `MM folder` to the thumb drive
4.  Insert the thumb drive to your Batocera Linux box
5.  Type `F1` to enter File Manager
6.  Navigate to /Applications and open Xterm
7.  `cd /media/install/MM`
8.  `chmod 755 ./install.sh` #may not be needed
9.  `./install.sh -install`
10.  `reboot`
11.  Enjoy!

## 🐭👾🖲️ Want to Leave the Multi-Verse?

1.  Insert the thumb drive to your Batocera Linux box
2.  Type `F1` to enter File Manager
3.  Navigate to /Applications and open Xterm
4.  `cd /media/install/MM`
5.  `./install.sh -uninstall`
6.  `reboot`
7.  No hard feelings, we understand Multi-Mouse is not for everyone!

## 🐭👾🖲️ Credits

* Virtual Multi-Mouse develped by StarPlayrX aka Todd Bruss
* MizterB for his initial post on Evseive, Batocera, Retroarch settings
* Special thanks to the Batocera team for giving me a renewed interest in RetroArch and Linux
* Shout out to RetroArch, EmulationStation, Recalbox and Multiple Machine Arcade Emulator teams

## 🐭👾🖲️ Reference Material
* https://github.com/KarsMulder/evsieve
* https://wiki.batocera.org/launch_a_script
* https://forums.libretro.com/t/configuring-ra-for-multi-mouse-spinners-lightguns-tackballs/12619E
* https://forum.batocera.org/d/6652-being-able-to-use-trackball-and-spinner-using-per-mouse-index/8
* https://forum.batocera.org/d/6652-being-able-to-use-trackball-and-spinner-using-per-mouse-index/10
