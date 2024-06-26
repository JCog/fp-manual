# Settings

This is where most of the functionality of fp is configured. Use the +/- buttons to select which profile is selected to save/load from. When the game starts, the settings saved to profile 0 are automatically loaded, if any.

* **menu appearance, display, commands**: See below.
* **save settings**: Saves the current settings to the currently selected profile.
* **load settings**: Loads the settings from the currently selected profile.
* **restore defaults** Restores all saved settings to their default values (Does not affect saved profiles). If the saved settings were to become corrupted in such a way that they prevent the game from starting, holding the Start button when the game is starting will load the default settings instead of loading profile zero.

The following settings are saved:

* Menu and on-screen displays appearances and settings.
* Watches.
* Command button binds.
* Activated cheats.
* Activated trainers.

#### Menu Appearance

* **font**: Selects the font of the menu.
* **drop shadow**: Enables/disables the menu drop shadow. Disabling drop shadow can reduce the graphical computation impact of the menu, but may also reduce readability.
* **position**: Moves the on-screen position of the entire menu.
* **background**: Toggles the black background that appears behind the settings.
* **alpha**: Adjusts the opacity of the background

#### Display

* **logging**: Enables/disables and moves the position of all log messages.
* **input display**: Enables/disables and moves the position of the input display.
* **analog type**: Selects whether to display the analog stick as `numerical`, `graphical`, or `both`.&#x20;
* **graphical range**: Adjusts the maximum analog value for the _graphical_ and _both_ displays up to a maximum value of 127. This is to account for varying analog ranges on different controllers.

#### Commands

The **commands** menu lets you bind commands to custom button combinations and/or activate them manually. Pressing the name of a command will activate that command, and pressing the button combo in the right column will bind a button combo to the corresponding command. If you want to unbind a command, press and keep holding L when starting the binding. A button combo for any given command can contain at most four buttons. When activating a command with a button combo, the button combo must explicitly be input the way it appears in the commands menu. For example, a command with the button combo `R + A` will only be activated if you press R first and then A, or R and A at the same time. `A + R`, or `R + B + A` will not activate the corresponding command. If the set of buttons in one button combo is a subset of those in another button combo, the former will be overridden by the latter when both are active simultaneously.

The following commands are available:

* **show/hide menu:** Opens the utility menu if it's closed, closes it if it's opened. _Default: `R + D-Up`_
* **return from menu:** Returns to the previous menu, as if the _return_ button was pressed. _Default: `R + D-Left`_
* **levitate**: Makes Mario fly into the air. _Default: `D-Up`_
* **turbo**: Increases Mario's running speed. _Default: `D-Down`_
* **save position**: Saves Mario's current position and orientation. _Default: `D-Left`_
* **load position**: Loads Mario's saved position and orientation. _Default: `D-Right`_
* **lzs**: Allows Mario to walk into loading zones and store them without taking them. If a menu is then opened and closed after moving somewhere else, Mario will then take the loading zone as though Loading Zone Storage jumps had been performed. _Default: `R + D-Left`_
* **reload map**: Reloads the current map with the last known entrance value. Also works when in battle. _Default: `R + D-Down`_
* **reload last warp**: Reloads the last room warped to through the **locations** menus. _Default: `unbound`_
* **toggle watches**: Toggles whether to display the watches you have set. _Default: `R + D-Right`_
* **reimport save**: Re-imports the last save file imported from the SD card. _Default: `R + Z`_
* **save game**: Saves the game to the current save slot as though a save block had been used. _Default: `L + D-Left`_
* **load game**: Loads the save file from the selected save slot, similar to loading a file from the file select screen. _Default: `L + D-Right`_
* **start/stop timer**: Sets the timer to start after the next cutscene or starts/stops the timer, depending on the timer mode. _Default: `unbound`_
* **reset timer**: Sets the timer back to 0 and reverts it to an inactive state. _Default: `unbound`_
* **show/hide timer**: Toggles whether the timer is showing when it's active. _Default: `unbound`_
* **break free**: Attempts to break any effect that removes control of Mario. _Default: `L + D-Down`_
* **toggle in. disp.**: Toggles the visibility of the input display.
* **clippy**: Toggles the "clippy" state on and off.

_**Warning:**_ Unbinding the _show/hide menu_ or _return from menu_ commands, or binding them to a button combination that will interfere with menu navigation can make it impossible to use the utility menu. If this happens, you can restore the default settings by entering the following button sequence: `D-Up D-Up D-Down D-Down D-Left D-Right D-Left D-Right B A`.

_Note:_ Button combos that interfere with menu navigation for commands that aren't related to menuing are disabled while the utility menu is active.
