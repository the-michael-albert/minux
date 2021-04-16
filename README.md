# minux
Michael's Linux
Steps:
sudo apt-get install bison
sudo apt-get install libssl-dev
sudo apt-get install libelf-dev
sudo apt-get install qemu-system-x86

wget https://mirrors.edge.kernel.org/pub/linux/kernel/v5.x/linux-5.9.9.tar.xz
tar -xf ./linux-5.9.9.tar.xz


wget https://busybox.net/downloads/binaries/1.30.0-i686/busybox
# puts it in "arch/x86/boot/bzImage"
#tar jfx busybox-1.33.0.tar.bz2

chmod +x busybox

https://jootamam.net/howto-initramfs-image.htm
https://superuser.com/questions/1613122/how-to-make-an-iso-file-from-bzimage-and-initramfs
