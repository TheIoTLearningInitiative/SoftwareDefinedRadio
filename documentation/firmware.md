# Firmware

> HackRF devices ship with firmware on the SPI flash memory and with a bitstream programmed onto the CPLD. The firmware can be updated with nothing more than a USB cable and host computer. [Homepage](https://github.com/mossmann/hackrf/wiki/Updating-Firmware)

- Updating the SPI Flash Firmware
- Updating the CPLD

Latest Release

- [Github Hackrf](https://github.com/mossmann/hackrf/releases/latest)

```sh
user@workstation:~/hackrf-2015.07.2/firmware-bin$ ls
hackrf_cpld_default.xsvf       hackrf_jawbreaker_usb_rom_to_ram.bin  hackrf_one_usb_rom_to_ram.bin
hackrf_jawbreaker_usb_ram.dfu  hackrf_one_usb_ram.dfu
user@workstation:~/hackrf-2015.07.2/firmware-bin$ hackrf_spiflash -w hackrf_one_usb_rom_to_ram.bin 
File size 20452 bytes.
Erasing SPI flash.
Writing 20452 bytes at 0x000000.
```

```sh
user@workstation:~/hackrf-2015.07.2/firmware-bin$ hackrf_info 
Found HackRF board 0:
Board ID Number: 2 (HackRF One)
Firmware Version: 2014.08.1
Part ID Number: 0xa000cb3c 0x006d4749
Serial Number: 0x00000000 0x00000000 0x321864c8 0x3952811d
pymelab@workstation:~/hackrf-2015.07.2/firmware-bin$ 
```

Reset

```sh
pymelab@workstation:~/hackrf-2015.07.2/firmware-bin$ hackrf_info 
Found HackRF board 0:
USB descriptor string: 0000000000000000321864c83952811d
Board ID Number: 2 (HackRF One)
Firmware Version: 2015.07.2
Part ID Number: 0xa000cb3c 0x006d4749
Serial Number: 0x00000000 0x00000000 0x321864c8 0x3952811d
pymelab@workstation:~/hackrf-2015.07.2/firmware-bin$ 
```

```sh
pymelab@workstation:~/hackrf-2015.07.2/firmware-bin$ hackrf_cpldjtag -x hackrf_cpld_default.xsvf 
File size 37629 bytes.
LED1/2/3 blinking means CPLD program success.
LED3/RED steady means error.
Wait message 'Write finished' or in case of LED3/RED steady, Power OFF/Disconnect the HackRF.
Write finished.
Please Power OFF/Disconnect the HackRF.
pymelab@workstation:~/hackrf-2015.07.2/firmware-bin$ 
```

```sh
