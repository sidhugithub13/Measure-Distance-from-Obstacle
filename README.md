# Measure-Distance-from-Obstacle

The objective is to measure the distance between the ultrasonic sensor and the obstacle.

The HC-SR04 ultrasonic sensor uses ultrasonic sound waves to determine the distance of an object. It offers excellent non-contact range detection with high accuracy and stable readings in an easy-to-use package from 2 cm to 400 cm or 1 foot to 13 feet.
The operation is not affected by sunlight or black material, although acoustically, soft materials like cloth can be difficult to detect. It comes complete with ultrasonic transmitter and receiver module.



![image](https://github.com/user-attachments/assets/257ff47d-39ec-4c8c-89dd-57256181a0df)

Ultra sonic sensor

The sensor head emits an ultrasonic wave and receives the wave reflected back from the target. 
Ultrasonic Sensors measure the distance to the target by measuring the time between the emission and reception.



 ![image](https://github.com/user-attachments/assets/73bd73db-c56e-4079-bb9a-5c6812765ace)

Working principle of HC-SR04
 

**Outline and detection principle:**
An optical sensor has a transmitter and receiver, whereas an ultrasonic sensor uses a single ultrasonic element for both emission and reception. In a reflective model ultrasonic sensor, a single oscillator emits and receives ultrasonic waves alternately. This enables miniaturization of the sensor head.

**Distance calculation:**
The distance can be calculated with the following formula:
Distance L = 1/2 × T × C, where L is the distance, T is the time between the emission and reception, and C is the sonic speed. 
(The value is multiplied by 1/2 because T is the time for go-and-return distance.)

**Hardware Requirements:**
•	1 × Breadboard
•	1 × Arduino Uno R3/Raspberry pi
•	1 × ULTRASONIC Sensor (HC-SR04)

**Circuit connection for Arduino:**

![image](https://github.com/user-attachments/assets/7238c0ca-c5f7-471c-ab1f-a61548a0cbb6)


**Ouput:**

![image](https://github.com/user-attachments/assets/7a3a02ee-f5d9-483e-bd3c-5820f14944b6)


**Circuit connection for Raspberry Pi:**

![image](https://github.com/user-attachments/assets/8674256e-090d-473e-820a-e37e09f66bf0)

**Output:**

![image](https://github.com/user-attachments/assets/7709ee8f-e6b9-4a00-961b-807ae1b40990)
