---
layout: post
title: Home Automation
---
# Home Automation
Home Automation is cool, Right? We'll today build an Home Automation System that controls all the home appliances with your voice.
Yes, Using your own voice to control your home.
### Things You need:
1. PC or Mac installed with Python, Any Version, I used 3.6
1. Arduino UNO
1. 12V Relay
1. Some Wires

### Getting your Python Ready
1. Load all the required libraries
    ```python
    import speech-recognition as sr
    import serial
    import os,sys
    ```
* Speech-Recognition module is for making Speech to Text which we'll use for controlling the appliances.
* serial is to communicate with the Arduino which we'll configure later.
* OS is to control the bash commands. (Text to speech for Jarvis :P)
1. Initialize the speech module and make it with the Source.
