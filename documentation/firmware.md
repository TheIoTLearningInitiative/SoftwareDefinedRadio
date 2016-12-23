```sh
pymelab@workstation:~/hackrf-2015.07.2/firmware-bin$ ls
hackrf_cpld_default.xsvf       hackrf_jawbreaker_usb_rom_to_ram.bin  hackrf_one_usb_rom_to_ram.bin
hackrf_jawbreaker_usb_ram.dfu  hackrf_one_usb_ram.dfu
pymelab@workstation:~/hackrf-2015.07.2/firmware-bin$ hackrf_spiflash -w hackrf_one_usb_rom_to_ram.bin 
File size 20452 bytes.
Erasing SPI flash.
Writing 20452 bytes at 0x000000.
pymelab@workstation:~/hackrf-2015.07.2/firmware-bin$ hackrf_info 
Found HackRF board 0:
Board ID Number: 2 (HackRF One)
Firmware Version: 2014.08.1
Part ID Number: 0xa000cb3c 0x006d4749
Serial Number: 0x00000000 0x00000000 0x321864c8 0x3952811d
pymelab@workstation:~/hackrf-2015.07.2/firmware-bin$ 
```

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