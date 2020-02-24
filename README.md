# OTA-programming-Arduino-Pro-Mini-using-ESP8266

The ESP8266 downloads the OTA for the Arduino Pro Mini from a URL on an http server, then powercycles the Pro Mini pulsing PC6/RESET, during which it also drives the Mini's DTR low. After RESET goes high, DTR also goes high. The ESP8266's TX and RX are connected to the Pro Mini's RX & TX and it uses these transfer the new firmware to the Pro Mini, after which the Pro Mini is rebooted by pulsing PC6/RESET again.

This is a placeholder for a subproject. If there's enough interest, I can clean it up and post it.

