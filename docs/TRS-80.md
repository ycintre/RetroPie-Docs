***
![trs-80](https://cloud.githubusercontent.com/assets/10035308/15901462/a43326d2-2d60-11e6-9607-ee959ea30b40.png)
***
_The TRS-80 was a home computer originally released by the Tandy Corporation in 1977. T=Tandy RS=Radio Shack 80=Z-80 microprocessor._
*** 

| Emulator | Rom Folder | trs-80 type | Extension | BIOS |  Controller Config |
| :---: | :---: | :---: | :---: | :---: | :---: |
| [sdltrs](https://github.com/RetroPie/sdltrs) | trs-80 | trs-80 model I  | .dsk | level2.rom | hardcoded |
| [sdltrs](https://github.com/RetroPie/sdltrs) | trs-80 | trs-80 model III  | .dsk | level3.rom | hardcoded |
| [sdltrs](https://github.com/RetroPie/sdltrs) | trs-80 | trs-80 model 4  | .dsk | level4.rom | hardcoded |
| [sdltrs](https://github.com/RetroPie/sdltrs) | trs-80 | trs-80 model 4P  | .dsk | level4P.rom | hardcoded |


## Emulator: [sdltrs](https://github.com/RetroPie/sdltrs)

## ROMS
Accepted File Extensions: **.dsk**

Place your TRS-80 ROMs in
```
/home/pi/RetroPie/roms/trs-80
```

## BIOS

The BIOS file needed is **level2.rom** for Model I, **level3.rom** for Model III, **level4.rom** for Model 4 and **level4p.rom** for Model 4P. An overview of the options for legally obtaining one of the various compatible BIOS files can be found [in the sdltrs README file](https://github.com/RetroPie/sdltrs).

Place your level2.rom BIOS file in
```
/home/pi/RetroPie/BIOS
```

## Controls:

- F7: Emulator Options
- F10: Reset Emulator
- F12: System Menu (Quit)

### Advanced Configuration

For more detailed information on autolaunching disks and games see this guide [HERE](https://github.com/RetroPie/RetroPie-Setup/files/114630/sdltrs.configuration.pdf)