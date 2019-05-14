# minimal-linux
Minimal linux kernel 4.12.9 with SCSI and ethernet controllers activated

For compiling.

cp -a CONFIG_NAME_DOWNLOAD /home/$USER/linux-kernel$(VERSION)/.config

For edit options with the kernel linux:

make menuconfig.

For compile:

make -j20 $(PROCS)

Replace $(PROCS) for the number of cores of you processor

Implemented for debian based distros (ubuntu,etc) not tested with gentoo and other distributions.

Happy hacking!

