# Ender 3 Max with BigTreeTech SKR MINI E3 v3.0 and TFT35

Firmware for BTT SKR-E3 v3.0 with TFT35 on Ender 3 Max
 

## Hardware 
    - Ender 3 Max (300x300x340)
    - CRTouch / BLTouch
    - Filament Sensor
    - Creality Spider Hotend (optional but hotend max_temp is set to 300)
    - BTT SKR MINI 3 v3.0 (STM32G0B1 RET6 may work with other)
    - BTT TFT 35

## Enabled Firmware Functions
    - Marlin Version : bugfix-2.0.x
    - TH set to max 300
    - CRTouch / BLTouch - Bed Leveling functions Enabled
    - Filament Sensor Enabled
    - Bed Tramming Enabled
    - Bed set at 300x300x340


## Installation
    - Copy firmware.bin to your SD Card root and rename it to all caps (FIRMWARE.bin) otherwise btt board will ignore the install.
    - Insert SD card (3d printer sd card slot) then turn your 3d printer on.
    - Wait several seconds to update your firmware. 
    - Remove SD Card
    - From MENU -> SETTINGS -> MACHINE -> EEPROM, do a reset.
    - Restart Machine.


## SET PROBE OFFSET VIA THE TFT UI

    MENU -> SETTINGS -> MACHINE -> SETTINGS -> PROBE OFFSET
    

## SET PROBE OFFSET VIA THE MARLIN UI

    CONFIGURATION -> ADVANCE SETTINGS -> PROBE OFFSET

Stock Mount is set at X = 45; Y=-18.5; Z = 1.52

---
> WARNING: This is my setup, intended for personal reference. Use at your own risk.

