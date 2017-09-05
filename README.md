This is a simple Door sensor project.

Setup:

1. wemos mini esp8266 device is used in this project
2. Install Atom IDE and Install platfromIO
3. Door sensor magnet unit. DO in the layout is used in this program
4. Connect positve side of door sensor to D0 pin
5. connect negative side to GND

Next 3 things in the code,

configure your wifi AP in the device by modifying (1)ssid, (2)password in the main.cpp

Run mqtt broket in anohter device, PC or raspberrypi and get the server address
Ex. 192.168.1.109 and if user name and password
update (3)mqtt_server in the code main.cpp

build and upload the project to esp8266

Thats all!
