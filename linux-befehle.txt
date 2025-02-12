sudo shutdown -h now
sudo reboot -h now

sudo apt-get update
sudo apt-get upgrade

ip a -> Netzwerkinfos

iwconfig -> WLAN infos
iwconfig wlan0 power off -> Energiesparmodus WLAN deaktivieren

touch -> datei erstellen
rm -> datei löschen
rm -r ORDNER -> ordner löschen

sudo rpi-update

schreibrecht auf ordner geben:
sudo chmod 777 -c -R /ort/ordner


prozesse anzeigen und killen:
ps -ax
ps -a -> nur User prozesse
kill {PID} -> killt


Cron:
crontab -e
python3 /home/pi/Fan-Steuerung.py & -> "&" ist wichtig weil sonst gewartet wird bis prozess fertig ist!

Netzwerkeinstellungen PI:
sudo nmtui

systeminfo:
neofetch

IP-Adressen scannen:
sudo nmap -sT 192.168.1.0/24
