# Project Info
This Project to test how to build STM32 (or other arm platform mcu) code in the Eclipse software under Windows platform.

## Procedure
1. Install GNU MCU Eclipse extension from the Eclipse Marketplace.
	- install this extension will give you a environment for convinient building arm's codes.
	- It will guide you how to build, and provide you necessary building informations.

2. Install GCC and 'make' command
	- Install 'MinGW' software.
	- Install all the basic required compiling tools listed in the 'basic' list of 'MinGW'.
	- Add the compiling files' directory to the system's environment variable 'PATH'.
	- Change the file 'mingw32-make.exe' to 'make.exe'
	
3. Install 'arm-none-eabi-gcc' command
	- Download this building tool from ARM website: https://developer.arm.com/open-source/gnu-toolchain/gnu-rm/downloads
	- Add the compiling files' directory to the system's environment variable 'PATH'.
	
4. Create a C/C++ project in eclipse
	- Select STMxx as your running platform.
	
5. Build the project
	- If everything go well, the console will output message 'Finished building: xxx.siz'.
	- The '.elf' and '.hex' files will exist in the subfolder '/Debug' of your project directory.