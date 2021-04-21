# Raspberry-pi-pico-udev
To use the arduino ide with pico using a linux computer

So you have just installed Arduino IDE on your linux computer to program your pico( or any other RP2040 board). Just opened the blink example sketch but after it compiled it showed an error while uploading (The pico was in bootloader mode). What should you do now.
<It is only for the official version, not @earlephilhower 's version'>

the problem might be due to missing udev rules (Arduino dosn't use mass storage upload but the other interface exposed by the bootloader). 

run the `install.sh` file as root.

Step 1 
Download the `install.sh` file
Step 2
Open the folder where you have downloaded the file in terminal, usingh `cd` command (e.g. `cd downloads`)
Step 3
type `sudo -i` to become root
Step 4
run the file using `bash ./install.sh`

Voila, it should work now.



P.S. This is my **first Github Repository**. Sorry for (if any) typos.
