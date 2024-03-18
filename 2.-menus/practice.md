# Practice

Both the **trainers** and **timer** menu have a `save settings` button. This button has the same function as the one in settings (see [Settings](settings.md)) which is saving all fp settings to the current profile.

#### Trainers

The **trainers** menu contains various different helpful menus and information screens to help with practicing and learning the game. The following trainers are available:

* **bowser blocks**: When enabled, causes Bowser to only attack using the specified move. Works with both Hallway and Final Bowser, though note that setting lightning will make Hallway Bowser wave since he doesn't have a lightning attack.
* **lzs jumps**: Used to practice _Loading Zone Storage_ jumps. Displays logs with information on why LZS jumps are failed. Also keeps track of the current and most consecutive jumps in the current session which can be seen by pressing the wrench button.
* **action commands**: Used to help learn action command timings. Displays log messages with information on the frame data for action commands, including attacks and blocks.
* **clippy**: When attempting to obtain the _clippy_ state by opening the partner menu while encountering an enemy and riding Lakilester, displays a log telling when you're early or late on the timing.
* **ice staircase skip**: Used to help line up in the proper position to perform the Ice Staircase Skip trick. `position` can be either **good**, **inconsistent**, or **bad**, depending on whether using Lakilester's ability will always, sometimes, or never clip properly.
* **oot ace**: JP-exclusive. Helps with performing arbitrary code execution aided by The Legend of Zelda: Ocarina of Time. `effects` shows the number of active particle effects. `flags` displays whether the animation flags located before the idle timer in Mario's player struct will cause a premature crash. `frame window` displays how big the frame window for stopping the idle timer and getting a successful jump to code stored on the expansion pak is. It will most likely always be 1 unless Ocarina of Time is used to zero out the expansion pak beforehand. Pressing `practice payload` will make it so that upon a successful jump to the expansion pak, the value of the idle timer will be displayed in the bottom-left of the screen. Pressing `oot instruction` will place the same ASM instruction on the expansion pak that doing the proper OoT setup would.
* **save settings**: Saves the current cheats menu to your active settings profile.

#### Timer

The **timer** menu provides a real-time timer that is unaffected by lag. Separately, it also displays 30 fps lag frames by taking half of the game's vertical interrupt counter and subtracting the number of game frames that have passed. Note that lag frames can decrease due to the game speeding up to account for lag. Additionally, the timer is only guaranteed to be accurate on console.

The timer has three modes, **cutscene, loading zone,** and **manual**.

* **cutscene**: In this mode, pressing `start/stop` will prime the timer to start, but it won't start right away. Instead, once primed, the timer will begin the next time a cutscene ends. A cutscene, in this context, is anything that takes the player's control away from Mario, such as entering a loading zone or opening a menu. The timer will then continue to run until the number of cutscenes that have occurred equals the configurable `cs/lz count`. In this way, any arbitrary sequence of events can be timed without worrying about human error affecting the starting/stopping of the timer.
* **loading zone:** This mode functions exactly the same as **cutscene** mode, but it only triggers on loading zones.
* **manual**: This mode is much simpler. Pressing `start/stop` will start the timer immediately, and it will continue to run unless `start/stop` or `reset` is pressed.

The timer will continue to function even if the utility menu is closed, but by default it will not be displayed when running due to lag concerns. Additionally, no log messages related to the timer will be displayed when the timer is running. These can be changed by toggling the `show timer` and `timer logging` options. You can also move the location of the timer with `timer position`. These settings can be saved to your current settings profile with `save settings`.

Note that button combinations can be configured for the `start/stop` and `reset` functions, and the position of the timer can be configured in settings (see [Settings](settings.md)).
