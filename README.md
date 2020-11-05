# chromium78
Downgrade to chromium-browser v78 on a Raspberry Pi

## To install:
```
git clone https://github.com/Botspot/chromium78

#extract chromium-browser
cd /home/pi/chromium78/usr/lib/chromium-browser
unzip /home/pi/chromium78/usr/lib/chromium-browser/chromium-browser.zip
cd

#install
sudo cp -af ~/chromium78/. /
```
## To revert back to latest chromium-browser:
```
sudo apt install --reinstall chromium-browser chromium-browser-l10n chromium-codecs-ffmpeg-extra rpi-chromium-mods
```
