# Cybersecurity : CSN150-Doc-Template

## Name of Project
ESP32-CAM WhatsApp Message Sender

## Purpose
Send WhatsApp messages automatically using an ESP32-CAM-MB and the CallMeBot API.

## Equipment
* [ESP32Cam](https://www.amazon.com/Aideepen-ESP32-CAM-Bluetooth-ESP32-CAM-MB-Arduino/dp/B08P2578LV/ref=sr_1_3?crid=4FY0ECFW0ZX7&keywords=ESP32+Cam&qid=1678902050&sprefix=esp32+cam%2Caps%2C240&sr=8-3)

* [USB Micro Data Cable](https://www.amazon.com/AmazonBasics-Male-Micro-Cable-Black/dp/B0711PVX6Z/ref=sr_1_1_sspa?keywords=micro+usb+data+cable&qid=1678902214&sprefix=Micro+USB+data+%2Caps%2C89&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFaU0NaUVZHU1RFUlAmZW5jcnlwdGVkSWQ9QTA3NTA4MDVFVERCS01HVlgxM1YmZW5jcnlwdGVkQWRJZD1BMDE4NTE1NTIwWUdONkdWSzU1M1Amd2lkZ2V0TmFtZT1zcF9hdGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl)
* [USB to USB C Adapter](https://a.co/d/0KY9rxd)]

## Links to documentation

##### Video 1: 
[https://www.youtube.com/watch?v=pRa3cijuuik]


 

##### Other Links: Video 2:
[https://www.youtube.com/watch?v=I22uHf97EG4&t=1s]

### Video 3
[https://www.youtube.com/watch?v=HQBtwz5EBZM]

#### Video 4
[https://www.youtube.com/watch?v=4inE-n6kXSE]



## Steps I followed
1. Installing the Arduino IDE ( https://www.arduino.cc/en/software/). 
2. Installing the USB-to-Serial Bridge Driver ([CH340 drivers](https://www.wch-ic.com/downloads/CH341SER_ZIP.html)
3. Installing the ESP32 Arduino Core [File>preferences](https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json)
4. Selecting the Board and Port (Tools > Board > ESP32 Arduino and select AI-Thinker ESP32-CAM)
5. ESP32-CAM Example 1 : Blink (File > Basic > Blink)
6. More CAM Example : (File > Examples > ESP32)
7. ESP32-CAM Example 2 : Live Video Streaming Server (File > Examples > ESP32 > Camera > CameraWebServer)
   #Because we’re using the AI-THINKER model here, uncomment it and comment all the other models.
   ##Next, you need to tell the ESP32-CAM about your wireless network. Fill in the following variables with your network credentials:
8. Accessing the Video Streaming Server (open the serial monitor at baud rate 115200 and press the Reset button on the ESP32-CAM.)






## Problems
Note your problems or errors here.  Google any error you may come across, and not what you tried (even if it does not work), and what was the final answer. Document your errors and solutions that worked for you.  

1. I have a MacBook Air that only has USB-C ports but ESP32-CAM-MB uses a USB-A to USB cable, which doesn’t fit into my laptop.

How did I solve: I got a USB-C to USB Adapter to connect the USB-A cable to my MacBook. After that I was able to connect the ESP32-CAM-MB to my laptop.

2.WiFi connecting...................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................x�x�x�x��xxxx�x����x������x�x�WiFi connecting........................................................ets Jul 29 2019 12:21:46


 How did I solve:  I entered the wifi username wrong. I solved it by RE-entering the correct Wifi Credentials and it worked.



## Final Report
