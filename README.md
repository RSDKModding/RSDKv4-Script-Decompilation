# RSDKv4 Script Decompilation

A full decompilation for the scripts in Sonic 1 & 2's 2013 mobile remakes.

These scripts have been manually reverted back to what the original scripts could've looked like. This means that:
* Function IDs have been recoverted back to proper function names
* Functions are in the proper order
* Default aliases have been re-added where possible
* Re-added static variables and tables
* Added editor renders and variables for (almost) every object
* Origins code has been included via the use of `#platform:` markers

Some portions of the code have been slightly modified for compatibility purposes.

To use these scripts in mods:
* RSDKv4/RSDKv5U Decompilation: Extract the `Scripts` folder to the exe's root directory: eg `[rootdir]/Scripts/`.
* Sonic Origins (Requires [Hedge Mod Manager](https://github.com/thesupersonic16/HedgeModManager)):
  * Navigate to the game's executable directory. The easy way to get to it is by clicking `Open Game Directory` in the Settings tab of Hedge Mod Manager.
  * Once you're there, extract the `Scripts` folder into a folder named `Sonic1u` or `Sonic2u` in the exe's root directory: eg `[rootdir]/Sonic1u/Scripts/`.

Make sure you use the appropriate Scripts folder for the game you're trying to run.
Mods are only required to include the scripts that have been changed.

For anyone curious about how RSDKv4's scripting language works, check out the handbook (RetroScript Handbook v4.pdf) we made to help get people into using RetroScript v4. We recommend downloading the handbook as it makes it easier to navigate.
