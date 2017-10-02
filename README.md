Running an MQTT broker to serve all devices for a house ( 20pcs) is required at least a Raspberry Pi or equivalent.
SD card fails from time to time, and requires some Linux skills to make it work and the final price is over USD 70. (Good power supply, case, HDMI cable, keyboard )

But how about running an MQTT broker on an USD 3 ESP8266 chip ? It is possible ? Yes, it is ! Go to http://iotcentral.eu and with few clicks you will be able to flash your ESP8266 ( 4Mb) with the binary. 

No need to compile code, to solve errors , just click and run. More than that your MQTT broker will communicate with your http://iotcentral.eu instance so you still get your messages on your phone if your mobile app is connecting to the websockets to your http://iotcentral.eu cloud instance. 

But what I am at home and my internet connection is down ? Can I communicate with my devices or I am isolated?  Don't worry, your mobile app will still be able to connect to the ESP8266 MQTT Broker over the websocket so you can control your devices.
