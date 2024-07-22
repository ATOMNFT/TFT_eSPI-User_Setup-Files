# Configuring User_Setup Files
(Before adding these file make a full back of the TFT_eSPI folder) <br>
These files are to be added to your TFT_eSPI library. The images below show the location of the library folder that you will need to move these files to. After moving these files locate and open the User_Setup_Select.h file.

Inside this file locate the display you are using. (Use pic for ref)
To use the display/device of your choice remove the // in front of the entry. Make sure only one display is uncommented at a time and also pay attention to the name to minimize error.

## Screenshots


---

## Custom User_Setup Files for Specific Firmwares and Devices
<p>Custom User_Setup files are essential for ensuring proper functionality of certain firmwares and devices. These files contain crucial information such as GPIO pins, display configurations, and other necessary settings.

Utilizing these files is straightforward, as each is designed with clear and intuitive naming conventions to simplify device configuration.</p>
<br>
<details>
<summary>M5 Minigotchi Configuration</summary>
<p align="left">If you intend to flash the minigotchi firmware to an M5 device, ensure you select one of the following User_Setup files that corresponds with the device available in the firmware:
<br>
User_Setup_m5stickc.h <br>
User_Setup_m5stickcp2.h <br>
User_Setup_m5cardputer.h
</p>
</details>

<details>
<summary>TTGO T-Display (Non branded) Minigotchi Configuration</summary>
<p align="left">If you intend to flash the minigotchi firmware to an generic TTGO T-Display, ensure you select one of the following User_Setup files that corresponds with the device available in the firmware:
<br>
User_Setup_TTGO_NoTouch.h <br>
</p>
</details>