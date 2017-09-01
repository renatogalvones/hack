# hack
dell 3480

boot flags
- boot args dart=0 nv_disable=1 -v
- pci devices -> 4 first options
- cpu tuning -> patchAPIC
- binaries patching -> fake cpuid 0x0605e3 -> kernel support cpu

run multibeast 9.0.2
- options
- uefi boot mode
- bootloader clover 2.4k uefi

customize
- intel hd 6xx
- system definitions -> macbook pro -> macbook pro 11.2

reboot
