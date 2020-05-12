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

# (Tools)[tools.md]
I've created a separate file for the tools I use to get the most out of my space
