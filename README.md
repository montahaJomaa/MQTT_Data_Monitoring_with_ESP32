MQTT Temperature Humidity Monitoring with ESP32
This code provides an example implementation of monitoring temperature and humidity using an ESP32 microcontroller and MQTT (Message Queuing Telemetry Transport) protocol. The ESP32 communicates with a BME280 sensor to read temperature and humidity values, and then publishes them to an MQTT broker. The code also includes the functionality to subscribe to an MQTT topic and control an LED based on received messages.


#Components_used
ESP32 microcontroller board
BME280 sensor
Wi-Fi network credentials
MQTT broker information (server IP address)

#Usage
Open the Serial Monitor to view the ESP32's output.
The ESP32 will attempt to connect to the Wi-Fi network and MQTT broker.
Once connected, it will start publishing temperature and humidity readings to the MQTT broker every 5 seconds.
You can also subscribe to the topic "esp32/output" on the MQTT broker and send messages to turn the LED on or off.
