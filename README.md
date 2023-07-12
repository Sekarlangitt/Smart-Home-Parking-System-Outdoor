# Smart-Home-Parking-System-Outdoor
This is an IoT project.

# Component
a. 4 LED lamp
    ● 2 yellow
    ● 1 green
    ● 1 red
b. NodeMcu amica cp2102 esp8266
c. Photoresistor / LDR
d. Servo
e. Ultrasonic sensor type HC-SR04
f. DHT11 temperature sensor

# Features
There are 3 on/off switch buttons and value labels in the Blynk 2.0 application:
a. LED button to turn off led = virtualPin v0
b. Gate button to drive servo = virtualPin v1
c. Auto button = virtualPin v2
d. Temperature value = virtualPin v3
e. Humidity value = virtualPin v4
![image](https://github.com/Sekarlangitt/Smart-Home-Parking-System-Outdoor/assets/134146217/67d580b0-c0f0-4477-b2d2-d3da89cba16b)
![image](https://github.com/Sekarlangitt/Smart-Home-Parking-System-Outdoor/assets/134146217/aa3e9837-0051-4daf-aeea-4cf1f97b656c)

# Process
a. Temperature value and humidity value will always display temperature
information and Humidity.
b. When the auto button on, 2 yellow leds will turn on when the light is dark and
turn off when bright light and also the servo will rotate 45 degrees (red led off and
green led on) when the ultrasonic sensor detects an object from a distance of
10cm, if the object is more than 10cm, the servo will return to its original position
0 degrees (green led off and red led on).
c. When the lamp button is on, 2 yellow leds will light up, when the lamp button is
off the led is off.
d. When the gate button is on, the servo will rotate 45 degrees (red led off and green
led on). When the gate button is off, the servo will return to its original position of
0 degrees (green led off and red led on).

# Circuit Diagram
![image](https://github.com/Sekarlangitt/Smart-Home-Parking-System-Outdoor/assets/134146217/72478aba-4d59-4c32-b9e9-f5935765d34a)
![image](https://github.com/Sekarlangitt/Smart-Home-Parking-System-Outdoor/assets/134146217/46e2c936-c7e3-4af9-88c6-98e1d5dd5241)

# Result
![image](https://github.com/Sekarlangitt/Smart-Home-Parking-System-Outdoor/assets/134146217/fac2608a-a463-4fc3-a44e-9cb613045a97)
![image](https://github.com/Sekarlangitt/Smart-Home-Parking-System-Outdoor/assets/134146217/b1753dfd-4840-4f01-b6b8-ea1cc8e5f930)
![image](https://github.com/Sekarlangitt/Smart-Home-Parking-System-Outdoor/assets/134146217/1404f634-fde4-48b7-867f-9f9e712c54b5)
![image](https://github.com/Sekarlangitt/Smart-Home-Parking-System-Outdoor/assets/134146217/50c3ddf4-fa06-4ee3-9394-8e9157143188)
