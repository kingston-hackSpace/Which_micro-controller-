# WORK IN PROGRESS

# Arduino PRO MICRO 5V (Sparkfun)

Arduino PRO MICRO is an Arduino-compatible board much smaller than an Arduino Uno. 

Read more [here](https://learn.sparkfun.com/tutorials/pro-micro--fio-v3-hookup-guide/all)

----
## Wiring
See wiring diagram [here](https://github.com/kingston-hackSpace/Micro-controllers/blob/main/ProMicro-pins.png)

SDA → pin 2

SCL → pin 3

---
## Set Up: Windows and Mac/Linux

To use the Pro Micro with your computer, you need to install a driver so the computer can communicate with the board over USB.

Follow the intallation instructions for:

- [Windows](https://learn.sparkfun.com/tutorials/pro-micro--fio-v3-hookup-guide/installing-windows)

- Mac/Linux (detailed instructions [here](https://learn.sparkfun.com/tutorials/pro-micro--fio-v3-hookup-guide/installing-mac--linux)):
  
    - Open the Arduino IDE in your computer
 
    - Go to File > Preferences
 
    - Then, towards the bottom of the window, paste the following URL into the "Additional Board Manager URLs" text box: https://raw.githubusercontent.com/sparkfun/Arduino_Boards/main/IDE_Board_Manager/package_sparkfun_index.json
 
*** AFTER THESE STEPS, COULDNT MAKE THE MICRO WORK. 

    - Click OK. Then open the Board Manager by clicking Tools, then hovering over the Board selection tab and clicking Board Manager.

    - Search for "SparkFun AVR Boards". Install.
    
    
