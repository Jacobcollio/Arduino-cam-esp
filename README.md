# Arduino-cam-esp

With an ESP8266 board, WiFiEsp library allows an Arduino board to connect to the internet.
It can serve as either a server accepting incoming connections or a client making outgoing ones.
The WiFi Esp library is very similar to the Arduino [WiFi](https://www.arduino.cc/en/Reference/WiFi) and Ethernet libraries, and many of the function calls are the same.

Supports ESP SDK version 1.1.1 and above (AT version 0.25 and above).

# Features
APIs compatible with standard Arduino WiFi library.
Use AT commands of standard ESP firmware (no need to flash a custom firmware).
Support hardware and software serial ports.
Configurable tracing level.

# Wiring
The WiFiEsp library has been designed to work with the [ESP WiFi shield](https://www.espruino.com/arduino-esp8266). It is a cheap version of the Arduino WiFi shield that uses an ESP-01 module to provide networking capabilities to Arduino boards.

# Examples


[WebClient](https://github.com/Jacobcollio/Arduino-cam-esp/tree/main/ESP8266WiFi/examples/WiFiClient) - Connect to a remote webserver

[WebServer](https://github.com/Jacobcollio/Arduino-cam-esp/tree/main/ESP8266-wifi%20connected-webserver/examples/AdvancedWebServer) - Serve a webpage from the WiFi shield

[WebServerAP](https://github.com/Jacobcollio/Arduino-cam-esp/tree/main/ESP8266WiFi/examples/WiFiAccessPoint) - Serve a webpage from the WiFi shield starting a local Access Point




# Supported APIs
Most of the standard Arduino WiFi library methods are available. Refer to the [WiFi library page](https://www.arduino.cc/en/Reference/WiFi) for more details.

# ESP8266 12-E NodeMCU Kit

The ESP8266 12-E NodeMCU kit pinout diagram is shown below.

![initial](https://user-images.githubusercontent.com/70785525/99380401-3f679a00-290d-11eb-813d-d1c7c532957f.png)



