# Arduino-cam-esp

With an ESP8266 board, WiFiEsp library allows an Arduino board to connect to the internet.
It can serve as either a server accepting incoming connections or a client making outgoing ones.
The WiFiEsp library is very similar to the Arduino WiFi and Ethernet libraries, and many of the function calls are the same.

Supports ESP SDK version 1.1.1 and above (AT version 0.25 and above).

# Features
APIs compatible with standard Arduino WiFi library.
Use AT commands of standard ESP firmware (no need to flash a custom firmware).
Support hardware and software serial ports.
Configurable tracing level.

# Wiring
The WiFiEsp library has been designed to work with the ESP WiFi shield<https://www.espruino.com/arduino-esp8266>. It is a cheap version of the Arduino WiFi shield that uses an ESP-01 module to provide networking capabilities to Arduino boards.

# Examples

ConnectWPA - Demonstrates how to connect to a network that is encrypted with WPA2 Personal

WebClient - Connect to a remote webserver

WebServer - Serve a webpage from the WiFi shield

WebServerAP - Serve a webpage from the WiFi shield starting a local Access Point

WebServerLed - Turn on and off a led from a webpage


# Supported APIs
Most of the standard Arduino WiFi library methods are available. Refer to the WiFi library page for more details.
