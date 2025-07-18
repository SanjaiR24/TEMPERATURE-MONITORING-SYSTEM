# TEMPERATURE-MONITORING-SYSTEM

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SANJAI R

*INTERN ID*: CT04DH8046

*DOMAIN*: EMBEDDED SYSTEMS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH

*TASK DESCRIPTION*

This task involves designing a basic embedded system to measure ambient temperature using the LM35 sensor and display the temperature on a 16x2 I2C LCD using Arduino UNO.The analog output of the LM35 is read through the Arduino’s analog input pin and converted into temperature (°C) using a formula. The temperature is displayed on the I2C LCD screen in real-time.This task helps in understanding analog signal processing, interfacing sensors, and I2C communication.

*COMPONENTS USED*:
   
    Arduino UNO

    LM35 Temperature Sensor

    16x2 I2C LCD Display

    Breadboard and Jumper Wires

*WORKING PRINCIPLE*:

The LM35 outputs 10mV per degree Celsius.
Arduino reads the analog voltage and converts it into a temperature value using the formula:
Temperature (°C) = (analogRead * 5.0 / 1023.0) * 100
The calculated temperature is displayed on the I2C LCD.
I2C LCD simplifies wiring by using just two pins:
SDA: A4
SCL: A5

*OUTPUT*

![Image](https://github.com/user-attachments/assets/24fe181a-7200-4646-ac77-a459a5dab2ea)
