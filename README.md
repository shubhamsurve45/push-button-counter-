# PUSH BUTTON COUNTER

COMPANY : CODETECH IT SOLUTION

NAME : SHUBHAM DATTATRAY SURVE

INTERN ID : CT08DH2161

DOMAIN : EMBEDDED SYSTEM

DURATION : 8 WEEKS

MENTOR : NEELA SANTOSH KUMAR 

This project was developed on the Tinkercad simulation platform using an Arduino UNO microcontroller. The objective was to build a simple digital counter that increments a value each time a push button is pressed. The count value is displayed either on the Serial Monitor or optionally on a 7-segment display.
The circuit includes an Arduino UNO as the main controller, a push button as the input device, and a 10kΩ resistor used as a pull-down resistor to ensure stable input readings. A breadboard and jumper wires were used to create the physical connections between components. The logic was programmed using Arduino C/C++.
When the button is pressed, the Arduino reads the digital input and increments a counter variable. This updated count is then printed on the Serial Monitor or shown on a 7-segment display. A software debounce method can be implemented to avoid false triggering due to mechanical bounce in the button.
This project has real-world applications such as entry/exit counters, production unit counters in industries, and as a beginner-level digital logic experiment for learning Arduino and embedded systems concepts.

🔩 Components Used:

1. Arduino Uno – Main microcontroller to control the logic
2. Push Button – To give digital input (press)
3. 16x2 LCD Display – To show the count
4. Resistors (10kΩ) – For pull-down or pull-up logic
5. Breadboard & Jumper Wires – For connections
6. USB Cable – For Arduino power and programming

⚙️ Working Principle:

The push button is connected to one of the digital input pins of Arduino.
Every time the button is pressed, Arduino detects the HIGH signal.
A counter variable is increased by 1.
The updated count is shown on the LCD.
It also uses a debounce technique to avoid multiple counts for a single press.

💻 Platform Used:
Tinkercad (Online Simulation Platform)
Alternatively, you can do it using Arduino IDE + real components

📍 Applications:
People counters (door entry counting)
Number of times a machine is used
Score counter in small games
Basic understanding for building input-based systems

🎯 Importance of Project:
Teaches digital input and conditional programming
Demonstrates LCD interfacing with Arduino
Helps in learning debounce logic
Good first project to start real-time embedded development
Can be upgraded to IR based or sensor-based counter

✅ Output:
When the circuit is powered and the code uploaded:
LCD will display:

Count: 0

Every time the push button is pressed, the count increases:

Count: 1  
Count: 2  
Count: 3  
...and so on



