# smoke-detection-for-smart-home
Designing an intelligent gas leakage detection system as part of a smart home automation framework that enhances safety, convenience, and responsiveness. The system aims to continuously monitor the environment for hazardous gases like LPG and provide real-time alerts (both audio and visual),
<img width="951" height="1154" alt="image" src="https://github.com/user-attachments/assets/3dcd4648-1dc6-4601-b2cd-7f3de0280684" />
1. Hardware Requirements:
• Arduino UNO:
Acts as the microcontroller unit that processes the gas sensor's data and
controls output devices like LEDs and buzzer.
• MQ-6 Gas Sensor:
Detects the presence of flammable gases such as LPG, butane, propane, etc.
and sends an analog signal to the Arduino.
• Red & Green LEDs:
Indicate gas status — Green for safe, Red for danger/leak detected.
• Buzzer:
Provides an audio alert when gas leakage is detected.
• Breadboard:
Used to build the circuit without soldering, useful for prototyping.
• Jumper Wires:
Connect all the components on the breadboard to the Arduino.
• Power Source (USB or 9V Adapter):
To power the Arduino and sensor.

2. Software Requirements:
• Arduino IDE:
To write, compile, and upload the code to the Arduino UNO board.
• Embedded C / Arduino Language:
Programming language used to write the code for controlling the system
Behavior.
