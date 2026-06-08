# mag_alt_ctrl_jam_launcher_ahk
The autohotkey script for the alt control jam launcher really needed to be in its own repo

[josephalopod](https://github.com/josephowen) has contributed a massive amount to this project.

For use with this game launcher: https://github.com/andymasteroffish/mag_alt_ctrl_jam_launcher

Versions for AutoHotkey 1 and 2 are provided

# AutoHotkey 1 Version

Tested with this version: https://www.autohotkey.com/download/1.1/AutoHotkey_1.1.37.02_setup.exe

# Some notes for the AutoHotkey 2 Version:

Update auto_launch.ahk to use AutoHotkey 2.
This update makes a few changes to functionality:
- Running the script immediately closes everything before opening the launcher.
- Cursor can optionally be shown when games are open (it is still hidden whenever the launcher is open).
- The script never moves or clicks the mouse.
- If there is only one window active (which should be true whenever the launcher or a game is open) the script will check that the window is active every 200ms and make it active if it is not.