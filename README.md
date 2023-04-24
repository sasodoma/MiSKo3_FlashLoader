# MiSKo3 FlashLoader
An external QSPI loader project for flashing files onto the external flash memory of the MiSKo3 using STM32CubeProgrammer.
Designed for the Winbond W25Q128JV.

## Installation and usage
Copy the `MiSKo3_FlashLoader.stldr` file to `<Install directory>\STM32CubeProgrammer\bin\ExternalLoader`.
In the STM32CubeProgrammer **EL** tab select the `W25Q128JV_MiSKo3` loader.
External flash data is now availabe at address 0x90000000.

## Compiling
After building the project, you need to rename `MiSKo3_FlashLoader.elf` to `MiSKo3_FlashLoader.stldr`

Made using the following tutorial:
https://www.youtube.com/playlist?list=PLnMKNibPkDnHIrq5BICcFhLsmJFI_ytvE
