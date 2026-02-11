# OLED Display Project

## Overview
This project demonstrates how to interface an SSD1306 128x64 OLED display with a microcontroller using C++ and the Arduino framework. The display is initialized and used to show text, making use of the Adafruit GFX and SSD1306 libraries.

## Using CLion
Development is done in the CLion IDE, which offers advanced C++ support, code navigation, and integrated build tools. CLion is configured to work with Arduino projects for seamless development and deployment.

## IDE Version
- CLion 2025.3.2

## Code Structure
- `src/main.cpp`: Contains the main application logic, including OLED initialization and display routines.

## Libraries
- `Arduino.h`: Core Arduino functions.
- `Wire.h`: I2C communication.
- `Adafruit_GFX.h`: Graphics library for drawing text and shapes.
- `Adafruit_SSD1306.h`: Driver for SSD1306 OLED displays.

## Dependencies
- Arduino IDE or PlatformIO (for building and uploading code)
- Adafruit GFX Library
- Adafruit SSD1306 Library
- Compatible microcontroller (e.g., Arduino Uno, Nano)
- I2C support enabled on the microcontroller

## Hardware Components
- SSD1306 128x64 OLED display (I2C, address: 0x3C)
- Microcontroller (e.g., Arduino Uno)
- I2C connection (SDA, SCL lines)
- USB cable for programming

## Setup Instructions

1. **Install CLion**  
   Download and install CLion 2025.3.2 from the official JetBrains website.

2. **Install Arduino IDE or PlatformIO**  
   Required for compiling and uploading code to the microcontroller.

3. **Clone the Repository**  
   Clone this project to your local machine.

4. **Install Libraries**  
   Use the Arduino Library Manager or PlatformIO to install:
    - Adafruit GFX Library
    - Adafruit SSD1306 Library

5. **Connect Hardware**
    - Connect the OLED display to the microcontroller using I2C (SDA to A4, SCL to A5 on Arduino Uno).
    - Power the display and microcontroller.

6. **Build and Upload**
    - Open the project in CLion.
    - Build the project and upload it to your microcontroller.

## How It Works

- The code initializes the OLED display using the Adafruit SSD1306 library.
- It checks for successful initialization and prints an error to the serial monitor if it fails.
- The display is cleared, and text is printed to the screen, including author and contributor names.

## Contributors Displayed on OLED
- Gaurav Thakur
- Sorab Bhabautiya
- Samarth Gupta
- Nitin Meena

## Author
- Gaurav Thakur

## License
This project is licensed under the MIT License.
