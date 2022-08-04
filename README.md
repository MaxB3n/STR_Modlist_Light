# STR_Modlist
Max's Skyrim Together repo with wabbajack list and other files.

Go through the README below for detailed installation instructions. Installation will take about a half hour of clicking through things and a few hours of letting big things download. It looks like a lot, but each step should be quick and easy :p if anything gives you trouble, ask me for help!

Steps Below:
1. Setting up Skyrim
2. Setting up modding tools
3. Downloading this mod list and its accessory files
4. Installing with wabbajack
5. Final set up
6. Troubleshooting tips / resources


# 1 Getting Skyrim set up
Download and install Skyrim Special Edition (SSE). If you have it installed already, delete the SSE folder in your steam library, the SSE folder in documents > mygames >, and the SSE folder in %appdata% > local (3 folders total), then uninstall through steam, then reinstall the game.

It's important that you move SSE into a steam library that's NOT in any of the program files, documents, desktop, users, or other "smart" file locations. If you already have a library directly on a drive, move SSE there and continue. If you have a second drive (ex D: or E:), you can make a second library through steam: from the top right corner of the steam app go to steam > settings > downloads > steam library folders and then add a new library with the + button at the top (make sure you create the new library directly on your drive or in a new folder directly on your drive). If you do not have a second drive, google how to create a new steam library on your boot drive, it's a bit messier. There are a few ways to do it, I used this tool https://github.com/LostDragonist/steam-library-setup-tool/releases but it doesn't seem to work for everyone. Message me if you're having trouble with this step.

Once you have Skyrim in the correct library, click [play] in steam to initialize it. The launcher should open and prompt you for graphics settings. Once the prompts are finished, you can close the launcher.


# 2 Getting modding tools set up
Make a modding folder, also directly on your drive, to keep all of your modding tools and downloads organized in (I have subfolders for STR mod installation/, Single player mod installation/, Backups/, and Modding tools/--it really helps to keep things organized.

Download the Wabbajack release and move the application into your modding tools folder https://github.com/wabbajack-tools/wabbajack


# 3 Downloading the modlist and its accessory files
github doesnt actually have the storage so you'll need to download the whole thing from google drive. Here's the link: https://drive.google.com/drive/folders/1MNf9tP3xCnqkUuz2q6KhPdRqz_7fi-ra?usp=sharing

Download the STR Light Modlist folder from Google Drive. If you can change google drive settings to download big files without zipping (by syncing drive to a local folder on your computer and syncing the STR Light Modlist folder through drive) that's ideal, but you can also download normally and let google drive zip it.

IF YOU DOWNLOAD NORMALLY:  
-Extract the STR Light Modlist folder somewhere.  
-In Google Drive, navigate to STR Light Modlist > STR Installation Folder Files > downloads and download the zipped files in there individually (re-zipping them renders them unusable).  
-Without extracting them, drag and drop those individually downloaded zip files into your local, extracted copy of STR Light Modlist > STR Installation Folder Files > downloads and replace the files there.


# 4 Installing with Wabbajack
Open the Wabbajack application in your modding folder and click "install from disk".  
For Target Modlist, use the [...] button to open file explorer and navigate to the extracted STR Light Modlist folder > STR 2.1.1 and select the STR 4.1.5 wabbajack file inside.  
For Installation Location make a mod installation folder inside of your modding folder if you haven't already and select it using the [...] button again.  
Download Location should be filled automatically.

When prompted to sign in to nexus mods, sign in with my login creds    ~    email: orcishinterpreter@gmail.com    pass: d_C5x#LMi.N$+zY

The download and installation process should take a few hours depending on your internet connection. You can use your computer for other things during the download and installation but the less network/disk heavy things the better. Run overnight if you have to.

If the download/installation process is interrupted or an error comes up, don't worry, wabbajack can pick up where it left off as long as the installation and download folders are the same.  

The installation will probably error once, the first time it does, copy the contents of the STR Light Modlist > STR Installation Folder Files into your install location and run wabbajack again with the same settings. If it errors a second time, let me know and I'll help you troubleshoot it.

Once everything is installed, close wabbajack and go to the installation location. Open the Mod Organizer 2 application (it has a blue icon), this will be your hub for launching the
game, launching tools, and changing mods. You might as well make a shortcut and put it on your desktop or in your start menu.  
NOTE: this instance of mod organizer 2 is separate from any other installation and vice versa--you have to open the application in your installation folder to launch things and use your mods.


# 5 Final set up
Time to add all of the accessory files.

Copy the contents of STR Light Modlist > STR Installation Folder Files into your installation folder again to make sure wabbajack didnt overwrite anything while it finished up.

Copy the contents of STR Installation > Game Folder Files and paste it in the SSE application folder in your new steam library (address should look something like
library folder > steamapps > common > SSE), you should be prompted to replace some files, do. While you're in the game folder, open the data folder and delete the creation club content files, there should be 8.

Copy the contents of STR Light Modlist > Documents Folder Files and paste inside of the SSE documents folder (Documents > My Games > SSE), replace when prompted.


Back in the Main Mod Organizer 2 interface, click on the downloads tab on the right-hand side of the application and you should see the names of the 4 compressed files you downloaded in the Non-Nexus Downloads folder: texGen Output_2.1.1, DYNDOLOD Output_2.1.1, Hel rising, and Maelstrom. The status column next to each should say "Downloaded" in green. Double click each of them and hit ok in the popup to install each mod. They should appear on the left-hand side of the window with unchecked boxes, check each box.

In the plugins tab on the right, search "bash" to make sure bashed patch 2 is enabled and no other bashed patches. Search plugins for "SSEMerged" and make sure sse merged 2.1.1 is enabled and no other SSEMerged patches.

Everything is installed as it should be now! You're almost done, we just have to sort plugins and set up skyrim preferences. From the drop down next to [RUN], select LOOT and then run it. Once LOOT initializes, click sort plugins in the top left corner, and then hit apply load order, then close LOOT.

From the drop down, select BethINI and [RUN]. Close MO2 when prompted and hit OK. Select recommended tweaks and appropriate quality settings in the BethINI window, then save and exit.

Everything should be good to go! Select Skyrim together in the drop down menu and run it!

It Just Works.
