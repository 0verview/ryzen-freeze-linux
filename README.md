Install and use the Hardware Enablement kernel:
1. sudo apt-get install linux-image-generic-hwe-22.04
2. kernelstub -v -k /boot/vmlinuz-x.xx.x-x-generic (change to yours veriosn) -i /boot/initrd.img-x.xx.x-xx-generic 
3. sudo reboot

4. sudo nano /etc/default/grub
5. GRUB_CMDLINE_LINUX_DEFAULT="ipv6.disable=1 intel_idle.max_cstate=1"
6. sudo add-apt-repository ppa:oibaf/graphics-drivers
7. sudo apt update && apt upgrade
8. sudo reboot


