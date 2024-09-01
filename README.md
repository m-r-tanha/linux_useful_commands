# Linux Useful Commands
### No space left on device:
df -h
sudo du -h --max-depth=1 / | sort -hr | head -n 20
sudo apt autoremove
sudo apt clean
sudo apt autoclean
sudo apt-get remove --purge linux-image-x.x.x.x-generic
sudo journalctl --vacuum-time=7d
sudo rm -rf /tmp/*
sudo find / -type f -size +100M
sudo rm -rf /var/cache/apt/archives/*
sudo reboot
sudo apt update
sudo apt upgrade

Resize the Disk (If Possible):
If the above steps don't free up enough space, and you have the ability to do so, consider increasing the size of your virtual machine's disk.


