# hack
dell 3480

bios -> default settings
- disable vt for direct
- sata operation -> ahci

boot flags
- boot args dart=0 nv_disable=1 -v
- pci devices -> 4 first options
- cpu tuning -> patchAPIC
- binaries patching -> fake cpuid 0x0506e3 -> kernel support cpu

run multibeast 9.2.0
- options
- uefi boot mode
- bootloader clover 2.4k uefi

customize
- intel hd 6xx
- system definitions -> macbook pro -> macbook pro 11.2

**second try**
- after multibeast
- dont reboot
- star clover configurator steps

- delete all options from devices Fake Ids
- configure devices and graphics
**end second**

reboot

clover configurator
- mount efi -> current boot disk (**on second try, already mounted**)
- replace all content from efi folder (mounted disk) with efi content form usb efi_backups
- load config plist from efi (mounted)

README steps from download/intel_hd fix

reboot

boot on hd
- fake cpuid flags -> kernel support cpu
