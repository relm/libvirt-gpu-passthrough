# Skeen's Virtual Gaming Rack Machine
Reference from the [Arch Linux wiki](https://wiki.archlinux.org/index.php/PCI_passthrough_via_OVMF/Examples#Skeen.27s_Virtual_Gaming_Rack_Machine)


Repository is layed out as `/` on the host.

Files:
* `./etc/libvirt/qemu/win10-2.xml`: LibVirt QEMU/KVM configuration file.
* `./home/skeen/Desktop/GF100.rom`: Original ROM pulled from ASUS GTX 480 using GPU-Z
* `./home/skeen/Desktop/GF100_updGOP.rom`: GOPupd'ated ROM referenced from the LibVirt configuration file.
