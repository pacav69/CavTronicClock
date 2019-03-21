# CavTronicClock

## pins used
Found in common.h

    /* MP3 player GPIO pins */
    #define SERIAL2_RXPIN	16
    #define SERIAL2_TXPIN	17
    #define BUSY_PIN	4
    
    
    /* Buttons & LDR GPIO pins */
    #define BUTTON1 D2
    #define BUTTON2 D3
    #define BUTTON3 D4
    #define LDR A0
    

        /* FireBeetle 24x8 LED hat GPIO pins */
        #if defined( ESP_PLATFORM ) || defined( ARDUINO_ARCH_FIREBEETLE8266 )  //FireBeetle-ESP32 FireBeetle-ESP8266
        #define FBD_DATA D6
        #define FBD_CS D5
        #define FBD_WR D7
        //#define FBD_RD D8
        #else
        #define FBD_DATA 6
        #define FBD_CS 5
        #define FBD_WR 7
        //#define FBD_RD 8
        #endif


## Links to product specifications
[DFPlayer Mini](https://www.dfrobot.com/wiki/index.php/DFPlayer_Mini_SKU:DFR0299)