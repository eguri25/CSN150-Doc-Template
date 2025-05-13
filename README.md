# Cybersecurity : CSN150-Doc-Template

## Name of Project
ESP32 Introduction

## Purpose
Set up ESP32 and Arduino enviornment. Execute sketch " Wifiscanner". 

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)

## Screenshots of Arduino installation
arduino setup.png

## Links to documentation

##### Video 1:


##### Other Links: 


## Steps I followed
1. Write the steps you followed here.  This way you can keep track of where you might have messed up if the project does not work.
   * we find the CameraWebServer sketch under File > Examples > ESP32 > Camera > CameraWebServer.
   * to make it work we need to select the appropriate camera model which is AI-THINKER model.
   * Next, you need to tell the ESP32-CAM about your wireless network. Fill in the following variables with your network credentials:

const char* ssid = "REPLACE_WITH_YOUR_SSID";
const char* password = "REPLACE_WITH_YOUR_PASSWORD";

   * Once you have uploaded the sketch, open the serial monitor at baud rate 115200 and press the Reset button on the ESP32-CAM. You should see the IP address in the Serial Monitor.
   * Launch a browser and enter the IP address shown on the serial monitor. Ensure that the web browser is on the same network that the ESP32-CAM is connected to.

The ESP32-CAM should display a web page. To begin video streaming, press the Start Stream button.





## Problems
Note your problems or errors here.  Google any error you may come across, and not what you tried (even if it does not work), and what was the final answer. Document your errors and solutions that worked for you. 
* There were no problems while I was setting up the webcam on Arduino.  


### Example Problem


## Final Report
