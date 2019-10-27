# Doorbell Cam

**A Doorbell Camera App using Node.js  - Implemented by Eduardo J. Castillo**

## Required Modifications to enable Webapp Functionality 

**As described by the authors (David Goedicke and Nikolas Martelaro), the original code designed for serial communications was modified to add a webcam functionality that takes pictures remotely.**

**A new variable 'NodeWebcam' was created to invoke the "node-webcam" module. In addition, an event triggered function was created to take a picture when the "Take a picture" button was pressed. I modified the code to trigger a photo captures every time "doorbell" button was pressed.** 

**Below is a demo of the functionality:**

[Basic Arduino Clock Trigger]( https://www.youtube.com/watch?v=uKbn_pM_ZrM)

[Basic Doorbell Camera Circuit Functionality]( https://www.youtube.com/watch?v=HeRE_vQISpw)

## Description of the Final Doorbell Cam App

**After completing the basic template for the lab, I decided to implement a GPS-based camera trigger. To accomplish that
objective, I researched several options to extract GPS information from my iPhone. After some research I was able to extract
my coordinates using the GPS2IP iOS app and the cURL command on the Raspberry Pi terminal. After that, I found a Nodejs package called gps, an extensible parser for National Marine Electronics Association (NMEA )sentences, used in GPS communications. I was able to load a simple node.js example that decodes a NMEA  data packet through the terminal.**

**I was also able to transfer GPS data from my iPhone in real time and validate it using Google Maps. Admittedly, the whole camera trigger concept was a bit ambitious, so I decided to continue working on the idea as part of my final project (a very low bandwidth traffic monitoring system).**

**Below is a demo of the functionality achieved thus far:**

[NMEA Data with iPhone and Node.js]( https://www.youtube.com/watch?v=E7WsG55H8mo)



