# Outdoor Lighting with Motion Detection & HA Integration

This project outlines how to create a smart outdoor lighting system for your front door and even Christmas lights.  
The system is integrated into Home Assistant, enabling comprehensive control and automation.  
The ESP32 is programmed with ESPHome to connect directly to Home Assistant.  

## Project Goals and Capabilities:
### The aim is to build a smart lighting with the following features:

**Dynamic LED effects:** Display Lights with various animated patterns.  
**Motion detection:** Utilize a RCWL-0516 radar motion sensor for accurate movement detection.  
**Wireless automation:** Remotely turn lights on and off, Monitor light status and receive alerts for malfunctions.  
**Home Assistant integration:** Connect the system to Home Assistant for centralized control and automation.  
**Adjustable timing:** Control the delay time for lights to remain on after motion and control the light based on sunrise and sunset.  
**Brightness and dimming control:** Fine-tune light intensity and dimming transitions.  
**Integrated audio:** Play Christmas carols via a speaker, by using a ESP32’s with I2S support. (optional)  

## Components Used:

Here’s a list of the components essential (currently) for this smart lighting project:  
**LED Strip:** A 2-meter strip of 5V WS2812B SMD5050 IP67 with 120 LEDs in total.  
**Microcontroller:** An ESP32 C3 SuperMini  
**Motion Detector:** A RCWL-0516 microwave motion detector  
**Home Assistant & esphome:** The central software for integration and automation.  
**Light Dependent Resistor (LDR):**  optimal3.3V Power: require for ESP32 and motion sensors.  
**5V Power:** LEDs all require a 5V power supply.  
For the 5V power supply, I used a small step-down board to convert a 12V solar power source to 5V.  


![This is wiring diagram.](https://forgani.com/wp-content/2025/06/front-lights.jpg)

> [!NOTE]
> For more information: [Outdoor Lighting with Motion Detection & HA Integration](https://forgani.com/electronics-projects/outdoor-lighting-with-motion-detection-ha-integration/).
