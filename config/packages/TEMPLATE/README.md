Subsystem is designed to search for scripts and packaging information for:

- board (bananapi, udoo, oragnepizero, ...)
- kernel family (sun7i, rk3399, rockchip64, ...)
- common (armbian-config, armbian-desktop, armbian-firmware, ...)

Deb packages are packed and installad in order as written above.

Currently we still use board suppport package for backward compatibility reasons and everything 
is stored there except files like script.bin which goes into family package (armbian-family-sun7i).

It is possible to add unlimited additional packages to any of the category or even make a new top level category.

Features:


