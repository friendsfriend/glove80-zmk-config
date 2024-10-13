# Personal Glove80 zmk configuration

If you want to change something to the keymap you can just edit it and commit / push the changes.
The firmware will be built by github actions.

Two versions of the firmware are included in the repository
- A US layout with german locale and and an additional layer for german special characters
- The fist layout extended by homerow modifications

## Flashing the firmare to the Glove80
- Download the build firmware from the repository
- Connect both halfes of the Glove80 to your computer

Flash the right half
- Plug the right half into your computer
- Press MAGIC + ' (Puts the Glove80 into Bootloader mode)
- Copy the .u2f file to the Glove80

Flash the left half
- Plug the left half into your computer
- Press MAGIG + ESC (Puts the Glove80 into Bootloader mode)
- Copy the .u2f file to the Glove80

Reset to factory
- Press PgDown + 8 while powering on the right half and hold for 5 seconds
- Press MAGIC + 3 while powering on the left half and hold for 5 seconds
- Switch on both halfes at the same time
- Press MAGIC + T to see if both halfes are glowing
- Press MAGIC + T to deactivate RGB again
- Wait for roughly one minute
- Repair with all devices

