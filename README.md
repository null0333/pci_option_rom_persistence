# pci_option_rom_persistence
persistence via flashing NIC pci option rom

notes:
bootutil shows flash not supported despite tested NIC (8086:10bf) being on ipxe's supported hardware list and showing on the list

todo:
https://marc.info/?l=flashrom&m=144225228219353&w=2
- IMPORTANT: use flashrom to dump pxe rom
- use flashrom to write helloworld efi application to option rom
- chainload efi application stored in nvram for extra storage
- infection
