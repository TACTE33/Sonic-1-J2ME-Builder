8# Sonic-1-J2ME-Builder
A Source Port of all Sonic 1 J2ME versions.

SonJ2ME Builder (RetroMe Engine)
​A modular C/SDL3 source host and custom scripting framework designed to port and modernize J2ME Sonic the Hedgehog mobile ports (such as the Glu Mobile 2006/2012 releases).

​🚀 Features
​Asset Decoupling: Uses original .jar files purely as an asset bank for graphics, tilemaps, and audio.

​Modular Architecture: Clean directory separation between engine source code (src/), build targets, and runtime game assets (Data/).
​
Custom .rme Scripting: Replaces legacy Java code with human-readable script definitions for game logic, object behaviors, and stage layouts.
​Dual Execution Modes: Support for dynamic runtime script interpretation (Script Mode) or compiled binary bytecode (Bytecode Mode).
​
⚙️ How to Set Up
​Place your target J2ME .jar file into the bin/ directory.
​Run SonJ2ME_Extract.bat to unpack graphics, palettes, and tile data.
​
🛠️ How to Compile
​Run your preferred platform build script (SonJ2ME_PC.bat, SonJ2ME_Android.bat, or SonJ2ME_Web.bat).
​Ensure the extracted data is properly populated in the Data/ directory.
​Execute the binary using either script interpretation or pre-compiled bytecode.

(This project is in progress...)
