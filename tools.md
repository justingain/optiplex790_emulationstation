# Tools

For this section, I'll go over how I got the most out of the limited space I have. I use three tools - I'll explain what they are and how I use them:

* CDmage
* CISO
* PSX2PSP

### CDmage
CDmage is software that is used for working with CD Images. The way I used it is to take Playstation games that have multiple bin files related to a single cue file and condense them to a single bin file. This allows you to use PSX2PSP later to convert it to pbp. Why pbp and not iso? I've found that when I compress it to pbp - not only can PCSX Rearmed read pbp files natively without issue - but it also compresses files down to about 30% of their normal size.

To start you want to make sure you are running the right version. The version I used is 1.02.1 Beta 5. The one from the official site didn't allow me to save my condensed file to another .bin file. I found the proper version of CDmage [here.](https://www.emuparadise.me/links-and-downloads/General_CD_Utils/CDmage_1.02.1_Beta_5/20)
The steps are as follows:
1. Open CDmage
2. Drag your .cue file into the section labelled Joliet Image Tree
3. Give it a few moments to load all the associate .bin files into the program
4. Once it's done, click file -> save as and save it to a different folder so it doesn't override anything important (I recommend creating a temp or converted folder to hold all of your new bin/cue file that's created
5. That's it - you're ready to push it to PSX2PSP

### PSX2PSP
PSX2PSP was originally created to turn PS1 ISO/BIN files to something the PSP could read with all the proper metadata. Instead of that however, we are going to use this tool to convert PS1 bin files that we created with CDmage or downloaded from the internet to .pbp which is compressed a lot more and can save a good amount of room on your hdd. 
#### Converting Single Disc Files
1. Open PSX2PSP
2. If it asks which theme - use classic. It has better compatibility with multi disc files which I'll explain how to do next.
3. At the top you'll see where it says "ISO/PBP File", be sure to click the button with the "..." and choose the .bin file you want to convert.
4. Next, choose an output folder. I just pushed my conversions to my main PS1 rom folder.
5. Game Title and Main Game Title should be prefilled. If for some reason it's not (which happened to me with Threads of Fate) then be sure to copy it so that Game Title and Main Game Title show the same. So I had to write Threads of Fate in both boxes. Also make sure that Game ID and Main Game ID match. One usually gets pre-filled when you open the .bin file but if they are both blank for whatever reason you can go (here)[https://psxdatacenter.com/ntsc-u_list.html] to find the correct Game ID for the game you're converting.
6. If you want to make it a bit easier on yourself, be sure to go to Options and change the folder settings to "Create Main Game Title Folder" before you convert anything.
7. Finally press the Convert button and wait for the process to complete.
8. Go to the folder where you pointed the pbp output to. From here you should see a folder with the game title, go into the folder and you'll see a file called EBOOT.PBP. Change EBOOT to whatever the name of the game is and then put it in your MAIN PS1 Rom folder. You can then delete the folder with the name of the game as it should be empty now. If you load EmulationStation (see emulationstation.md for setup instructions), these should be picked up by ES and you can scrape for the info. You'll also notice that they run perfectly in the core I listed in the readme.

#### Converting Multi Disc Files
1. The overall setup is the same for multi disc files except there's one major difference: When you choose the file in step 3, you'll have to click the drop down and choose "ISO/PBP File 2" and place the disc 2 bin here. The only downside is once you're done converting - if you have any other single disc games you'll have to close the application and reload as I couldn't find a way to unload the second file.
2. Also keep in mind when you load the bin file the file name will say [Disc 1 of 2] and [Disc 2 of 2] - you can delete these to keep the name consistent, but don't change any other settings. The Game ID/Main Game ID matching above doesn't apply to Multi Disc Games.
3. After those changes, you can follow all the rest of the steps above to get a single pbp file.

### CISO
This application is used to convert PSP isos to csos which are compressed forms of isos. Honestly, you may see a 10% compression - so it's up to you if you want to go this route. The steps are simple:
1. Open CISO
2. Drag the ISO into the app insuring that ISO > CSO is selected
3. Wait until completed
4. Delete the original ISO

That's it.
