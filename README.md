# ESP32.Access.Point.Webserver
 using esp32 as a access point, launch webserver

ESP32 Web Server with Access Point
This project showcases creating a web server using an ESP32 microcontroller. The ESP32 acts as both a web server and an access point, allowing users to control LEDs, read temperature and humidity data from a DHT22 sensor, and control a servo motor through a simple web interface.

Features
LED Control: Toggle green and red LEDs on/off.
Sensor Data: Display real-time temperature and humidity readings.
Servo Control: Set the angle of a servo motor.
Setup

Hardware Connections:
DHT22: Data pin to GPIO 4
Green LED: GPIO 32
Red LED: GPIO 33
Servo motor: GPIO 2

Software Configuration:
Install Arduino IDE and required libraries: Adafruit Unified Sensor, DHT, ESP32Servo.
Set Wi-Fi credentials in the code.
Upload the code to the ESP32.

Accessing the Web Server:
Power on the ESP32. It will create its Wi-Fi network with the specified SSID and password.
Connect your device to the ESP32's Wi-Fi network.
Open Serial Monitor to find the ESP32's IP address.
Enter the IP address in a web browser.

Usage
Connect your device to the ESP32's Wi-Fi network.
Access the web interface via the IP address obtained from the Serial Monitor.
Use the web page to control LEDs, view sensor data, and set the servo angle.
