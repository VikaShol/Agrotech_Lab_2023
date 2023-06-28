# Agrotech_Lab_2023

The goal of our project is to create a compact greenhouse that effectively regulates the humidity levels both in the air and in the water for optimal plant growth. To achieve this, we incorporated temperature sensors and fans to control the humidity in the air, as well as soil moisture sensors and a dripper system to regulate the moisture levels in the soil.
Additionally, we used a solar panel to power the ESP-CAM, in order to capture and document our project and ensure that the greenhouse operates efficiently and sustainably.  

<img src="https://github.com/VikaShol/Agrotech_Lab_2023/blob/main/Photos/project_inside_pic.jpeg" width="300" height="400"> <img src="https://github.com/VikaShol/Agrotech_Lab_2023/blob/main/Photos/project_area_pic.jpeg" width="300" height="400">

By implementing these technologies, we aim to create an environment where plants can thrive by maintaining the ideal humidity conditions required for their growth and development.

For our equipment list, please visit this link : [https://github.com/VikaShol/Agrotech_Lab_2023/blob/main/Equipment_List](https://github.com/VikaShol/Agrotech_Lab_2023/blob/main/Equipment/README.md)

For our full code and explanation of the steps, please visit this link: https://github.com/VikaShol/Agrotech_Lab_2023/tree/main/Code

For images of the project, please visit this link :
https://github.com/VikaShol/Agrotech_Lab_2023/tree/main/Photos

Guy, Shir and Vika
Faculty of Agriculture

<img src="https://github.com/VikaShol/Agrotech_Lab_2023/blob/main/Photos/Us.jpg" width="150" height="200">

## Project Description

This project consists of two parts: monitoring soil moisture levels and automating watering using solenoid valves, as well as controlling humidity levels with a fan.

### Soil Moisture Monitoring and Automated Watering

In the first part of the project, three soil moisture sensors are placed inside separate pots to monitor the moisture levels in the soil. These sensors measure the amount of moisture present in the soil and provide feedback to the system.

Using the data from the soil moisture sensors, the system determines whether the soil requires watering. If the moisture levels drop below a certain threshold, indicating the need for water, the system triggers the watering mechanism.

<img src="https://github.com/VikaShol/Agrotech_Lab_2023/blob/main/Photos/Automated%20Watering.png" width="500" height="450"> <img src="https://github.com/VikaShol/Agrotech_Lab_2023/blob/main/Photos/Automated-Watering_1_.jpg" width="300" height="400">

### Humidity Control

The second part of the project focuses on controlling humidity levels using an SHT31 sensor. The SHT31 sensor measures the relative humidity (RH) in the environment. If the RH exceeds a predefined threshold, indicating excessive moisture, the system activates a fan to lower the humidity.

By integrating the SHT31 sensor and the fan control mechanism, the system creates a closed-loop feedback system to maintain optimal humidity levels. This feature ensures a conducive environment for plant growth and helps prevent issues such as mold or fungal growth.


<img src="https://github.com/VikaShol/Agrotech_Lab_2023/blob/main/Photos/Humidity%20Control.jpg" width="500" height="450"> <img src="https://github.com/VikaShol/Agrotech_Lab_2023/blob/main/Photos/Humidity_Control_P.jpeg" width="300" height="400">


### ESP32-CAM MJPEG2SD

This project utilizes code from the [ESP32-CAM_MJPEG2SD](https://github.com/s60sc/ESP32-CAM_MJPEG2SD) repository by [s60sc](https://github.com/s60sc).

Description: [The "ESP32-CAM_MJPEG2SD" project is designed to enable an ESP32-CAM module to capture MJPEG video streams from a camera and save them directly to an SD card. The ESP32-CAM module combines an ESP32 microcontroller and a camera module, making it an ideal platform for capturing and processing video.]

<img src="https://github.com/VikaShol/Agrotech_Lab_2023/blob/main/Photos/esp32-cam.jpeg" width="200" height="300"> <img src="https://github.com/VikaShol/Agrotech_Lab_2023/blob/main/Photos/esp32-cam_fritzing.png" width="200" height="300">


Feel free to explore the repository for more detailed information, including circuit diagrams andcode implementation.

