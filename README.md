# roomsense-one
A simple diy homeassistant room  sensor, monitoring temprature and humidity. 

The first version is powered by a USB-C connector with 5V


## Needed Components 

* ESP32-C3 Super Mini Plus
* AHT20 & BMP280 Breakout Board
* BulkBoost Converter -> TPS63020 Out: 3.3V In: 2 - 5.5V
* Case 3D printed
* USB-C Connector
* Cables,....


Software: 

esphome 2025.12.5 was used to develop this sensor


## Install

First checkout the project using GIT and make sure you have `esphome` installed.

```
git clone https://github.com/mjellat/roomsense-one.git

cd roomsense-one

```

Now adapt the `roomsense-one.yaml` with your WIFI settings unsing your favorite editor.

```
nano roomsense-one.yaml
```

Then install on your esp device. To do so, connect the ESP32 SuperMini with your computer using a proper USB Cable.

```
esphome run roomsense-one.yaml
```

### I2C Interface

* SDA -> Pin 21
* SCL -> Pin 20

# ToDo:



