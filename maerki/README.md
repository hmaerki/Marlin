# Motherboard for Ender 3

https://www.creality3dofficial.com/de/products/creality-silent-mainboard-v4-2-7?variant=31830634496073

https://www.aliexpress.com/item/1005001708452825.html

US $29.05, Newest CRELAITY 3D Upgrade 32 Bits Silent Mainboard For Ender-3/Ender-3Pro/ Ender-5 Printer

# Prepare

cp  ~/versuche_marlin/Configurations/config/examples/Creality/Ender-3/CrealityV427/* ~/versuche_marlin/Marlin/Marlin/

* VSCode
* Extension: PlatformIO IDE
* Extension: Auto Build Marlin

# Flash

Build "PROJECT TASKS": STM32F103RET6_creality_maple

Version: firmware-20210620-Maerki-B.bin Maerki-B
  * MESH_BED_LEVELING
  * LCD_BED_LEVELING
  * RESTORE_LEVELING_AFTER_G28

Version: firmware-20210703-Maerki-C.bin Maerki-C
  * FILAMENT_RUNOUT_SENSOR (ADVANCED_PAUSE_FEATURE, NOZZLE_PARK_FEATURE)

Version: firmware-20210717-220133.bin Maerki-D
  * Enable BLTouch
  * https://youtu.be/NTwEaVxEe1s
  * https://crosslink.io/2021/04/26/ender-3-v2-bltouch-upgrade-creality-4-2-2-or-4-2-7-mainboard/
  * disable LCD_BED_LEVELING
  * BLTOUCH (Z_SAFE_HOMING)
  * firmware-20210717-Maerki-D.bin
