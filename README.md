Installation from scratch:

On top of the download you will also need:
⦁ Any Doom or Freedoom iwad (N.B. Freedoom is an open source project and is free to download from: Freedoom.github.io)

 
//Zandronum
⦁ Download Zandronum. The latest stable and dev version can be found here: Zandronum.com

⦁ In the main Zandronum directory place the Doom or Freedoom iwad.

⦁ In the Zandronum main directory create a new folder called "skins" and place any mod files here that you want to load (mod, maps, music, etc).

⦁ Run Zandronum.exe to play


//GZDoom
⦁ Download GZDoom: Zdoom.org

⦁ In the main GZDoom directory place all files here (Doom or Freedoom iwads and mod files).

⦁ There are multiple ways to load the mod. Here are a few methods:

Drag all mod files onto the GZDoom.exe to run (quickest but wihout mod load ordering)

Use a mod launcher such as ZDL (ZDoom Loader), DML (Doom Mod Loader) or Doom luancher to load mods.

Start GZDoom.exe and exit the game to generate a config file gzdoom-<username>.ini. Edit the config file and add the mod file names under the [doom.autoload] heading and save the config.

example:

[doom.autoload]
path=bd64game_v2.666.pk3
path=bd64maps_v2.666.pk3
path=any other mod file

⦁ Run GZDoom.exe to play


//Delta Touch (Android Only)

Delta Touch Google Play link: Play.google.com

After installing the app the necessary folders are automatically created on your device.

The simplest way to transfer file is to use a cable to transfer from computer to device. You can also just use the device to download and place the files.

Place Doom or Freedoom iwads into folder OpenTouch/Delta

Place all mods into the folder OpenTouch/Delta/mods

Start Delta Touch and select your desired sourceport. Press on the large arrow on the left to bring up the sourceport list. Select either Zandronum or if using GZDoom remember to use v3.8.2 or above.

When selecting mods, the load order is determined by the sequence you select mods from the list. N.B. To clear the active mods press the X icon, this is handy of you have an incorrect loading order.

Press the play button to begin. 
