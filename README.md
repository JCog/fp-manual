# 1. Installation

fp supports both the US and JP versions of Paper Mario on N64, Wii, and Wii U. Use the [web patcher](https://fp-web-patcher.vercel.app/) to install the latest version. For legal reasons, you must provide a copy of the base game yourself.

* **N64:** Provide an N64 ROM in `.z64` format (big endian). If the file ends in `.z64` but the patcher doesn't recognize it, it might be in a different format with the wrong extension. Try swapping it [here](https://hack64.net/tools/swapper.php).
* **Wii:** Provide a `.wad` file. A separate N64 ROM isn't required as the patcher will use the one in the WAD.
* **Wii U (experimental):** Provide decrypted game data packed in either a `.zip` or `.tar` file. This should include `code`, `content`, and `meta` folders. They do not need to be in the root of the archive, but they must all be in the same folder. Note that while this is an option, it's still somewhat experimental with minimal testing, and you may run into issues installing. Expect only minimal support.
