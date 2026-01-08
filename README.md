# open-trailcam
This is the repository for an attempt to create an open source trail camera. 
Since most of the commercial trail cameras use some kind of proprietary or hard to get (as an individual) SoCs, possibly custom cameras, in this project 
We will try to use of the shelf easly accessible components that everyone can buy, solder, flash etc. to create a trail camera. 

## 1st phase 
- STM32 Blue Pill with STM32F103C8T6 chip
- SIM7100 modem

Mission goal : 
- Try to send an SMS to an another phone to verify communication and operation between STM32 and SIM7100 4G modem. 

## 2nd phase 
- STM32 Blue Pill with STM32F103C8T6 chip
- SIM7100 modem
- SDCard
- WebHosting to send the photo to

Mission goal : 
- Try to send a photo stored on the sd card to a server 

## 3rd phase 
- STM32 Blue Pill with STM32F103C8T6 chip
- SIM7100 modem
- SDCard
- WebHosting to send the photo to
- 2MP Arducam SPI Camera https://www.arducam.com/arducam-2mp-spi-camera-b0067-arduino.html

Mission goal : 
- Take a photo every 5 minutes, use the sd card as the buffer and send them to the web server

## 4th phase 
- STM32 Blue Pill with STM32F103C8T6 chip
- SIM7100 modem
- SDCard
- WebHosting to send the photo to
- 2MP Arducam SPI Camera https://www.arducam.com/arducam-2mp-spi-camera-b0067-arduino.html
- mmWave Radar

Mission goal : 
- Take a photo every 5 minutes, use the sd card as the buffer and send them to the web server
- Detect motion, take photo and send it to the web server

## 4th phase 
- STM32 Blue Pill with STM32F103C8T6 chip
- SIM7100 modem
- SDCard
- WebHosting to send the photo to
- 2MP Arducam SPI Camera https://www.arducam.com/arducam-2mp-spi-camera-b0067-arduino.html
- mmWave Radar
- try to find a suitable ir cut motorized filter for the SPI CAMERA
- add a 12V IR Reflector of some kind for the night vision

Mission goal : 
- Try to add night vision to the project
