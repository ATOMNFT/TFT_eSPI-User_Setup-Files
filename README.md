## Custom User_Setup Files for Specific Firmwares and Devices
<p>Custom User_Setup files are essential for ensuring proper functionality of certain firmwares and devices. These files contain crucial information such as GPIO pins, display configurations, and other necessary settings.

Utilizing these files is straightforward, as each is designed with clear and intuitive naming conventions to simplify device configuration.</p>

---

## Screenshots
Coming soon!

---

# Configuring User_Setup Files

--Before proceeding, ensure you create a complete backup of the TFT_eSPI folder--

These files need to be integrated into your TFT_eSPI library. The images below illustrate the precise location within the library folder where these files should be placed. Once relocated, locate and open the User_Setup_Select.h file.

Inside this file, identify the specific display you are using (refer to the provided images for guidance). To activate your preferred display device, uncomment the corresponding entry by removing the "//" preceding it. It is crucial to have only one display configuration uncommented at any given time and to verify the accuracy of the display name to avoid errors.

<br>

<b>Below you'll find instructions for certain projects using certain devices</b>

<details>
<summary>Minigotchi Configurations</summary>
<p align="left">If you intend to flash the minigotchi firmware to an M5 device or a generic ttgo t-display, ensure you select one of the following User_Setup files that corresponds with the device available in the firmware:
<br>
1. (User_Setup_CYD.h) For use with a ESP32-2432S028R also called a CYD 
<br>
2. (User_Setup_CYD2USB.h) For use with a CYD that has microUSB & USB-C 
<br>
3. (User_Setup_m5stickc.h) For use with a M5Stick C Plus 1.1 
<br>
4. (User_Setup_m5stickcp2.h) For use with a M5Stick C Plus 2 
<br>
5. (User_Setup_m5cardputer.h) For use with a M5Cardputer 
<br>
6. (User_Setup_TTGO_NoTouch.h) For use with a generic TTGO T-Display choose this entry in User_Setup_Select.h file.
</p>
</details>
