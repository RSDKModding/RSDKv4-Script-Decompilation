# Sonic 1/2 2013 Script Decompilation (WIP Cleanup Branch)

## **Please don't use this branch for your mods, as we're still bug testing!**

A full decompilation for the scripts in Sonic 1 & 2's 2013 mobile remakes.

These scripts have been manually reverted back to what the original scripts could've looked like. This means that:
* Function IDs have been recoverted back to proper function names
* Functions are in the proper order
* Default aliases have been re-added where possible
* Re-added static variables, tables, and values
* Origins code has been added into scripts via the use of `#platform:` markers

To use these scripts in mods:
* RSDKv4/RSDKv5U Decompilation: Extract the scripts folder to the exe's root directory: eg `[rootdir]/Scripts/`.

Mods are only required to include the scripts that have been changed.

For anyone curious about how Sonic 1/2's scripting language works, check out the handbook (RetroScript Handbook v4.pdf) we made to help get people into using RetroScript v4. We recommend downloading the handbook as it makes it easier to navigate.
