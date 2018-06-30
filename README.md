# SparkFun Venus GPS Coding
Development board: [Arduino Uno](https://store.arduino.cc/arduino-uno-rev3)
GPS Module:
  - [SparkFun Venus GPS with SMA Connector](https://www.sparkfun.com/products/11058)
  - [SparkFun Venus GPS Logger - SMA Connector](https://www.sparkfun.com/products/10920)

## **Usage:**
Change the Arduino and GPS baudrate to what your hardware uses, by default `9600`
Uncomment the `byte` code parts and the corresponding `gpsSerial.write`
Do not forget to uncomment rule 59-62 if you change the baudrate and change the baudrate in rule 62 to whatever you set it to
