#up/laserOS/hardware lasercube_esp32
[😊#up/laserOS/hardware lasercube_esp32](https://47.111.95.20:6001/user/1/start/%23up%2FlaserOS%2Fhardware%20lasercube_esp32)


## [[2022-06-19]]

[[lasercube 7.5w mainboard issue]]

### [[2022-06-02]]

SSC53L


[[2022-05-20]]
- [ ] [LaserDOCK Hardware: Burn in test program for esp32 wifi cube](https://basecamp.com/1763987/projects/2265763/messages/93663156#comment_858405484)
	- [ ] new firmware v0.6



[[lasercube_esp32 secure boot verification failed]]

```bash
source ../../../../esp_expressive_sdk_tools_wificube_020920/esp/esp-idf/export.sh


cd /home/pilypala/__work/2020_05_20_esp32/laserdock-esp32_wifi.git/WifiLaserCube && source ../../esp_expressive_sdk_tools_wificube_020920/esp/esp-idf/export.sh
idf.py monitor -p /dev/ttyUSB1
idf.py monitor -p /dev/ttyUSB3

cd /home/pilypala/__work/__wl/2019_04_19_laserdock_factory/laserdock_factory_utilities.git/esp32wificube 
./2
```

```bash
cd /home/pilypala/__work/__wl/2019_04_19_laserdock_factory/laserdock_factory_utilities.git/esp32wificube
```

### List of DC power points
- GND TP1
- +3.3V TP3
	- supply to XO1 50Mhz crystal
	- pull-up to MTDO
	- supply to network chip LAN8720AI U6
	- pull-up to MDIO
	- pull-up to PRG network
	- pull-up to PHYAD0
	- supply to U9 crypto chip ATSHA204A-STUCZ-T
	- supply to U11 MCP9701AT-E/TT temperature chip
	- supply to U4 CN809S delay chip
	- supply to MOD1 WROOM32UE
- 6V TP5
	- to suppler output TLV274C op-amp U3
	- to supply U13 the interlock chip
	- U14 PUSB2X4D
	- to supply fan power
	- used to be inverted to supply -6V
- -6V TP4
		- to suppler -6V to output TLV274C op-amp U3
- 5V TP6 
	- reference to supply reference votlage to output TLV274C X/Y U3


### Interlock Circuitry

- p3.2 and p3.3 are input pins for START and STOP
- p3.1 and p3.0 are progrmaming pins
	- p3.1 is used to communciate with esp32 module too
- p3.5 is output pin that enables DEN
- p3.4 drives LEDs

![[esp32 interlock circuitry.png]]

![[esp32 interlock circuitry p3.1.png]]