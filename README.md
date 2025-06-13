# mouse-emulator

A bus powered usb device that emulates a mouse by moving the pointer in a circle.
LED will flash every second when there is power seen on the bus but hasn't configured with the device.  LED will stay on and stop flashing when it has successfully communicated with the device and will begin moving the mouse pointer in a circle.

## Schematic
![pic](https://github.com/AryllPetersen/mouse-emulator/blob/main/schematic%20v2.jpg?raw=true)

## Project Details

The Mouse.X folder in the repo is an MPLAB X IDE v6.20 project folder while the src folder contains the actual code for the project along with a usb library from https://github.com/Microchip-MPLAB-Harmony/usb. The code was flashed on a 32bit microcontroller ![PIC32MX270F256B](https://ww1.microchip.com/downloads/aemDocuments/documents/MCU32/ProductDocuments/DataSheets/PIC32MX1XX2XX283644-PIN_Datasheet_DS60001168L.pdf) and was flashed using a ![PICKIT 3](https://www.microchip.com/en-us/development-tool/pg164130). The PICKIT 3 is no longer supported by later version of MPLAB. Version 6.20 is the latest version where it still works.




