# Weather-Monitoring-System-Using-IoT-and-Machine-Learning
The Hardware is designed to read data from a DHT11 temperature and humidity sensor, as well as an LDR (Light Dependent Resistor) sensor, and send that data to ThingSpeak, an IoT platform, using an ESP8266 (WiFi module).
- Function: Reads data from DHT11 temperature/humidity and LDR sensors, then sends this data to ThingSpeak IoT platform using an ESP8266 WiFi module.
- Operation: Connects to a specified WiFi network, reads sensor values, constructs a POST request, and periodically sends sensor data to ThingSpeak server for updating fields in a designated channel.
- Key Components: Utilizes DHT.h and ESP8266WiFi.h libraries, defines sensor pins, and employs WiFiClient to establish connections and transmit data to ThingSpeak.



Prediction of weather of a particular location based on the previous weather data of the location 



- The Random Forest Regressor model successfully predicts temperature based on timestamp, humidity, and light intensity.
- Descriptive statistics provide insights into feature characteristics.
- The model's performance was evaluated using MSE and R2.
- Model accuracy within a tolerance of ±1.0 degrees was assessed.

This project demonstrates the process of collecting, preprocessing, exploring, modeling, and evaluating a dataset for temperature prediction. Further improvements may involve hyperparameter tuning or exploring other regression algorithms for enhanced accuracy.
