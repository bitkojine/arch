# arch

🎧 Bluetooth:
```
sudo pacman -Syu
sudo pacman -S bluez
sudo pacman -S bluez-utils
systemctl enable bluetooth.service
systemctl start bluetooth.service
```

🧱 UFW:
```
sudo ufw default deny outgoing
sudo ufw default deny incoming

sudo ufw allow out DNS
sudo ufw allow out WWW\ Full

# 22, 6969
```
