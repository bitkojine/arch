sudo systemctl enable bluetooth.service
sudo systemctl start bluetooth.service

sudo systemctl enable ufw.service
sudo ufw default deny outgoing
sudo ufw default deny incoming
sudo ufw allow out DNS
sudo ufw allow out WWW\ Full
sudo ufw allow out SSH
sudo ufw enable
