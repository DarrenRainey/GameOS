To built this Debain based distro you will need to first do

apt-get install xorriso live-build syslinux squashfs-tools

then chroot to source\base

and run the following commands


chroot chroot
mount none -t proc /proc
mount none -t sysfs /sys
mount none -t devpts /dev/pts
export HOME=/root
export LC_ALL=C
export PS1="\e[01;31m(live):\W \$ \e[00m"
