# Manual-IoT
Manual for a school project IoT
## Glimspe - smart mirror
Today in this manual we will be making a smart mirror activated by motion that lights up leds based on your own movement and shows weather information with colors, this will help you start your day without using your phone.
### Goal
The Goal of this project is to detects your presence and gives visual feedback with LEDs about the weather.
### requirements
- NodeMCU ESP8266
- HC-SR04 Ultrasonic Distance Sensor
- Adafruit Led strip
- Connection wires
- USB cable
<img width="2309" height="1732" alt="image" src="https://github.com/user-attachments/assets/e58ee18f-cbed-4d2d-9fe8-334520232926" />

### Software
- Arduino IDE
- Libraries; ESP82266WIFI, ArduinoJson, Adafruit_Neopixel
- Openweathermap for API Key api.openweathermap.org

# Step 1
Connect the HC-SR04 sensor and LED-strip to the NodeMCU
 > [! NOTE] > DO NOT USE THE 5V, THE 3V WILL DO JUST FINE. >
- **Component -	NodeMCU Pin**
- HC-SR04 VCC	- 3V
- HC-SR04 GND	- G
- HC-SR04 TRIG	- D5
- HC-SR04 ECHO	- D6
- LED-strip Data In -	D2
- LED-strip 5V	- 3V
- LEDstrip GND	- GND

<img width="1732" height="2309" alt="image (1)" src="https://github.com/user-attachments/assets/ed9d9637-000f-4b67-8a0d-b25e23599828" />

### Checkpoint
Connect the NodeMCU to your PC sensor LED may blink
<img width="1508" height="2651" alt="image (2)" src="https://github.com/user-attachments/assets/a1b09aae-dbc3-41ab-aea1-5fe171953427" />

You should see this in the bottom right corner of your arduino screen that it is connected
<img width="464" height="50" alt="Scherm­afbeelding 2025-10-17 om 22 44 32" src="https://github.com/user-attachments/assets/1e19a0cb-c8dd-4a91-a77f-96fa0bda09d3" />
if that is not the case, you might want to select the right module 

# step 2
 






