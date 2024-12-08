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
sudo pacman -Syu

sudo pacman -S ufw
sudo ufw default deny outgoing
sudo ufw default deny incoming
sudo ufw allow out DNS
sudo ufw allow out WWW\ Full
sudo ufw enable

sudo ufw status verbose

# 22, 6969
```
