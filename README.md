**Fork of Original Code**  
[https://github.com/eliddell1/RollJam](https://github.com/eliddell1/RollJam)

# RollJam
RollJam is an INO script which uses two CC1101 chip and a Teensy to create a MITM type of replay attack against rolling codes. 
It was based on the publications of Samy Kamkar, big up for him (https://samy.pl/defcon2015/, https://www.wired.com/2015/08/hackers-tiny-device-unlocks-cars-opens-garages/). 
The script was written for a Teensy 3.1, but it can be easily converted to any other micro controller.

**Correct Pin Numbers for Teensy 3.2**  
cs_rx = 5  
cs_jam = 6  
gdo0_rx = 2  
gdo0_jam = 3  
mosi = 11  
miso = 12  
clk = 13  

**Good Reference Project, same code but not forked, wiring diagram pins are out of sync with their code.**  
[https://github.com/CR11CS/RollJam-315MHz-433MHz](https://github.com/CR11CS/RollJam-315MHz-433MHz)
