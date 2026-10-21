PLAYER SKINS OVERHAUL  (Middle-earth: Shadow of War)                                      version 3.7
=============================================================================================

Skin Overhaul Project is a project that I have made to overhaul the character skins in shadow of war. I will be updating this mod to add new skins.

WHAT'S IN THE DOWNLOAD
  PlayerSkinsOverhaul.arch06            the mod (goes into the game folder)
  x64\plugins\PSO_RingSwap.dll          optional ring plugin (the New Ring for the two new skins)
  Player Skins Overhaul - README.txt    this file

REQUIREMENTS
  * Middle-earth: Shadow of War on PC (Steam), fully updated.
  * For the New Ring on Prologue Talion and Celebrimbor Talion only: "Shadow of War DLL Loader" by survivalizeed
    https://www.nexusmods.com/middleearthshadowofwar/mods/99
    Everything else works without it.

INSTALL  
  1. Open the game folder: in Steam, right-click Middle-earth: Shadow of War
     > Manage > Browse local files.
  2. Copy PlayerSkinsOverhaul.arch06 into that folder (next to the other .arch06 files).
  3. Open the "x64" folder.
  4. Right-click "default.archcfg" > Open with > Notepad.
     (If Notepad isn't listed, choose "Choose another app" and pick Notepad.)
  5. Go to the very bottom of the file, press Enter to start a new line, and type exactly:

       ..\PlayerSkinsOverhaul.Arch06

     It must be the LAST line of the file. Save (Ctrl+S) and close Notepad.
  6. Optional, for the New Ring:
     a. If you don't have it yet, install "Shadow of War DLL Loader" (link above): put its files into the
        game's x64 folder and create a folder named "plugins" inside x64.
     b. Copy x64\plugins\PSO_RingSwap.dll from this download into the game's x64\plugins folder.
  7. Start the game and pick a skin in the Skin Selection menu.

  Back up your save before first use, as with any mod. Saves:
  Steam\userdata\<your id>\356190\remote\ (Steam Cloud keeps a copy too).

UPDATING FROM AN OLDER VERSION
  Close the game and replace PlayerSkinsOverhaul.arch06 (and PSO_RingSwap.dll if you use it) with the new
  files. The default.archcfg line stays the same.
  From "Celebrimbor Restored": delete CelebrimborRestored.arch06 and remove the line
  ..\CelebrimborRestored.Arch06 from x64\default.archcfg, then install as above.

UNINSTALL
  0. In the game, switch to a normal skin first if you are wearing Prologue Talion or Celebrimbor Talion.
  1. Open x64\default.archcfg in Notepad, delete the line ..\PlayerSkinsOverhaul.Arch06 and save.
  2. Delete PlayerSkinsOverhaul.arch06 from the game folder.
  3. Delete x64\plugins\PSO_RingSwap.dll, PSO_RingSwap.txt and PSO_RingSwap.state (if present).

WHAT IT DOES

  CELEBRIMBOR (after the Shadow Wars ending)
    * Blue wraith effects instead of the green Dark Talion ones
    * Elven Rage as the ultimate instead of the Ringwraith 
    * The normal brand on dominated orcs, and the New Ring instead of Isildur's ring
    * Celebrimbor's voice and grunts.
    * Celebrimbor's speeches after you take a fortress (they cycle, like the original ones)
    * No voice lines when you fast travel or respawn (no Shadow Wars lines, no Talion banter)
    * No Talion replies to the overlord's taunt in the throne room
    * Raise Dead still works

  PROLOGUE TALION (new skin, sword icon)
    * Talion as he looks in the prologue, with his own wraith (not Celebrimbor) and his own voice
    * No Celebrimbor grunts or banter (also when he dashes), 
    * No Shadow Wars lines when he fast travels or respawns
    * Elven Rage as the ultimate instead of the Ringwraith 
    * Raise Dead still works 
    * Wears the New Ring with the plugin.

  CELEBRIMBOR TALION (new skin, hand-and-sword icon)
    * Talion as he was while bound to Celebrimbor, before he took Isildur's ring 
    * Celebrimbor's wraith and blue wraith effects 
    * Celebrimbor's grunts and banter
    * Celebrimbor's speeches after taking a fortress 
    * No Shadow Wars lines on fast travel 
    * Raise Dead still works
    * Elven Rage as the ultimate instead of the Ringwraith 
    * Wears the New Ring with the plugin.

  SKIN MENU
    Both new skins appear after the normal Talion skin, with their own icons and descriptions, and the row
    is spaced so all 10 skins fit inside the menu frame.

NOTES
  * Steam's "Verify integrity of game files" removes the archcfg line: add it again (install step 5).
  * The new skins' menu descriptions are in English. With another game language they may be empty.
  * Ring plugin: it only changes which ring model is drawn, never your save. It writes a small log
    (PSO_RingSwap.txt) and remembers the last ring (PSO_RingSwap.state) so the new skins spawn with the New
    Ring. If you load a save that was wearing a different skin than your last session and the ring is
    missing, switch skins once.
  * The desert fortress (Lithlad) has only one Celebrimbor speech in the game; there Talion may still speak.
  * Not compatible with other mods that replace game.gamedb, interface\bundles\ingame_tex.bndl or the English
    string table (database\string\enus\string.strdb). Whichever is last in default.archcfg wins.
  * Made for the final patch of the game. If the game is ever updated, wait for a mod update.

