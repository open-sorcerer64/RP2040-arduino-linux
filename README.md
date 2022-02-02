# Raspberry-pi-pico-udev
## A Simple Script to program your RP2040 micro-controller (like, Raspberry Pi Pico) on Arduino IDE using a Linux PC


![Example Image](https://github.com/open-sorcerer64/Raspberry-pi-pico-udev/blob/main/example.png?raw=true)

If the IDE throws an error while uploading code to micro-controller then you're at the right place, the problem might be due to missing `udev` rules (Arduino dosn't use mass storage upload but the other interface exposed by the bootloader). 

### To run the script:

```bash
mkdir ~/temp
cd ~/temp
wget https://raw.githubusercontent.com/open-sorcerer64/Raspberry-pi-pico-udev/main/install.sh 
./install | sudo bash
```

Voila, it should work now.

If you find any problem feel free to open a [issue](https://github.com/open-sorcerer64/Raspberry-pi-pico-udev/issues)
