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