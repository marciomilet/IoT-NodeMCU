# IoT-NodeMCU

Building a IoT solution using a NodeMcu v3 for a prototype  
we used a DHT11 sensor for measuring the temperature and humidity, a ESP9960 sensor for reading gestures made from the user and make the measurements and print then, also a RGB LED was used for giving the user visual cues on if the code has worked as intended, a thingspeak API is used for taking the measurements and saving then wich can be acessed here:  
https://thingspeak.com/channels/2492075/  
the frontend and the backend are both hosted on azure using a windows server VM and a ubuntu server respectivelly, the code for both can be acessed here:  
https://github.com/marciomilet/appArnot  
https://github.com/dayviddouglas/acesso-dashboard-Projeto-Integrador  

# Libraries

https://github.com/sparkfun/SparkFun_APDS-9960_Sensor_Arduino_Library  
https://github.com/adafruit/DHT-sensor-library  

# DHT11

GND-G  
DATA-D3  
VCC-3V  

# ESP9960

GND-G  
VCC-3V  
SDA-D2  
SCL-D1  
INT-D6  
# LED

red-D5  
black(voltage)-3V or G it depends on your LED type  
blue-D8  
green-D7  



