# Vanilla Quake II version 3.21 for MS Visual Studio 2019 

## Original 'readme.txt' reformatted:

This is the complete source code for Quake 2, version 3.21, buildable with visual C++ 6.0.  The linux version should be buildable, but we haven't tested it for the release.

The code is all licensed under the terms of the GPL (gnu public license). You should read the entire license, but the gist of it is that you can do anything you want with the code, including sell your new version.  The catch is that if you distribute new binary versions, you are required to make the entire source code available for free to everyone.

The primary intent of this release is for entertainment and educational purposes, but the GPL does allow commercial exploitation if you obey the full license.  If you want to do something commercial and you just can't bear to have your source changes released, we could still negotiate a separate license agreement (for $$$), but I would encourage you to just live with the GPL.

All of the Q2 data files remain copyrighted and licensed under the original terms, so you cannot redistribute data from the original game, but if you do a true total conversion, you can create a standalone game based on this code.

Thanks to Robert Duffy for doing the grunt work of building this release.

John Carmack    
Id Software

## Notes about *this* release

I took the original package and imported into Visual Studio 2019, then built it, tested it, and uploaded it here.

That's it. 

There are no additional changes, bug fixes, or tweaks of any kind.

### Additional, *possibly* important info...

* This all happened with the code you see here residing in `E:\Quake2Demo\src` on my computer. There shouldn't be any absolute paths so it shouldn't matter, but just in case, now you know.

* ref_soft.dll does not compile correctly, it trips up on the assembly files.  This may be a setting or an uninstalled component in Visual Studio 2019. I don't care to really dig into it. A fix for this is the ONE and only pull request I'll entertain.
