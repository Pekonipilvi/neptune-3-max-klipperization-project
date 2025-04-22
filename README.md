# neptune-3-max-klipperization-project
Just my own backup and file store if i had to reset things



VERSIONS
-----------------------------------------------
mcu(stm32f401xc) - Version: v0.13.0-0-g61c0c8d2e

mcu CB1(linux) - Version: v0.12.0-401-g383b83d78

Host(aarch64, 64bit) - Version: v0.13.0-0-g61c0c8d2e


FOR CONNECTION
-----------------------------------------------
in new install BTT-PAD7 login had changed so had to swap it back on two files

"sudo nano /etc/hostname" - btt-pad7
"sudo nano /etc/hosts" -127.0.1.1 btt-pad7

also i did add private key for it (not really needed on home use..just something im used to)


BOOT FOLDER TWEAKS
-----------------------------------------------
BTT-PAD7 (ON/OFF)
-BTT_PAD7="ON"
Automatic brightness adjustment
-AUTO_BRIGHTNESS="OFF"


ALSO SCREEN ROTATION WAS WHACKY
-----------------------------------------------
and cant really tell how did i do it...nothing seems to have any traces of what file i touched or did nether
1. /boot/system.cfg has values edited for screen rotation
2. nor KlipperScreen Files 
3. or even older /etc/X11/xorg.conf.d/40-monitor.conf file have any 

but it works for now so i can fight this small UI thing when needed. It wasnt that hard to rotate if i remember correctly.



