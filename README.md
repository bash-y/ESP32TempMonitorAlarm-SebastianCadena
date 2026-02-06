# ESP32 Temperature Monitoring and Alarm System

## Course
ENGR 4321 – Microcontrollers and Embedded Systems

## Student
Sebastian Cadena

## Project Description
This project uses an ESP32 DevKit V1 with a DHT22 sensor to monitor temperature. The system displays the temperature on an I2C LCD screen and activates a buzzer when the temperature exceeds 80°F.

## Hardware Used
- ESP32 DevKit V1
- DHT22 Temperature Sensor
- I2C LCD Display
- Buzzer

## System Operation
The ESP32 reads temperature data from the DHT22 sensor using GPIO 4.  
The measured temperature is displayed on the LCD through I2C communication using GPIO pins 21 and 22.  
If the temperature rises above 80°F, the ESP32 activates a buzzer connected to GPIO 18.

## Simulation Link
PASTE YOUR WOKWI LINK HERE
