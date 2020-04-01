## Intelligent-IOT
### Integrating IOT with machine learning to create environment monitoring system
This repository describes a model which is capable of collecting real time environmental data, such as temperature, pressure, humidity, air quality index etc (depending on the application specific),then analysing it to extract necessary insights for obtaining further conclusions. The entire process is automated.

The microcontroller used here is **Arduino UNO**.\
Sensors used:\ a) DHT11 (Humidity and temperature)\
              b) MQ135 (Smoke Sensor)\
Softwares:  Arduino IDE _(for communicating with arduino board to collect the data)_.\
After data acquisition the data is processed and plotted in real time by python and its plotting library _(matplotlib and seaborn)_.

