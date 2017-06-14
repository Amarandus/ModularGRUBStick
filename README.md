# ModularGRUBStick
Handwritten configurations for a modular multiboot usb stick.

## READ THIS!

Please use with caution, it is not my fault if you destroy your system. You have been warned.
Do whatever you want to with this, I don't really care.

This Repo is just for releasing the files to help other users, as it was somewhat hard to get this rolling in a nice way.
I can not repeat myself enough, this is not well maintained and is only created for publishing reasons!


The configs are somewhat old, as I did not update for a while. You may fix this by yourself, if you want to.


UEFI is currently not supported.


## Legacy-install:
 * Mount Stick to /mnt (ext4 should work)
 * sudo mkdir /mnt/boot
 * sudo grub-install --boot-directory=/mnt/boot
 * Put the files on the stick and modify grub.cfg to match the used systems.



## Some notes
Remember that I won't include the ISOs and this was no hard work!
Some isos (like every arch-based) needs to be extracted into /system/<name>. This may be done by mounting 
the iso and using rsync.

I won't update this on a regular basis, so if anyone feels the need for a pull request, go on.
