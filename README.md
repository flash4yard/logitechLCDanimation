# Logitech LCD animation tool

This software is designed to be integrated into the [blinkit software](https://github.com/techtek/Blinkit) by [@techtek](https://steemit.com/@techtek). BUT it can be used as a stand alone!
Also you can implement the code into your own project if you want.

## Use it as a standalone

### Prerequisites
* Logitech keyboard with monochrome LCD is connected to your computer
* Logitech Gaming Software is installed and running

### How to handle the code/project
Download the project files and open the project in, for example, Visual Studio. 
There you can copy the code to your own project or modify it.
After the code is ready. Go to the config folder located in: /logitechlcd project files/blinkitlogitechlcd/bin/Debug/
and check if the path to the Logitech Gaming Software is correct.

### Add new animation
* create 12 .bmp pictures (count can be changed in the code) with a resolution of 160x43px
* the bmp have to be numbered (1.bmp, 2.bmp, ...)
* create a new folder in the dir where the .exe is located
* write name of the folder in the logitechaction.txt
* done
