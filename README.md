 ![image](https://github.com/Hardy-PDi/ePaper_PervasiveDisplays/blob/master/iTC_Arduino.jpg)
 
 * The example code is for PDi iTC EPD(1.54"/2.13"/2.66"/2.71"/2.87"/4.2"/7.4"/12") on EXT2 board, it's verified by Arduino M0 Pro.
 *  And it sould be able to run on Arduino IDE supported Board, such as Arduino Due or Arduino Uno(Need a level shifter 5V -> 3V for EXT2 board)
 *  https://github.com/arduino/arduino/wiki/unofficial-list-of-3rd-party-boards-support-urls
 *  ![image](https://github.com/Hardy-PDi/ePaper_PervasiveDisplays/blob/master/arduino_w_EXT2.JPG)
 #  Hardware Connection
 ```bash
 #define SCL_PIN 13   //EXT2 BOARD J5 pin 7
 #define SDA_PIN 12   //EXT2 BOARD J5 pin 15
 #define CS_PIN 11    //EXT2 BOARD J5 pin 19 Master CSB
 #define DC_PIN 10    //EXT2 BOARD J5 pin 9
 #define RESET_PIN 9  //EXT2 BOARD J5 pin 10
 #define BUSY_PIN 8   //EXT2 BOARD J5 pin 8
 #define PNLON_PIN 7  //EXT2 BOARD J5 pin 11
 #define CSS_PIN 6    //EXT2 BOARD J5 pin 2 Slave CSB for 12" only
                      //EXT2 BOARD J5 pin 20 connected to GND
                      //EXT2 BOARD J5 pin 17 connected to GND for 4 wire SPI
                      //EXT2 BOARD J5 pin 1 connected to 3V3 
 ```
 #  Support
 *  For more information about PDi EPD and EXT2 board, please visit 
 *  [PERVASIVE DISPLAYS, INC. (龍亭新技股份有限公司)](http://www.pervasivedisplays.com/)
 *  [EPD Extension Kit Gen 2 (EXT2)](http://www.pervasivedisplays.com/kits/ext2_kit)
 *  [24/7 Service]http://www.pervasivedisplays.com/contact/technical-support
