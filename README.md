# ssh-raspberry-pi-beginners-guide
This is a guide for using SSH to connect to a Raspberry Pi on a local network. 

## Requirmeents:

- Raspberry Pi Imager (free software)

- Raspberry Pi Single-Board Computer

- Micro SD card with at least 32 gigabytes of storage  (and a way to connect it to your personal computer)

## Get Raspberry Pi Imager

1. If you have nto done so already, go to the *[Raspberry Pi website](https://www.raspberrypi.com/software/)* and download the Raspberry Pi imager for your personal computer's operating system (Windows, Mac, Linux).

![host-and-port](images/1-raspberry_pi_imager_download.png)

2. Once it has been installed, look for the Raspberry Pi Imager application and open it to confirm successful instalation.  The application may just be called "Imager" but it should have the Raspberry Pi logo as its icon (a purple/pink image of a raspberry as of December 2024).

![host-and-port](images/2_raspberry_pi_imager_download.png)

## Install the operating system on your Raspberry Pi

1. Insert your MicroSD card into your computer with a USB adapter or full-sized SD card with a slot for Micro SDs.

2. Open the Raspberry Pi Imager app. You should see a indow that looks like this:

![host-and-port](images/3_raspberry_pi_imager_interface.png)

3. Click on "CHOOSE DEVICE" and you should see the following screen:

![host-and-port](images/4_raspberry_pi_imager_choose_device.png)

4. Selet the specific Raspberry Pi on which you would like to install an operating system.

5. Click on "CHOOSE OS" and you should see the following screen:

![host-and-port](images/5_raspberry_pi_imager_choose_os.png)

6. Select the operating system which you would like to install onto your Raspberry Pi device.  If you would like to use an ISO downloaded onto your personal computer, scroll down to where it says "USE CUSTOM" and select the ISO image of your desired image within your file explorer.

![host-and-port](images/6_raspberry_pi_imager_use_custom_os.png)

7. Click on "CHOOSE STORAGE" and you shoudl see the following screen:

![host-and-port](images/7_raspberry_pi_imager_choose_storage.png)

You should see a list of all external storage devices currently conected to your computer (if any are connected).

8. Once you have chosen a device, an OS, and a memory device, click on "NEXT" and you should see the following screen:

![host-and-port](images/8_raspberry_pi_imager_next_button.png)

9. Click on "Edit Settings and you should see the following screen:

![host-and-port](images/9_raspberry_pi_imager_os_customization_1_general.png)

10. Set the hostname, username, password, SSID (the name of the WiFi which you choose when you connect to WiFi), your WiFi password, and locale settings.

**Make sure to remember the hostname, username and password as they will be needed in previous steps!**

11. Click on the "Services" tab at the top of the OS Customization window and you should see the following screen:

![host-and-port](images/10_raspberry_pi_imager_os_customization_2_services.png)

** Make sure that the "ENABLE SSH" and "USE PASSWORD AUTHENTICATION" options are checked.

12. The default settings in the "Options" tab can be left as they are.

![host-and-port](images/11_raspberry_pi_imager_os_customization_3_options.png)

**Make sure that the box marked "EJECT MEDIA WHEN FINISHED" is checked!**

13. Click "Save" and you should return to the following screen:

![host-and-port](images/12_raspberry_pi_imager_os_customization_4.png)

14. Click "YES" and you should see the following screen:

![host-and-port](images/13_raspberry_pi_imager_customization_5.png)

Click "YES".

15. Wait for the process should complete.  It will take a few minutes for the image to be written to the Micro SD card.  Exact time will depend on your operating system and hardware.

16. When the process is complete, Raspberry Pi Imager should let you know that you can safely remove the Micro SD card.

17. Put the Micro SD card into the Micro SD card slot of your Raspberry Pi device.

18. Plug your power source into your Raspberry Pi (or plug it into the wall using the power adapter) and wait a few minutes for the system to start up.

**The Raspberry Pi device should boot the operating system image from the Micro SD card.**

## Using SSH to remotely access your Raspberry Pi.




