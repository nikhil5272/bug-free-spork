# 1. Update and upgrade your system
sudo apt dist-upgrade

# 2. Install required packages
sudo apt install gnome-software gnome-packagekit
sudo apt-get install idle3
sudo apt-get install adb
sudo apt-get install discover   # GUI software manager (optional)

# 3. Basic Linux commands
ls        # list directory contents
pwd       # print working directory
cd        # change directory

# 4. Connect ADB shell (for uninstalling bloatware, etc.)
adb -d shell

# 5. Connect to Chromebook using ARC (for installing APK without developer mode)
adb connect arc.

# 6. Install APK
adb install "filename.apk"

# ────────────────
# ⚠️ Extra: If you get this error:
# "error: more than one device/emulator"
# use this command:
adb -s emulator-5554 install "filename.apk"

# 7. for kde plasma desktop try these
start-kde
⚠️ if not working try
startplasma-X11
try these
              cp /etc/X11/xinit/xinitrc ~/.xinitrc
    
          
               /etc/X11/xinit/xinitrc
              /etc/X11/xorg.conf.d/20-intel.conf
 
 
 # 8. for installing minecraft 


          sudo apt-get install gdebi (first install Debian-based Linux distributions)

          t
 
 

              
