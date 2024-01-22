                                            ApiSensor

Apisensor is an autonomous system capable of measuring the characteristics of a beehive and sending the data to its owner.

Support
Complete documentation: https://www.hackster.io/wilson032/apisensor-948d75
Contact us: wilson.ranganathan@gmail.com
Project Status
This project is currently in stable version.

required software :
ARDUINI IDE

Required Librairies : 
-Arduino Low Power by Arduino
-MKRWAN by Arduino
-DFRObot_HX711 by DFRObot
-DHT sensor librairy by Adafruit
-DallasTemperature by Miles Burton
-OneWire by Jim Studt
-Arduino FFT by Enrique Condes

Instructions
Clone the project: git clone https://github.com/wilson030402/ApiSensor

Use: Each code in git allows you to test a functionality of the project
You must check the pins used at the beginning of the file
- 2T+BAT+KG+DHT :Allows you to obtain the battery level with weight, information from the two temperature probes and the dht22
- 2T+KG+DHT :Allows you to obtain the weight, information from the two temperature probes and the dht22
- Balance : Allows you to obtain the weight from the strain gauge
- CODE SANT-CYR :The final code of the project
- DHT22+ Batterie : Allows you to obtain temperature and humidity from the DHT22 and battery level
- DHT22 : Allows you to obtain temperature and humidity from the DHT22
- Local entier : This code contains allows you to check if all the sensors work locally without sending to TTN
- Lorawan : Code which allows you to check that you can connect to TTN and send certain data
- OneWire : Allows you to obtain the temperature from the two DS18B20 probes in OneWire (on the same bus)
- PF: This file contains the Payload formatter code to put on TTN
- Temp1 : Allows you to obtain the temperature from one of the DS18B20 probes
- Temp2 : Allows you to obtain the temperature from the two DS18B20 probes
- Downlink : This code contains the Payload formatter to perform downlinks on TTN
- Local final : This code contains allows you to check if all the sensors work locally without sending to TTN




                                            
                                            

                                            
