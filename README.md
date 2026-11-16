# LG-Therma-V-HN1639-NK1-comunication-with-heat-pump
This is control and diagnose for old LG Therma V (2013?) I listen and replicate communication between integrated thermostat and waterbox.

Control:
ON/OFF
SET target water temperature

Sensors:
Water IN temp
Water OUT temp
Water Setpoint
ODU Compressor status
Cooling mode 
Defrost mode 
Error 
Error Code


And in my project I have two DS18B20 for measuring delta T at water input and output. I have constatnt flow trough heat exchanger so I just calibrate via integrated electric heater and energy meter: 
Turn on heater at constatnt flow of water, adjust constatnt to match electric consumption and temp difference IN/OUT that's COP = 1.
