# Chrono Trigger Autosplits by Meowski v0.2

## Usage

You will need the following:

* [SNI](https://github.com/alttpo/sni/releases) (QUsb2Snes works too, but I've never tried it)
* Hardware or software that is capable of loading and playing SNES ROM files, including:
    * An emulator capable of connecting to SNI. I recommend [snes9x-nwa](https://github.com/Skarsnik/snes9x-emunwa/releases) or [BSNES-plus](https://github.com/black-sliver/bsnes-plus)
    * An SD2SNES, FXPak Pro, or other compatible hardware. **note: modded SNES minis are currently not supported by SNI.**
* A Chrono Trigger ROM file

Setup:
1. Start your Chrono Trigger ROM and run SNI. Emulator users may need to follow an additional step:
   * **BSNES-Plus**: You don't need to do anything extra
   * **snes9x-nwa**: Click on the Network Menu and check **Enable Emu Network Control**
   * **for other SNI-compatible emulators**: copy the steps for your emulator found [in this Archipelago setup guide](https://archipelago.gg/tutorial/A%20Link%20to%20the%20Past/multiworld/en) under "Connect to the client". The Connector.lua file that you may need should be included with SNI
2. Go to [the USB2SNESSplitter releases page](https://github.com/usb2snes/LiveSplit.USB2SNESSplitter/releases), download *LiveSplit.USB2SNESSplitter.dll*, and put it in the *\Component* folder in your LiveSplit installation
3. Start LiveSplit and open your Chrono Trigger layout and splits
4. Right click and select *Edit layout*
5. Click on the plus sign and choose *Control -> USB2SNES Auto Splitter*
6. Click on *Layout Settings* and go to the tab named *USB2SNES Auto Splitter*
7. Click on *Autodetect*. This should populate the field to the left of it. If it didn't, then you didn't hook up SNI properly and need to go back to step 1.
8. Download the file *Chrono Trigger.json* provided with this README and add it as a *Config file*. **IF YOU ARE RUNNING NG+**, you need to use the file *Chrono Trigger (NG+).json* instead. I recommend that you have separate layouts for each category that you run. Additionally, any time you update to a newer json file, **you need to add it as a config file in the layout settings again**.
9. Now you'll get a list of all of your splits. The program tries to match them with the definitions in the config file, and when it can't, you manually pick it in the drop-down menus. Your splits will likely be different, but it should look something like this: ![](./livesplit%20layout%20example.png) 

## Split progress

Split | Category | Implemented | Tested on Practice ROM | Tested on Vanilla
:--- | :---: | :---: | :---: | :---:
autostart | No LSS | X | X | X
Yakra (room exit) | No LSS | X | X | X
Dragon Tank (HP 0) | No LSS | X | X | X
Dragon Tank (catwalk exit) | No LSS | X | X | X
5 Slimes (room exit) | No LSS | X | |
R-Series (HP 0) | No LSS | X | X | X
Heckran (cave exit) | No LSS | X | X | X
Zombor (Zenan Bridge Exit) | No LSS | X | X | X
Masamune (HP 0) | No LSS | X | X | X
Nizbel (HP 0) | No LSS | X | X | X
Flea (HP 0) | No LSS | X | X | X
Slash (HP 0) | No LSS | X | X | X
Magus (HP 0) | No LSS | X | X | X
Magus (kneels) | No LSS | X | X | X
Dactyl Nest exit | No LSS | X | X | X
Black Tyrano (HP 0) | No LSS | X | X | X
12,000 B.C. exit | No LSS | X | X | X
Retinite (HP 0) | No LSS | X | X | X
1999 | No LSS | X | X | X
Lavos Shell - Final Shell (HP 0) | No LSS/NG+ | X | X | X
Lavos Body (HP 0) | No LSS/NG+ | X | X | X
Lavos Core (elixir glitch used) | No LSS | X | X | X
autostart | NG+ | X | X | X
candy skip | NG+ | X | X | 
Lavos Core (damage number at peak) | NG+ | not sure how to do this | | 
Epoch | 100% | X | | 
Giga Gaia (HP 0) | 100% | X | |
Dalton Plus (HP 0) | 100% | X | |
Golem Twins (HP 0) | 100% | X | |
Masamune 2 | 100% | X | | 
Son of Sun (HP 0) | 100% | X | | 
Giant's Claw (exit) | 100% | X | |
Mother Brain (HP 0) | 100% | X | |
Yakra XIII (HP 0) | 100% | X | |
Death Peak exit | 100% | X | | 
Ozzie's Fort exit | 100% | X | | 
Mega Mutant (HP 0) | 100% | X | | 
Black Omen elevator exit | 100% | X | |
Mammon Machine (HP 0) | 100% | X | |
Queen Zeal - Final Form (HP 0) | 100% | X | |
Yakra (HP 0) | Glitchless | X | |
Guardian (HP 0) | Glitchless | X | |
Heckran (HP 0) | Glitchless | X | |
Zombor (HP 0) | Glitchless | X | |
Nizbel II (HP 0) | Glitchless | X | |
Mud Imp (HP 0) | Glitchless | X | |
Rust Tyrano (HP 0) | Glitchless | X | |
Giga Mutant (HP 0) | Glitchless | X | |
Lavos Core (first red frame) | Glitchless | not sure how to do this | |
All Endings splits | All Endings | haven't started these | |
Low Level splits | Low Level | LMAO | | 