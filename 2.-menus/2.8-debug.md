# 2.8 Debug

_Note: These features are for advanced users. Be careful._

This menu contains various debug features to use for testing;

* **flags:** Display and edit saved game flags. The flags are grouped by the records they are kept in. Use the arrows to cycle between flag records. Press a flag to toggle its state. A red flag is "off", and a green flag is "on". The **log** menu displays a list of recent flag events. When a flag changes, its record, id, and new value is inserted at the top off the list. The **undo** option reverts the effect of the most recent flag event and removes it from the log. The **clear** option removes all flag events from the log, but does not affect the state of the given flags. _Note:_ The flag log only records changes when the log menu is open. If a flag changes and then changes back while the log is closed, these changes will not be recorded.
* **memory:** Memory editor. Use the horizontal arrows to cycle between memory domains, and the vertical arrows to scroll up and down between addresses. Holding Z while scrolling will scroll faster. You can also enter an address manually in the address field. To edit memory, select the desired data type and press a memory cell to modify it.
