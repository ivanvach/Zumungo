# Zumungo
ESP8266 or ESP32 IoT solutions for relays, sensors, keypads, steeper motors
Zumungo software ( zumungo.com ) was created and field tested by Home Automation enthusiasts to add advanced features to ESP8266 or ESP32 based boards.
Zumungo's vision is to "bring the intelligence to the edge of the network".
Zumungo covers three major application areas for now and more are on its way.

1. Zumungo Relays adds sophistication to the relay management 

- Own web page for settings, controls and reports
- Normal mode - open/close by command
- Timing - open and close after certain time
- Overlay mode - like the two above however overruled by the status of an input
- Schedule mode - by day, hour, minutes, sunset +- offset, sunrise +- offset up to 3 schedules per relay 
- Trigger by input mode
- Mono mode - with 3 variants normal, recurruing and kill.
- 1wire temp sensor - 
- trigger by temperature +- hysteresis (all adjustable)
- Control and report by HTTP, MQTT or TCP (well documented commands and responses)
- Responds to "CallAll" command over UDP - to find out all boards on the network and their IP addresses
- JSON API
- OTA updates
- Supports geo location lat and lon coordinates.			
- Easy to integrate into third party systems			
- Well documented in English			
- Designed in the USA

2. Zumungo Matrix is named for the fact that it manages matrix keypads well, however it handles stand alone buttons as well as variety of sensors such as motion sensors, flood sensors, security sensors and any sensor that will provide binary on/off signal.

- manages matrix keypad 4x4 or 4x3
- Recognize and report a key press			
- Recognize and report combo press of 2 keys			
- Memorize up to 100 passwords			
- Passwords for principals and staff members with different powers			
- Staff passwords can be valid only during certain days and hours			
- TCP protocol for reports			
- Recognize and report “power button” presses. Power buttons are the ones pressed after successful password authentication.			
- Reports each successful and unsuccessful transaction.			
- Blocks operations for certain time (programmable) after 3 unsuccessful attempts to enter a password.			
- Intuitive (by timing) password entry recognition doesn't need entering special symbols as password delimiters.			
- Supports battery powered boards, monitors the battery and reports low battery condition.			
- Red/green LED lights provide a feedback to user.			
- Own web page for settings, passwords and reports			
- Can control up to three digital outputs upon successful entry of a password (for door/gate opening for example or for panic alarm for three unsuccessful attempts to enter a password).			
- Triggers optional panic alarm output after 3 unsuccessful password entry attempts			
- Easy discovery on the network. Responds to UDP protocol "CallAll" command with essential information about itself.
- OTA updates
- Supports geo location lat and lon coordinates.			
- Easy to integrate into third party systems			
- Well documented in English			
- Designed in the USA

3. Zumuingo Stepper motors control. While controlling stepper motors is relatively easy and free libraries exist for that Zumungo adds significant sophistication by allowing memorization of up to 100 positions and commands from moving from one position to another.

- Start/stop			
- Set direction			
- Set speed			
- Set destination by number of steps
- Set destination by time to run
- Memorize up to 100 positions			
- Copy any current position to memory			
- Move from any position to any other position from memory			
- Report current direction, speed and position			
- JSON API control and reports over TCP			
- UDP protocol for reports			
- Recognize and report errors			
- Security – password protected controls			
- Control up to 4 motors with one board			
- Power saving mode by using the Enable input of the motor driver			
- OTA (over the air) updates			
- Call ALL feature to locate multiple boards or recover forgotten IP address of the board			
- Well documented in English			
- Designed in the USA

PRE-REQUISITES

1. Your own ESP8266 or ESP32 based board.
2. For the Relays the board should be equipped with relays or use external "dumb" relay board in addition to your ESP board
3. For Matrix/sensors - have Matrix keypad and/or sensors that produce on/off signal. 
4. For stepper motor - setpper motor power control unit and stepper motor
5. Arduino IDE software to compile and flash
6. USB to serial adapter if your board doesn't have one built-in (most ESP8266 boards don't while most ESP32 boards do have it)

DOWNLOADING INSTRUCTIONS

1. Change the 3 lines in the Installer's source code per the embedded instructions.
2. Compile and flash the Installer in your Esp8266 or ESp32 board.
3. Restart the board and wait 1 minute for the board to download the software OTA.
4. Look for WiFi network named Zumungo XXXXXXX where  6 letter XXXXXXX is your unique board ID.
5. Go to zumungo.com "buy" section and purchase the product. 
FREE 15 days TRIAL IS AVAILABLE NO CREDIT CARD IS REQUIRED
6. In your router find the IP address of a device with MAC address ending with the 6 characters that are your board ID (see above).
7. Go to the IP address to setup your board and start using it immediately. 

