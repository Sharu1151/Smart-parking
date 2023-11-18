# Smart-parking
The project involves building a smart parking system that utilizes ultrasonic sensors to detect parking space availability and LED display arrays to indicate the status of parking spaces to drivers.
Procedure:
Step 1: Take ESP32 Board.
Step 2: Connect Ultrasonic Sensors with the following mentioned connections:
Ultrasonic sensor : (+) pin to ESP32: 3V3 pin for all Ultrasonic sensors.
Ultrasonic sensor : (-) pin to ESP32: Gnd pin for all Ultrasonic sensors.
Ultrasonic sensor: (TRIG) pin to ESP32: D2 pin for Ultrasonic sensor-1.
Ultrasonic sensor: (ECHO) pin to ESP32: D15 pin for Ultrasonic sensor-1.
Ultrasonic sensor: (TRIG) pin to ESP32: D18 pin for Ultrasonic sensor-2.
Ultrasonic sensor: (ECHO) pin to ESP32: D5 pin for Ultrasonic sensor-2.
Ultrasonic sensor: (TRIG) pin to ESP32: D27 pin for Ultrasonic sensor-3.
Ultrasonic sensor: (ECHO) pin to ESP32: D26 pin for Ultrasonic sensor-3.
Step 3: Connect LEDs's to ESP32 with the following mentioned connections:
Connect the positive leg (Anode) of each LED to the output pins of the ESP32 in the following
Manner:
LED 1: (+) pin to ESP32: D13 pin.
LED 2: (+) pin to ESP32: D12 pin.
LED 3: (+) pin to ESP32: D14 pin.

Note: For LED positive and Negative Leg, please refer to the Component Description of FAQ
Document.
Step 4: Connect each LED's Negative leg (Cathode) to the GND pin of the ESP32.
LED 1: (-) pin to GND pin.
LED 2: (-) pin to GND pin.
LED 3: (-) pin to GND pin.
Note: For LED positive and Negative Leg, please refer to the Component Description of the FAQ
Document.

Step 5: Burn the code to the ESP32 Board using Arduino IDE.
Step 6: Test the Project
Whenever an ultrasonic sensor detects any vehicle, the LED will be off. When there is no
vehicle in the parking area, the LED shows a green signal to park the vehicle.
