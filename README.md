# 🚨 Gas Leakage Detection System
A hardware-based safety system that detects harmful gas leaks in the environment and alerts the user through buzzer/alarm and notifications.  

---

# Abstract 
The petroleum sector involves hazardous environments where gases such as methane and carbon monoxide pose significant risks to worker safety. 
This project proposes an embedded-based portable kit for monitoring methane and carbon monoxide gas levels, ensuring the safety of workers in the petroleum sector.

The kit includes:
- Gas sensors for detecting methane and carbon monoxide.
- A portable embedded gateway device.
- A cloud-based platform.
- A dedicated mobile application.

The sensors are portable and rugged, enabling real-time monitoring of gas concentrations in the work environment.

---

## 🛠 Components Used
| Component                | Quantity | Notes                                |
|--------------------------|----------|--------------------------------------|
| Arduino UNO / ESP8266    | 1        | Microcontroller                      |
| MQ-6 Gas Sensor          | 1        | Detects LPG, Methane, CO             |
| Buzzer                   | 1        | Audible alert                        |
| LCD Display (16x2)       | 1        | Gas level display                    |
| Jumper Wires, Breadboard | -        | Circuit connections                  |
| Power Supply (5V)        | 1        | Power source                         |

---

# 📖 Features
- Detects hazardous gases (like LPG, Methane, CO) in real time  
- Triggers buzzer alarm when gas concentration exceeds safe levels  
- Displays alert on LCD / Serial Monitor  
- Sends notification to user (optional IoT integration)  

---

## ▶️ Usage

1. **Open Arduino IDE**
   - Open the project code file (`firmware/main.ino`) in Arduino IDE  

2. **Select Board & Port**
   - Go to **Tools → Board** → Select *Arduino UNO* (or your board)  
   - Go to **Tools → Port** → Select the COM Port where Arduino is connected  

3. **Upload the Code**
   - Click the **Upload** button to flash the code into the Arduino  

4. **Power the Hardware**
   - Connect power to the Arduino and the Gas Sensor  

5. **Project Operation**
   - **Normal condition** → LCD will display “Safe”  
   - **Gas leak detected** → Buzzer will sound + LCD will display “Gas Leak Detected”  

---

# Circuit Diagram
<img width="1278" height="728" alt="gps blockdiagram" src="https://github.com/user-attachments/assets/66b54de9-3271-4557-a4e2-acaef843283d" />


