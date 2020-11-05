# chromium78
Downgrade to chromium-browser v78 on a Raspberry Pi  
[![badge](https://github.com/Botspot/pi-apps/blob/master/icons/badge.png?raw=true)](https://github.com/Botspot/pi-apps)  
^ Will be on Pi-Apps very soon.

## To download:
```
git clone https://github.com/Botspot/chromium78

#extract chromium-browser binary
cd ~/chromium78/usr/lib/chromium-browser
unzip ~/chromium78/usr/lib/chromium-browser/chromium-browser.zip
rm ~/chromium78/usr/lib/chromium-browser/chromium-browser.zip
cd ~
```
## To install:
```
sudo cp -af ~/chromium78/. /
```
## To revert back to latest chromium-browser:
```
sudo apt install --reinstall chromium-browser chromium-browser-l10n chromium-codecs-ffmpeg-extra rpi-chromium-mods
```
