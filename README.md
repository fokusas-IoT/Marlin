# Marlin 2.0.x 3D Printer Firmware for Anet AM8 with SKR V1.3, TMC2130, TFT3.5

Hardware: 

- Anet AM8 printer
- BIGTREETECH SKR V1.3 32-Bit mainboard
- TMC2130 stepper drivers
- BIGTREETECH TFT35 V3.0 display

## Configuration adaptation

```diff
- Currently firmware not finished and not working.
```

Branches:

- 2.0.x-SKR_V1.3 //made copy from 2.0.x branch and added configuration changes for SKR V1.3
- bugfix-2.0.x-SKR_V1.3 //another copy but this time from bugfix-2.0.x branch and added configuration changes for SKR V1.3
- bugfix-2.0.x //Marlin 2.0 with bug fixes ("Nightly")
- 2.0.x //Latest release
- dev-2.1.x //Marlin 2.1 development ("Nightly")
- 1.1.x //Previous release
- 1.0.x //Older release
- bugfix-1.1.x //1.1.x "bugfix" snapshot ("Nightly")
- Marlin_RTOS // Marlin 2.1 Bugfix on Real-time operating system


Changed files: 

- platformio.ini
- Marlin/Configuration.h
- Marlin/Configuration_adv.h

## Links to usefull information on other sites

Good info how to migrate from Anet 1.5 board to SKR V1.3 https://caggius.wordpress.com/anet-a8-skr-v1-3-and-marlin-2-0-x/

Another good instruction how to setup SKR V1.3 board for printer (but this for creality ender-3): https://medium.com/@damien.martin.guillerez/skr-1-3-tmc2130-on-a-creality-ender-3-b4ec4abfdfd1

Bigtreetech github page: https://github.com/bigtreetech/BIGTREETECH-SKR-V1.3/tree/master/BTT%20SKR%20V1.3

Bigtreetech instruction manual: https://github.com/bigtreetech/BIGTREETECH-SKR-V1.3/blob/master/BTT%20SKR%20V1.3/SKR%20V1.3-Instructions.pdf

Bigtreetech video how to install SKR V1.3 https://www.youtube.com/watch?v=oaXfXkPYHpw&t=8s
