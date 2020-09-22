# 64-bitify
Script to make your raspberry pi 64-bit. Works on all Raspberry Pi 4s running Raspberry Pi OS and Raspberry Pi OS-based OSes. This is alpha code and might brick your pi so MAKE SURE TO BACKUP! The code simply makes your kernal 64-bit, so you get a performance boost, while sill letting you run your 32-bit apps in a 32-bit userland. 

# Caveats 
There are caveats to this, but if you have any problems, then try disabling 64-bit with the script and reboot. If it still is broken, then maybe use that backup I told you to make. So far, it's been noted that Kodi runs a little slower because the renderer is blocked, Java (NOT openJDK) doesnt work,  KDE shell doesnt work either, and Box86 doesnt work without recompiling for 64 bit. Wolfaram and Mathamatica, doesnt work, but a workaround is listed here:https://www.raspberrypi.org/forums/viewtopic.php?t=250730.

# Download script
Download script to make your existing install 64-bit: `cd ~ && wget https://raw.githubusercontent.com/mobilegmYT/64-bitify/master/64-bitify.sh & chmod +x 64-bitify.sh & ./64-bitify.sh`

# Download OS
Download 64-bit img version of TwisterOS: http://download1980.mediafire.com/0d6s18sgqkcg/dbc83jpil9fj54e/TwisterOS-64bit.img.xz

# Performance
The pi isn't noticably faster, but if you do a high-performance task like 

# Help
Go to the Pi Labs discord https://discord.gg/QGVRzJ for help with this version of TwisterOS. My nametag is "Raspberry Pi News#7199".

# Credits
The code to make your pi 64-bit is from https://medium.com/for-linux-users/how-to-make-your-raspberry-pi-4-faster-with-a-64-bit-kernel-77028c47d653

