# System 76 Graphics Switcher

## Description

Graphics switch when called switches between intel and nvidia graphics settings
using the [system76-power](https://github.com/pop-os/system76-power) utility.
The script will also restart the computer after toggling the graphics mode. It
is meant as a time saver when saving you from swapping with 
`sudo system76-power intel` and then `sudo systemctl reboot` which I found 
myself typing too often

## Usage
Simply copy the script to somewhere on your path and call it
```sh
> chmod +x ./graphics-switch && sudo cp ./graphics-switch /usr/local/bin

> graphics-switch
```
