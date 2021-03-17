# USGerman-win

This repository provides settings to install a Keyboard Layout that behaves like https://github.com/janv/usgerman, but on Windows.
This means it is specifically meant for people that use an US-International MacOS Keyboard on Windows.

Changes implemented:

* Copy and paste are done with `⌘+C` and `⌘+V` respectively (and all other commands that involve usage of the control key, too).
* Umlauts can be typed with `LEFT-ALT+a,o,u` (for ä, ö, ü)
* `CapsLock` is deactivated and set to `ESCAPE`. While not neccessary, it is a personal preference (and helpful for VIM).

*NOTE: For the Umlaut feature I had to swap **LEFT-ALT** with **ALT-GR**. This can lead to confusion when used in some apps.*

*NOTE: `CONTROL` and `⌘` (aka. the Windows key) are swapped. This means that all Windows key shortcuts are now activated using `CONTROL`.*


## Intalling

* Install [SharpKeys](https://github.com/randyrants/sharpkeys) and load the `standard.skl` config file. Log off or restart your computer.
* Install the KeyboardLayout from usgerman.zip or compile it yourself with the [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=102134). To do that, load the `USGerman.klc` file.
* I included another SharpKeys configuration for videogames, where I only deactivated `CapsLock`. Having can `CONTROL`and `⌘` (aka. the Windows key) swapped can be troublesome when playing.

