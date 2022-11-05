# Configure Compute Module 4 on IO Board
 ### This procedure tested 05NOV22 on Laptop17, a Dell Latitude running W10
 1. Fit correctly on the IO board
 2. Place a jumper on J2 to disable eMMC boot
 3. Fit a micro-USB cable to J11
 4. Download and run the [Windows Installer](https://github.com/raspberrypi/usbboot/raw/master/win32/rpiboot_setup.exe) to install the drivers and boot tool.
 5. Restart Laptop17
 6. Connect the micro-USB to Laptop17 and power up the IO Board, Laptop17 should now find the hardware and install the driver.
 7. Windows will offer to format a disk, use defaults.
 8. Download and run the [RPi Imager](https://www.raspberrypi.com/software/) to install the OS. The RPI showed as RPi-MSD-0001.
 9. Power down and remove the micro-USB.
 10. Remove the jumper on J2 to enable eMMC boot.
 11. Power up, you are good to go.
  
