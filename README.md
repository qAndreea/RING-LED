# RING-LED ESP32

Project created personally by me in a college course.
I have created a project to control a ring of NeoPixel LEDs using an ESP32. The project includes a web interface for controlling the LEDs, implemented in Python using the nicegui library, and an Arduino code for managing the LEDs on the ESP32.
My project offers the flexibility to be used on both mains and battery power, allowing for integration and use in various applications and usage scenarios.

First things first, I have divided my objective into smaller tasks : 

- Researching about the hardware and the software I was going to use
- Getting the hardware parts and wiring them up on a bread board
- Creating a Web Server and connecting to the ESP32
- Creating the Web Application and uploaded on the Web Server

  ###HARWARE
- Groundstudio Carbon D4(ESP32)
- NeoPixel LED Ring(12 LEDs)
- Optocoupler (JC817)
- Resistor
- Battery 9 V
- Convertor DC-DC Step-Down
- Holder with wires for 9V battery

  ###SOFTWARE
- I use Arduino IDE to create web server.
- Creating the web application and uploading it to the web server I used the nicegui library in Python to create a web interface that sends HTTP requests to the ESP32.

  ###SCENARIO
- You are responsible for monitoring and operating a machine in an automated production line. You want to implement a simple and effective solution to monitor the machine's health and automatically notify you of any problems encountered.
- Here's what problem management might look like:
 1. Success Button: The machine successfully completes an operation or a production cycle.
 2. Warning button: The machine encounters a situation that requires attention, but it is not a critical error.
 3. Loading Button: The machine is in a loading or processing process.
 4. Stop Button: The machine is stopped manually by the operator.
 5. Error Button: the machine encounters a problem and the ESP32 detects an error, the red LED lights up and the machine is turned off.


 **How to - Step by step**

1. Wiring the hardware components on the breadboard


![449898843_1458099178161479_155526987865273903_n](https://github.com/qAndreea/RING-LED/assets/112701654/54c8406b-2410-44b8-a188-a3a5c1cca29b)

![450149208_3738388726418916_6420324616005557855_n](https://github.com/qAndreea/RING-LED/assets/112701654/581c793f-f71e-42e8-aea3-2695d975f33a)



2. Writing, compiling and uploading the source code

   https://youtu.be/deocbepRT2o

   




   
