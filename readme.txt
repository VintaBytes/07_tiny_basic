TOYOSHIKI Tiny Basic for Arduboy - Interpreter

## Description
TOYOSHIKI Tiny Basic is Palo Alto Tiny BASIC(1976) clone.
Interpreter is magic. if you see internal structure, you will become wizard :)


## Installation
Request : Arduino IDE 1.6.x

1. download from github
2. pls edit test.bat(windows) or test.sh(osx) for your computer(must change COM port number)
3. execute test.bat
4. this program need Serial Monitor. i tested Tera Term. it is famous in Japan.
5. after connect, input keyboard.


## Manual(BASIC grammar)
https://en.wikipedia.org/wiki/Tiny_BASIC


## Original
simple source code. thank you!
https://github.com/vintagechips/ttbasic_win


## ToDo
INPUT order.


## Development
compiler        : windows Arduino IDE 1.6.9(avr-gcc) + 1.0.6(make.exe)
image converter : python 2.6 + PIL
etc             : Visual Studio 2015 C#


## License
GPL v2


## History
v1.01 2016/05/29    fix RUN, REM, RND, NEW, PSET, SIZE.
                    fix input bug after RUN.
                    variable and array size s8 -> s16.
                    add sample code. thanks fuopy!

v1.00 2016/05/28    first version


Arduboy 1.0 infomation.

AVR Memory Usage
----------------
Device: atmega32u4

Program:   15414 bytes (47.0% Full)
(.text + .data + .bootloader)

Data:       1809 bytes (70.7% Full)
(.data + .bss + .noinit)
