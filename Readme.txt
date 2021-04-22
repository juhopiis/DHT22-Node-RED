Temperature and humidity meter with automatic fan control.
If temperature rises above 25 degrees celcius or humidity rises above 45%, the fan connected turns on.

Parts needed:
1. Raspberry Pi
2. 5V fan
3. PN2222A transistor
4. DHT22 module
5. Cables for connections

Install Node-red node for node-dht-sensor: npm install node-red-contrib-dht-sensor
Import EmbeddedFinal.json to Node-RED

Connect DHT22 to 3.3V, Ground and GPIO4 (pins 1, 6, 7 on Raspberry Pi)

Connect fan power to 5V (pin 2 on Raspberry Pi)
Connect fan ground to the collector pin of the transistor
Connect the base pin of the transistor to GPIO27 and GPIO22 (pins 13, 15 on Raspberry Pi)
Connect the emitter pin of the transistor to Ground (pin 39 on Raspberry Pi)

Enjoy
