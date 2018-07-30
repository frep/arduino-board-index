# frep's Package Lists for the Arduino v1.6.4+ Board Manager

This repo contains the custom `package_*_index.json` files that can be used to add new
third party boards to the Arduino v1.6.4+ IDE.

Reminder:
To calculate the size and the checksum, the program md5deep can be used. Once installed,
get the informations by calling
```
sha256deep64 -r -z frep-samd-0.1.0.zip
```

## Usage:
* Download and install arduino IDE http://www.arduino.cc/en/Main/Software
* In Arduino: go to "Prefences" and add to "Additional Board Manager URLs" followin URL:
*  `https://raw.github.com/frep/arduino-board-index/master/package_frep_index.json`
* go to "Tools > Board > Board Manager" and select Type: Contributed and
* Install "frep's SAMD Boards
* Select the switchM0D with "Tools > Board > frep SAMD"
