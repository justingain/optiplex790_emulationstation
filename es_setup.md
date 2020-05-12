# EmulationStation Intro
EmulationStation is an emulator frontend that's typically for Raspberry Pi devices. However, there is a file called "RetroCake" that automates it so you can run EmulationStation on Windows. It automates the following:
* Downloads and creates EmulationStation
* Downloads Retroarch
* Downloads extra emulators such as Dolphin
* Sets it up so when you turn on your PC - it instantly launches EmulationStation without login once Windows 10 loads
* Allows you to easily access and edit your EmulationStation config file

This has made setting this machine up infinitely easier. The whole process is guided - so all you have to do is select the options you want and you're good to go. I'm going to put up a file on how I set up RetroCake for me in another file (retrocake.md) so you can get an idea - and I'm also posting my EmulationStation config file so you can see what I've done with the front end as well.

You may be asking yourself - what are some advantages of EmulationStation? Here's a few:
* Themes: You can install various themes - including ones that mimic the various mini systems that are prevalent these days
* Scraping: You can scrape artwork and info for every game that you have so you always have box art
* Configurable: Don't like to use Retroarch for a certain system - or can't? You can always change the cfg file to point at another application.
* Controller Navigation: This is a big one - I wanted to have an all in one system that I could navigate with my controller without using Mouse and Keyboard at all. This opens the gateway for that to happen.

The main things I've set up are my controller bindings - or how I want my controller to work within EmulationStation itself. Just remember whatever you set within EmulationStation is ONLY for navigation. It doesn't affect any of the games themselves.

The theme I currently use is: [Art-Book](https://github.com/anthonycaccese/es-theme-art-book) 

which can thankfully be downloaded through the RetroCake script. The reason I use this is because it has the most compatibility with various consoles as NES/Famicom/SNES Mini doesn't support GameCube (it'll show - it just won't be themed)
