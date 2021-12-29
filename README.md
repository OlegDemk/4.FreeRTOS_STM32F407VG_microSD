# 4.FreeRTOS_STM32F407VG_microSD

Start_SD_CARD task works with micro SD flash dick. Module (micro SD holder) connected to STM32 ower SPI. 

Orange LED blink (PD13) when data is in writing procces. 

If there are a problems with f_mount functions (SD card can't be mount), SD card must be format from Windows in FAT32.

Also project can reading data from sensors (see on picture) Start_bme280 and Start_AM2302 tasks. 

Also RTC added in function: Start_Blue_LED_Blink. Made changes in hardware part: Removed R26, connect to VBAT (pin 6) 3.3V battery, and LF cristal and capacitors.

![alt text](https://github.com/OlegDemk/4.FreeRTOS_STM32F407VG_microSD/blob/main/schem.png)

![alt text](https://github.com/OlegDemk/4.FreeRTOS_STM32F407VG_microSD/blob/main/SD.jpg)

Wrote test data (i variable) looks like:
![alt text](https://github.com/OlegDemk/4.FreeRTOS_STM32F407VG_microSD/blob/main/log_data_screen.png)

sourse: https://www.youtube.com/watch?v=acXPelSv2B4
