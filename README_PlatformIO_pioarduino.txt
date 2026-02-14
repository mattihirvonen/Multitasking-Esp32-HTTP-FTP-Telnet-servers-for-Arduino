
Arduino IDE/CLI and Pioarduino builds
=====================================

Project is modified to be "dual mode" application. This project can build
without source code modifications using:
- Arduino IDE
- Arduino CLI
- Visual Studio Code blugin "pioarduino" (which is fork of PlatformIO blugin)

Pioarduino is quite new fork of VScode's PlatformIO blugin.
PlatformIO blugin support officially only old out of date API 2.x libraries (of ESP processors).
Pioarduino blugin support up to date Arduino libraries.
- https://github.com/pioarduino/platform-espressif32
- https://github.com/sivar2311/platform-espressif32-versions/blob/main/README.md

NOTE(s):
-  Linux is case sensitive with file names and paths ! (some things fixed in original source files)
- "pioarduino" and Arduino IDE/CLI tested to build OK in Linux (Ubuntu 22.04) virtual machine

Following Arduino CLI build information is used as reference to modify project
compatible build with Arduino IDE/CLI and Visual Studio Code blugin "pioarduino".


Used library Version Path
WiFi         3.3.5   C:\Users\mattihirvonen\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.3.5\libraries\WiFi
Networking   3.3.5   C:\Users\mattihirvonen\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.3.5\libraries\Network
FS           3.3.5   C:\Users\mattihirvonen\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.3.5\libraries\FS
LittleFS     3.3.5   C:\Users\mattihirvonen\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.3.5\libraries\LittleFS
ESPmDNS      3.3.5   C:\Users\mattihirvonen\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.3.5\libraries\ESPmDNS

Used platform Version Path
esp32:esp32  3.3.5   C:\Users\mattihirvonen\AppData\Local\Arduino15\packages\esp32\hardware\esp32\3.3.5

