sudo nano /etc/default/grub

GRUB_CMDLINE_LINUX_DEFAULT="ipv6.disable=1 intel_idle.max_cstate=1"

sudo add-apt-repository ppa:oibaf/graphics-drivers

sudo apt update && upgrade

sudo restart
