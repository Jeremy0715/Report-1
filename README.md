# Report-1
Evaluation of Components for Autonomus Line Following Vehicle

# Arduino Projects README

This repository contains Arduino sketches for various projects. Each sketch is designed for a specific hardware setup. Below is a brief overview of each project along with instructions on how to use them.

## Project 1: Measuring Wheel using Rotary Encoder

### Description
This Arduino sketch enables you to build a DIY measuring wheel using a rotary encoder. The system calculates distance based on the number of encoder steps and displays the result on an I2C LCD. Additionally, a reset button is implemented to zero the distance.

### Hardware Setup
- Connect a rotary encoder to pins 2 (CLK) and 3 (DT).
- Connect a reset button to pin 4.

### Usage
1. Upload the sketch to your Arduino board.
2. Connect the hardware components as described.
3. Power on the system and rotate the wheel to measure distance.
4. Press the reset button to zero the distance.

## Project 2: Range Measurement using HC-SR04 Ultrasonic Sensor

### Description
This Arduino sketch utilizes an HC-SR04 ultrasonic sensor to measure distance. The distance in centimeters is printed to the serial monitor.

### Hardware Setup
- Connect the HC-SR04 sensor's trigger pin to pin 9.
- Connect the HC-SR04 sensor's echo pin to pin 10.

### Usage
1. Upload the sketch to your Arduino board.
2. Connect the HC-SR04 sensor as described.
3. Open the serial monitor to view real-time distance measurements.

## Project 3: Motion Measurement using MPU-6050

### Description
This Arduino sketch reads motion data from an MPU-6050 accelerometer and gyroscope sensor. The measurements include acceleration, rotation, and temperature.

### Hardware Setup
- Connect the MPU-6050 sensor to the I2C bus.

### Usage
1. Upload the sketch to your Arduino board.
2. Connect the MPU-6050 sensor as described.
3. Open the serial monitor to view motion data.

## Project 4: Line Following Robot using IR Sensors

### Description
This Arduino sketch is designed for a line-following robot using IR sensors. The robot can move forward, turn left, turn right, or stop based on the input from the IR sensors.

### Hardware Setup
- Connect IR sensors to pins 2 (Left Sensor) and 4 (Right Sensor).
- Connect motor control pins: enA, enB, in1, in2, in3, in4.

### Usage
1. Upload the sketch to your Arduino board.
2. Connect the IR sensors and motor control pins as described.
3. Place the robot on a surface with a visible line.
4. The robot will follow the line based on sensor inputs.

Feel free to refer to each project's specific section for more details on hardware connections and usage instructions.
