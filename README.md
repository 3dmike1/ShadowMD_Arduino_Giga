# ShadowMD_Arduino_Giga



This is a modified version of the ShadowMD project, which uses an Arduino Giga R1 Wifi board with onboard Bluetooth and Audio capabilities. This repository contains the updated code for running the ShadowMD project on an Arduino Giga R1 Wifi board, using a USB Thumbdrive named "R2USB" with the audio files located in a directory on the thumb drive named "R2D2 Sounds MP3Trigger".

Dependencies

This project relies on the following libraries:

MP3Trigger library
ArduinoJSON library
PS3Move library
SD library
Hardware

This project uses the following hardware components:

Arduino Giga R1 Wifi board
USB Thumbdrive named "R2USB"
PS3 Move Navigation controllers
Configuration

To use this project, the following parameters must be set in the config.ini file located in the root directory of the USB Thumbdrive:

bluetoothAddress: The MAC address of the Bluetooth module on the Arduino Giga R1 Wifi board.
ps3MoveServiceName: The name of the PS3 Move Navigation service.
ps3MoveServiceAddress: The MAC address of the PS3 Move Navigation service.
mp3TriggerSerial: The serial port number for the MP3Trigger module.
mp3TriggerTriggerPin: The trigger pin number for the MP3Trigger module.
mp3TriggerBusyPin: The busy pin number for the MP3Trigger module.
mp3TriggerReadyPin: The ready pin number for the MP3Trigger module.
mp3TriggerResetPin: The reset pin number for the MP3Trigger module.
Usage

Once the hardware and configuration are set up correctly, the ShadowMD project can be run on the Arduino Giga R1 Wifi board by uploading the ShadowMD_Arduino_Giga.ino sketch to the board.

When the project is running, the PS3 Move Navigation controllers can be used to control the movements of the ShadowMD robot, and audio files can be played through the MP3Trigger module triggered by specific actions of the robot.

Credits

This project is based on the original ShadowMD project created by Eebel.

License

This project is licensed under the MIT License - see the LICENSE file for details.
