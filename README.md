# optiplex790_emulationstation
How I set up emulation station on my optiplex 790 USFF

# Purpose
With the limited upgradability of the Optiplex 790 USFF (Ultra Slim Form Factor), I decided to set up a repository to keep track of all the thing I did to get Emulation Station (an emulator frontend) working up to GameCube. Note that it is within the realm of possibility to get one of these machines for around $50 on eBay, making it a pretty decent way to make a small emulation machine for a living room.

# Specs
First, the specs for the Optiplex 790 USFF are as follows:
* i3-2120 cpu @ 3.30ghz (from 2011)
* 4GB Ram
* 500GB SATA HDD
* Intel HD Graphics 2000

# Accessories
Here are some accessories I added to get more out of this:
* Xbox One Wireless Adapter (It supports 8 Xbox One Controllers according to online)
* DVI to HDMI adapter - this pc does not have HDMI natively - so I had to get an adapter

# Misc Notes
* At the moment, I don't think I'm going to need more space since I can only emulate so many consoles on this machine. However, if I do need more space - there is the possibility of replacing the CD/DVD Rom drive with another hard drive since they are sata (I believe)
* I'd really like to max out the RAM to 8GB to make sure it's running the best it can
* Overall I'd say performance is decent. With a few setting changes - I can get 60fps in Gamecube fairly easily.
* One key thing I noticed is OpenGL doesn't work so well on this machine. However, when I switched most to DX11 things worked a bit better. This is critical for RetroArch. Before I switched to DX11 - everything was slow going.

# Emulators
* OS: Windows 10
* Frontend: EmulationStation via Retrocake
* Emulator: Retroarch

| Console       | Core          |
| ------------- |:-------------:|
| NES           | Fceumm        |
| SNES          | SNES9x2010    |
| Game Boy      | Gambatte      |
| Game Boy Color| Gambatte      |
| Game Boy Advance| GPSP        |
| Nintendo DS   | DeSmuME       |
| Genesis       | Genesis Plus GX|
| SegaCD        | Genesis Plus GX|
| Playstation   | PCSX Rearmed  |

There are two consoles where I had to run standalone applications versus the retroarch core version for whatever reason. They are as follows:

| Console      | Application   |
| -------------|:-------------:|
| GameCube     | Dolphin       |
| PSP          | PPSSPP Gold   |

I have a few consoles that won't work for whatever reason. I've tried every core available to Retroarch AND standalone apps to no avail. They are as follows:
* N64
* FBA
* Dreamcast

# Tools
I've created a separate file for the tools I use to get the most out of my space.
View it [here](https://github.com/justingain/optiplex790_emulationstation/blob/master/tools.md)
