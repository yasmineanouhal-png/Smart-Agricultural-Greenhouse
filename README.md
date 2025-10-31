# Smart-Agricultural-Greenhouse
-Project Overview

This IoT system is designed for real-time monitoring and automated irrigation of a greenhouse. It measures:

Soil moisture

Water level

Ambient temperature

Electrical consumption of the pump via a current sensor

Plant color to assess their health

When low soil moisture is detected, the water pump and a servo-controlled valve are automatically activated, provided that the water level is sufficient and the temperature does not exceed 35°C, ensuring the safety and health of the plants.

All collected data is transmitted via Bluetooth to a mobile application and simultaneously published on the ThingSpeak platform for remote monitoring and analysis.

-Features

Real-time monitoring of soil, water, and ambient conditions

Automatic irrigation with safety checks (water level & temperature)

Plant health assessment using color detection

Data visualization and storage on ThingSpeak

Remote access via mobile application

-Components

ESP32 microcontroller

Soil moisture sensor

Water level sensor

Temperature sensor

Current sensor for pump consumption

Servo motor and valve

RGB/color sensor for plants

Bluetooth module

ThingSpeak platform for data monitoring
