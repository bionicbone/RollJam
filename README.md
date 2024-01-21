# RollJam
RollJam is an INO script which uses two CC1101 chip and a Teensy to create a MITM type of replay attack against rolling codes. 
It was based on the publications of Samy Kamkar, big up for him (https://samy.pl/defcon2015/, https://www.wired.com/2015/08/hackers-tiny-device-unlocks-cars-opens-garages/). 
The script was written for a Teensy 3.1, but it can be easily converted to any other micro controller.

**Pin Numbers**
cs_rx = 10  
cs_jam = 20  
gdo0_rx = 2  
gdo0_jam = 3  
mosi = 11  
miso = 12  
clk = 13  
