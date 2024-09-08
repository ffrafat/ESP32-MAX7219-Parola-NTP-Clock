![image](https://raw.githubusercontent.com/ffrafat/ESP32_MAX7219_Parola_NTP_Clock/main/clockface.jpg)

# MAX7219 Parola Animated NTP Clock Using ESP32

This ESP32 code utilizes MAX7219 (FC16) mono-color 8\*32 LED matrix (4 pcs 8x8 matrix) to show a big animated clock, day, and date. It fetches the time from the NTP server and thus you will need to connect it to your local WiFi network.

The original code was found on a YouTube channel named Technical Tushar and that code was for ESP8266. Thanks to him. I immediately fell in love with the simple yet feature-rich clock and thus I ported that for my ESP32 board. Thanks to ChatGPT.

## Used Hardware Components

1. ESP32 WROOM 32 Microcontroller (You can use any ESP32 board)
2. MAX7219 LED Matrix (8x32)
3. 5 Female to Female Jumper Wires (Because both my ESP32 and MAX7219 panels had pins soldered)
4. USB Type C to C Cable (You can use USB A to C cable too)

![image](https://raw.githubusercontent.com/ffrafat/ESP32_MAX7219_Parola_NTP_Clock/main/dateface.jpg)

## Features

* Big Bold Clockface with Hour and Minute (HH:MM)
* The separator blinks for each second
* It shows the day of the week and date after a certain period which is customizable
* It has night mode feature where you can customize the time period when the led will be lit in maximum, minimum or in a certain intensity

## Instructions

* Make sure you know how to do the wire connections in ESP32 and MAX7219.
* Also, I am assuming you know how to upload sketches in your ESP32 using Arduino IDE.
* Keep the fonts.h and max7219.h in the same folder with your .ino file. Otherwise, it might not work. Install other necessary libraries (eg. WiFi) if needed.

## Demo

![image](https://raw.githubusercontent.com/ffrafat/ESP32_MAX7219_Parola_NTP_Clock/main/Demo.gif)
