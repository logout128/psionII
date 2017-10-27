# Psion II apps
Various OPL apps for Psion II series. Written and tested on Psion II XP.

MasterMind (MMIND.OPL)
----------------------
Well known number guessing game. Player tries to find out a number (four digits without repeating), computer responds by displaying how many digits were guessed on correct position in the number and how many were guessed on wrong position.

ZX VRAM calculator (ZXVRAM.OPL)
-------------------------------
After entering X and Y coordinates (X: 0-255, Y: 0-191, origin in lower-left corner) on ZX Spectrum screen the app calculates and displays three numbers:
* P%: Address in pixel VRAM where the pixel defined by coordinates is stored
* B%: Value of the byte in pixel VRAM to set the specified pixel
* A%: Address in attribute VRAM on which colour of specified pixel is stored

So the result can be used in ZX Spectrum basic as:

    POKE P%, B%     
    POKE A%, colour
