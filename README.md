# Basic CH32V307 RISCV Makefile project

Requirements:
 - xpack riscv toolchain (riscv-none-embed-)

Set up udev rules for WCH link
```
sudo cp ./50-wch.rules   /etc/udev/rules.d  
sudo udevadm control --reload-rules
```

Make project
```
make
```


# Licence

Files under Vendor/ come directly from the CH32V307VCT6 project template packaged with MounRiver, a free to download toolchain for the WCH parts based on Eclipse.
However, the source files themselves do not seem to contain a license..

Makefile is based on an example here: https://spin.atomicobject.com/2016/08/26/makefile-c-projects/
