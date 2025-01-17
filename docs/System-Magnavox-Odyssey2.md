# Magnavox Odyssey²

## Overview

- Core: `o2em`
- Paths:
  - `/roms/odyssey`
  - `/roms/videopac`
- Supported Extensions: `.bin .BIN .zip .7z`

## BIOS

There are four bios files required for the Odyssey/VideoPac:

| Filename    | md5                              |
|-------------|----------------------------------|
| o2rom.bin   | 562d5ebf9e030a40d6fabfc2f33139fd |
| c52.bin     | f1071cdb0b6b10dde94d3bc8a6146387 |
| g7400.bin   | c500ff71236068e0dc0d0603d265ae76 |
| jopac.bin   | 279008e4a0db2dc5f1c048853b033828 |

## Controls

Some games on the Odyssey have multiple variants of the game on the cartridge. When they boot up, a Select Game screen will be displayed. You choose the game by using the 1-4 numeric keys, either using the controller buttons mapped to numeric keys or using the onscreen keyboard.

The onscreen keyboard uses the Action key to press the keyboard button. There's no indication that the button has been pressed on the keyboard itself.

Unfortunately, non-numeric keyboard buttons can't be mapped to controller buttons. This means that most games that control with the keyboard rather than the joystick will be unplayable.

| Odyssey Button    | RG Button |
|-------------------|-----------|
| Action            | B         |
| Onscreen Keyboard | Select    |
| Numeric Key 0     | X         |
| Numeric Key 1     | L1        |
| Numeric Key 2     | R1        |
| Numeric Key 3     | L2        |
| Numeric Key 4     | R2        |
| Numeric Key 5     | L3        |
| Numeric Key 6     | R3        |

## Add Support for The Voice Speech Synthesis Module

1. Go to the O2EM project homepage and download both sound sample sets.
2. On your GAMES partition, inside the `BIOS` directory, create a `voice` directory and unzip the contents of both zip files into it.
3. Test to make sure it's working.  The game "K.C.'s Kracy Chase' is a quick and easy way to test the functionality as it plays voice samples at the start of gameplay and regularly throughout.