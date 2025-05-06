# home-automation-system


## project overview
This project involves the development of an IoT-Based Home Automation System aimed at enabling users to remotely monitor and control home appliances using a smartphone or web interface. The primary focus is on enhancing convenience, security, and energy efficiency through automation.

Using a microcontroller with Wi-Fi capabilities, the system connects to cloud platforms to allow real-time control and feedback of devices such as lights, fans, or any general appliance. The setup is scalable and can be extended to integrate sensors and smart assistants.


## Components and apps used
Hardware Components:
NodeMCU ESP8266 – microcontroller with built-in Wi-Fi

Relay Module (1/4/8-channel) – to control high-voltage home appliances

Bulb or Fan – as controlled output devices

Push Buttons / Switches – optional manual control

Power Supply – for NodeMCU and relay module

Jumper Wires, Breadboard – for connections

Software & Applications:
Arduino IDE – to write and upload firmware to NodeMCU

Blynk App / MQTT Dashboard / Firebase Console – for real-time IoT control

Tinkercad – for simulation and design (optional)

GitHub – for version control and documentation


## Libraries used for compiling of code
To compile and run the NodeMCU firmware successfully, the following libraries are used:

ESP8266WiFi.h – enables Wi-Fi communication on the ESP8266

BlynkSimpleEsp8266.h – integrates the NodeMCU with the Blynk mobile platform

ArduinoJson.h – used for handling data formats, especially with cloud platforms like Firebase

PubSubClient.h – for MQTT protocol communication (if used)

SimpleTimer.h – for time-based operations

All libraries can be installed via the Arduino Library Manager or added manually from GitHub repositories.


## Project outcome
By the end of this project, the system was able to:

Successfully turn appliances ON/OFF remotely using a mobile phone

Monitor real-time status of connected devices

Respond to commands over the internet with low latency

Ensure basic safety (relay isolation and proper wiring) while dealing with AC loads

Provide a modular, extensible setup for future enhancements (e.g., voice control, scheduling)


## Conclusion
The IoT-Based Home Automation System demonstrates the power of embedded systems and cloud connectivity in modern smart homes. The system brings convenience, energy efficiency, and control to everyday appliances using affordable and widely available components. Future scope includes adding sensors (temperature, motion), integrating voice assistants (like Alexa/Google Home), and deploying it as a complete smart home ecosystem.
![Screenshot (50)](https://github.com/user-attachments/assets/bd090646-c4ce-47ab-8e2c-ad18d200d02b)
