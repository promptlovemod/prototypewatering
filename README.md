# prototypewatering
Automatic Watering System w ESP32

Hey!
This is a repo for my Independent Study Project code

Note : *The code is partially AI assisted*

# Feature
- Receives Temp & Humid Value via DHT22
- Receives Soil moisture Raw value and convert to %
- Calculate Vapor Pressure Deficit based on DHT22 Value
- Adaptively waters the plant based on *int base = 30;* (Row 253) The base value will be adaptive based on Vapor Pressure Deficit Value
- Send all info via HiveMQ Cloud using any Wi-Fi

# How to use it
Find the file "system esp32" and copy all the code inside the file and upload it via Audrino IDE (Recommended)
