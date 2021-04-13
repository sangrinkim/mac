# Ubuntu Dual Boot on Mac OS X

Test bed:
* MacBook Pro(Retina, 15-inch, Mid 2014)
* Ubuntu 18.04

Steps:
1. Create Bootable Ubuntu USB flash drive

2. Make a new partition for Ubuntu
Disk Utility > Select target Disk > Click Partition Menu > Click "+" Button > Set Partition Information(format is MS-DOS) > Set Partition Size > Apply > Partition > Continue

3. Restart > Hold on **option** key

4. Select EFI boot DISK > Install Ubuntu
(If you have ACPI error, press e on GRUB menu, add "acpi=off" at the and of the kernel line, push F10)

5. Double Click "Install Ubuntu.." Icon on screen > Install Ubuntu
