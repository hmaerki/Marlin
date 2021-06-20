# Motherboard for Ender 3

https://www.creality3dofficial.com/de/products/creality-silent-mainboard-v4-2-7?variant=31830634496073

https://www.aliexpress.com/item/1005001708452825.html

US $29.05, Newest CRELAITY 3D Upgrade 32 Bits Silent Mainboard For Ender-3/Ender-3Pro/ Ender-5 Printer

# Prepare

cp  ~/versuche_marlin/Configurations/config/examples/Creality/Ender-3/CrealityV427/* ~/versuche_marlin/Marlin/Marlin/

* VSCode
* Extension: PlatformIO IDE
* Extension: Auto Build Marlin

Enable MESH_BED_LEVELING

# Flash

Build "PROJECT TASKS": STM32F103RET6_creality_maple

Version: firmware-20210620-Maerki-A.bin Maerki-A
  MESH_BED_LEVELING
  LCD_BED_LEVELING
  RESTORE_LEVELING_AFTER_G28
