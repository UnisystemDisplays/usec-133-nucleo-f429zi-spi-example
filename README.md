OVERVIEW
--------

This repository contains example of [*usec-133-generic-spi-lib*](https://github.com/UnisystemDisplays/usec-133-generic-spi-lib) library integration for [*STMicroelectronics NUCLEO-F429ZI*](https://www.st.com/en/evaluation-tools/nucleo-f429zi.html) (*STM32 Nucleo-144* development board with *STM32F429ZI MCU*). Please check [*usec-133-generic-spi-lib*](https://github.com/UnisystemDisplays/usec-133-generic-spi-lib) project repository for more info about library itself.

PREREQUISITES
-------------

To get started, please make sure, that *STM32CubeIDE* (Integrated Development Environment for STM32) is properly installed and configured on your machine - please visit [*STM32CubeIDE webpage*](https://www.st.com/en/development-tools/stm32cubeide.html) for more info.

CONNECTIONS
-----------

|  USEC module connector | STM32 |
| ---- | ----- |
| VBUS | 5V    |
| GND  | GND   |
| SCLK | PA5   |
| MISO | PA6   |
| MOSI | PA7   |
| CS   | PD14  |
| RDY  | PD15  |
| RST  | PF12  |

COMPILATION
-----------

[1] Clone *usec-133-esp32-spi-example* repository:

`git clone https://github.com/UnisystemDisplays/usec-133-nucleo-f429zi-spi-example.git-`

[3] Start *STM32CubeIDE* and import *usec-133-esp32-spi-example* project by choosing:

`File -> Open Projects from File Systems`

[3] Build the project by running:

`Project -> Build All [Ctrl+B]`

GETTING HELP
------------

Please contact Unisystem support - [*<lukasz.skalski@unisystem.com>*](lukasz.skalski@unisystem.com) or [*<jacek.marcinkowski@unisystem.com>*](jacek.marcinkowski@unisystem.com)

LICENSE
-------

See *LICENSE.txt* file for details.