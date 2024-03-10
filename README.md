# IEEE-Player-Character-Voice-Installer-
This is a tool and a template that allows you to install player character voice sounds for certain Infinity Engine games. The latest release can be found [here](https://github.com/Incrementis/IEEE-Player-Character-Voice-Installer-/releases).

![Figure11](https://github.com/Incrementis/Infinity-Engine-Modding-Wiki-Content-/blob/main/IEEE%20PCVI/Images/Figure11.png)

## Supported Games
* BG:EE (Baldur's Gate:Enhanced Edition) tested version is 2.6.6.0
* SoD (Siege of Dragonspear) tested version is 2.6.6.0
* BG2:EE (Baldur's Gate 2:Enhanced Edition) tested version is 2.6.6.0
* IWD:EE (Icewind Dale:Enhanced Edition) tested version is 2.6.6.0

## Key Features
* Installs pre-made sound files for player character voices.It is capable of installing WAV and [OGG sound files](https://github.com/Incrementis/IEEE-Audacity-Savefiles-for-Player-Character-/issues/6#issuecomment-1979658895). This renames OGG file extensions to WAV file extensions.
* Optionally scans "dialog.tlk" with the installed soundset and automatically repairs any incompatible "strref" entries, ensuring seamless integration with the selected voice pack.
* Serves as a template for creating custom player character voice sets.
* Requires minimal coding knowledge

IEEE PCVI mainly targets soundslots used by the original Infinity Engine games in their selectable
voice sets within the character customization menu.

The supported sound slots as a list for the individual games are marked with Postfix and their
meaning can be found in the “guides” folder or online:
* [BG:EE (Baldur's Gate:Enhanced Edition)](https://github.com/Incrementis/Infinity-Engine-Modding-Wiki-Content-/blob/main/IEEE%20ASfPC/Tables/BGEE/charsnd2DA_SLOTS.pdf)
* [SoD (Siege of Dragonspear)](https://github.com/Incrementis/Infinity-Engine-Modding-Wiki-Content-/blob/main/IEEE%20ASfPC/Tables/SoD/charsnd2DA_SLOTS.pdf)
* [BG2:EE (Baldur's Gate 2:Enhanced Edition)](https://github.com/Incrementis/Infinity-Engine-Modding-Wiki-Content-/blob/main/IEEE%20ASfPC/Tables/BGEE2/charsnd2DA_SLOTS.pdf)
* [IWD:EE (Icewind Dale:Enhanced Edition)](https://github.com/Incrementis/Infinity-Engine-Modding-Wiki-Content-/blob/main/IEEE%20ASfPC/Tables/IWDEE/charsnd2DA_SLOTS.pdf)

IEEE PCVI uses the following postfixes:

| Postfixes  ||
| ---------- |-|
|b           | l_
|c           | i
|d           | j
|a           | k
|8           | 0_
|9           | 1_
|g_          | 2_
|h_          | 3_
|l           | W
|m           | z
|e           | 1
|n           | 2
|o           | 3
|p           | 4
|q           | 5
|r           | 6
|f           | 7
|g           | s
|h           | t
|0           | u
|k_          | v

If you are interested installing more voice lines for the player character, an alternative system is the
[soundset installation tool](https://github.com/Gibberlings3/EE_soundset_tool).

## Guides
For more detailed information, please visit this [project's wiki](https://github.com/Incrementis/IEEE-Player-Character-Voice-Installer-/wiki).

## Operating Systems
* Implemented and tested on Micrososft Windows 11

## Compatibility
* It uses the unofficial [soundset convention](https://www.gibberlings3.net/forums/topic/34560-adding-soundsets-to-the-ees-using-the-ee-soundset-tool/) for advanced sound slots, ensuring compatibility with sound files developed under this standard.
* WAV files only at this stage of development

## Troubleshooting
### There are known issues when installing SOD as DLC for BG:EE
* [DLCmerger](https://github.com/Argent77/A7-DlcMerger/releases) is recommended for installation

## Languages
* English
* Deutsch

## Special Thanks
Thanks to ["The Gibberlings 3"](https://www.gibberlings3.net/forums/) forum and Discord users who helped me with hints and information:
* CamDawg
* Graion Dilach
* DavidW
* jmerry
* subtledoctor
* Jarno Mikkola
* AL|EN
* Zelazko
* Jastey
* argent77
* Bubb
* suy

## Copyright
The "*IEEE PCVI*" Project is not developed, supported, or endorsed by BioWare™, Interplay/BlackIsle, Beamdog, or Wizards of the Coast.

"*IEEE PCVI*" is licensed under a [Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/).
