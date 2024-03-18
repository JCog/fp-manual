# Watches

This menu lets you add custom RAM watches to observe arbitrary parts of game's memory in real-time. Pressing the plus icon will add a new watch, and pressing the cross next to a watch will remove that watch. After adding a watch, enter a memory address and value type to display the value at that address. These watch types are available:

* **u8:** one-byte value, unsigned.
* **s8:** one-byte value, signed.
* **x8:** one-byte value, hexadecimal.
* **u16:** two-byte value, unsigned.
* **s16:** two-byte value, signed.
* **x16:** two-byte value, hexadecimal.
* **u32:** four-byte value, unsigned.
* **s32:** four-byte value, signed.
* **x32:** four-byte value, hexadecimal.
* **f32:** four-byte value, IEEE 754 single-precision floating-point.

Pressing the wrench button next to a watch will show that address in the memory editor (see [Debug](debug.md)). Pressing the anchor button will release the watch from the watches menu so that it's always visible, even when the menu is closed. When a watch is released, a positioning button will appear which lets you change the position of the watch on the screen. Holding Z when positioning the watch will move it faster. Pressing the wrench icon next to a watch will open the memory editor at the address of that watch. The **visible** option can be unchecked to hide all watches globally.

Watches can be imported from text files on an SD card by pressing the folder icon. Press a watch file to bring up a list of all watches contained in that file. Press a watch to import it to your watch list. When you've imported all the watches you need, press **return** to go back to the watches menu.
