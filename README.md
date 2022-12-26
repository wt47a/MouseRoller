# MouseRoller
This is simple mouse emulator to scroll down and up mouse wheel. It runs on STM32 Minimum Development Board connected to desktop USB port.
It is usefull to simulate user behavior disabling desktop to lock or go to standby mode.

## Usage
Once device prepared with procedure described as below can be easily pluged -in and -out to desktop USB port.
## Build and Deploy
MouseRoller requires special software and hardware to prepare working end user device.
### Software and hardware requirements
* STM32 Minimum Development Board - it is cheap hardware dedicated to user. It can be bought be 1-2$ on eBay or aliexpress
* ST-LINK programmator - used to program device
* STM32CubeIDE - software on you desktop to build and program flash
* STM32CUbeMX (optional) - software to  
### Desktop preparation
It does not require special software preparation. Just download and install STM32CubeIDE software from https://www.st.com/en/development-tools/stm32cubeide.html 
Install software together with STLINK drivers.
Additionally you need git client no your desktop to get this software from GitHub repository. You can use separated or eclipse built in git client.
### Get software
Just clone software from git repository to you desktop and open project in STM32CubeIDE
### Building
Before building connect you board to ST-LINK. Once done first build by: from menu select: "Project" -> "Build"
### Deploying
From IDE menu select: "Run" -> "Run" and create new configuration. After this you device is ready to use.
With ready device plugin to use port.