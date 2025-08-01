# All Sensors Testing Kit using Arduino Nano and OLED

This project is a multi-sensor testing system using an Arduino Nano and a 0.96" OLED display. It allows you to scroll through a menu and test different sensors live on a compact OLED screen. A push button is used to switch between sensor readings.

## 🧰 Components Used

Arduino Nano – 1  
OLED Display (128x64 I2C) – 1  
Push Button – 1  
MQ-2 Gas Sensor – 1  
DHT11 Temp/Humidity Sensor – 1  
IR Obstacle Sensor – 1  
Ultrasonic Sensor (HC-SR04) – 1  
Flame Sensor – 1  
LDR Sensor – 1  
Soil Moisture Sensor – 1  
Sound Sensor – 1  
PIR Sensor – 1  
ADXL335 Gyro Sensor – 1

## 🔌 Pin Connections

MQ-2 → A0  
DHT11 → D2  
IR Sensor → D3  
Ultrasonic → D4 (Trig), D5 (Echo)  
Flame Sensor → D6  
LDR → A1  
Soil Moisture → A2  
Sound Sensor → A3  
PIR → D7  
Button → D8  
OLED → A4 (SDA), A5 (SCL)

## ⚙ How It Works

- When powered on, the OLED shows a welcome screen.
- Press the button to cycle through the sensors.
- Each screen shows live sensor data.
- If a sensor is not connected, it will skip or show no value.

## 📚 Required Libraries

Install via Arduino Library Manager:

- Adafruit GFX Library  
- Adafruit SSD1306  
- DHT sensor library

## 🧑‍💻 Uploading Code

1. Connect Arduino Nano to your computer.
2. Open the Arduino IDE.
3. Go to Tools > Board > Arduino Nano.
4. Select Processor: ATmega328P (Old Bootloader) if needed.
5. Upload the .ino file.

## 🧪 Output Sample

2. DHT11 Temp  
Temp: 28.0 C  
Hum: 64.0 %

## 📦 Applications

- DIY sensor lab tool  
- ECE/Electronics educational kit  
- Rapid sensor testing and demos  

## 🙋‍♂ Created By

Mohankumar M  
ECE Dept, KPR Institute of Engineering and Technology

⭐ Feel free to fork, star, and contribute!
