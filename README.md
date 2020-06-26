# Installition Notes UBports for Onclite

Installition
0.1 Unlock Bootloader               
0.5 Install TWRP          
0.9 Reboot in TWRP        
1. flash UBports-vendor.zip
2. flash ubports-gsixx.zip
3. flash halium-boot.zip
4. flash halium-ramdisk.zip
5. flash apparmor.zip
6. Reboot to system!
7. Fix camera

Fix camera:
    Password is "phablet"
    To connect to shell use ssh phablet@10.15.19.82
    In order to get camera working need to run commands blew in terminal:
wget https://static.peat-network.xyz/junk/ubports/com.ubuntu.camera_3.1.2+gstdroid3_armhf.click
