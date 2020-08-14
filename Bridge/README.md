# Bridge
The bridge functions as a, you guessed it, bridge between the wireless sensor module and the MQTT broker. Hence, it needs to have a 433Mhz receiver and be able to connect to an MQTT Broker. That's exactly what's happening here. 

## How to use
There is literally an infinite amount of ways this bridge can be used; some of the possibilities will be given below.

One can flash this code on an ESP-01, connect a SRX882 and just put it somewhere. However, when you already have an ESP8266 running somewhere, you could easily just copy this code with additional benefit a very easy to use MQTT client.