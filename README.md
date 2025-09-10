# bootable-usb-project
A documentation on how to install an operating system on a portable usb flash drive.
##  Objective
   - Reuse an old flash drive
   - Boot an operating system that avoids leaving traces on the host machine
   - Use it as a penetration testing tool kit which can be carried anywhere
##  Tools
   - Balena Etcher
   - Kali Linux ISO ( **Live Boot** )
   - A USB drive (at least **8GB**, 16GB+ recommended)
##  Process 
 ### 1. Installation
- Kali Linux ISO : Go to https://www.kali.org/get-kali/#kali-live and select the recommended point release live image.
- Balena Etcher : Go to https://etcher.balena.io/ and click download Etcher.
 ### 2. Insert the USB
 - Back up any files on the usb - flashing will **erase all data**
 ### 3. Open Balena Etcher
 - Launch the Balena Etcher application
 - Click **Flash from file** and choose the downloaded `kali-linux-xxxx.iso`.
 - Click **Select target** and pick your USB stick.
 - Click **Flash!** and wait for the process to complete.
### 4. Reboot your computer
 - Restart your computer
 - Enter the boot menu (`F12`, `Esc`, or `Del` depending on system)
 - Select your USB drive by ordering it above the host machine's OS
## You should now boot into Kali Linux Live mode 🎉
