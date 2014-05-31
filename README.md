

Linux kernel with Xin-Mo arcade module support for Raspicade distribution Last release 3.12.20+

How to install :

$ git clone https://github.com/ian57/Raspicade-kernel-xinmo.git

$ cd Raspicade-kernel-xinmo

$ sudo cp kernel-raspicade-3.12.20+ /boot/kernel-raspicade-3.12.20.img

$ cd /lib

$ sudo cp -R firmware firmware_old

$ sudo cp -R modules modules_old

$ sudo cp -R ~/Raspicade-kernel-xinmo/modules/lib/firmware/ .

$ sudo cp -R ~/Raspicade-kernel-xinmo/modules/lib/modules/ .

After edit the /boot/config.txt file and modify kernel line

kernel=kernel-raspicade-3.12.20.img

Save an reboot
