# moint dd image
 `losetup --partscan --find --show disk.img`
 `mount /dev/loop0p1 /mnt`
 `...`
 `losetup -d /dev/loop0`
