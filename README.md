# ESP32-CAM Surveillance Robotic Car

## Project Overview

A physical surveillance robotic car built using an ESP32-CAM configured for the AI-Thinker camera module. The system provides a browser-based interface for wireless movement control and live camera streaming over Wi-Fi.

## Repository Structure

src/ — Arduino source code

hardware/ — Component list and wiring documentation

media/ — Prototype photos and demonstration video

docs/ — Setup and operating instructions

## Implemented in the Source Code

- Live MJPEG camera stream.
- Browser-based forward, backward, left, right, and stop controls.
- Camera image settings, including brightness, contrast, frame size, and image quality.
- Light ON/OFF control.
- Wi-Fi connectivity with the device's local IP address displayed over the serial monitor.

## Hardware and Software

- **Controller/camera:** ESP32-CAM, AI-Thinker configuration
- **Development environment:** Arduino IDE
- **Programming language:** Arduino/C++
- **Interface:** Embedded web interface served by the ESP32

## Usage

1. Install ESP32 board support in the Arduino IDE.
2. Ensure the required camera-server source files and libraries are available.
3. Configure Wi-Fi credentials locally without committing them to GitHub.
4. Select the appropriate ESP32-CAM board and upload the sketch.
5. Connect to the same network and open the device's IP address in a browser.
6. Use the on-screen controls to operate the car and view the camera stream.

Actual motor-driver wiring, power connections, and any board-specific settings should be documented from the hardware used in this build.

## Author

Kiran Joy T
GitHub: https://github.com/KiranJoyT
