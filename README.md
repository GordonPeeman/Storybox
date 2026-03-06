# Storybox
Standalone NFC-based audio "Storybook"
It’s basically a box that plays different stories depending on what NFC tag is being scanned, each represented by a dinosaur figurine.

The stories have been recorded by my son, my wife and myself. The files have been converted to .ogg format where each tag is mapped to a specific audio file defined in a JSON configuration file. I’ve also included a tag in a keychain that if scanned, plays a random story from the library.

Since i have 0 experience in coding, the script has been vibe-coded using multiple AI’s (and a lot of iterations and head scratching) and includes features like volume buttons, pausing when the same tag is scanned and auto-shutdown.

Materials:

Raspberry Pi 3A+
NFC-scanner module (PN532 (over I2C))
Mono amp (MAX98357A)
Visaton FR 87 speaker
Two standard buttons
NFC stickers
3D-printed bases for the tags
Jumper wire cables + speaker cables
A wooden box (with holes drilled in the back for ventilation and sound improvement)
