dell 3480 with sierra 10.12.6

bios -> default settings
- sata operation -> ahci

boot flags
- boot args dart=0 nv_disable=1 -v
- pci devices -> 4 first options
- cpu tuning -> patchAPIC
- binaries patching -> fake cpuid 0x0506e3 -> kernel support cpu

install normally in an empty disk

run multibeast 9.2.0
- uefi boot mode
- bootloader clover 2.4k uefi
- intel hd 6xx

install kexts to solve problems

multibeat voodoo on sound
