# Coreboot X230t

Prebuilt Coreboot for my X230t, works with X230 as well.

Includes Tianocore.

coreboot.rom is the coreboot build. You can flash it via flashrom, just make sure you use the chip layout file (on the X230 wiki page) for it or else you WILL brick!

The ifdmegbe.bin.new is a patched bottom chip region (flash first!) that had me_cleaner run on it and also has the ifd unlocked, which makes it possible to flash coreboot via flashrom on the laptop itself.

vbios.bin is the dumped vbios from my machine.
