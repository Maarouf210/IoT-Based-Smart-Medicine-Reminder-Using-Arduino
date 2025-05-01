# 💊 IoT-Based Smart Medicine Reminder Using Arduino

This project is an **IoT-enabled smart medicine reminder** designed to help patients take their medications on time. By combining a **Real-Time Clock (RTC)** with an **LCD display**, **buzzer**, **push buttons**, and **Bluetooth connectivity**, the device provides customizable and reliable reminders to take medicine once, twice, or three times a day.

---

## 🧠 Features

- 🕒 **Real-Time Clock (DS3231)**: Keeps accurate time even when the device is powered off.
- 🔘 **Custom Reminder Schedule**:
  - Once per day
  - Twice per day
  - Thrice per day
- 📟 **LCD Display**: Shows current time, date, helpful instructions, and encouragement.
- 🔔 **Audio Alerts**: Buzzer sounds at medication times.
- 💾 **EEPROM Memory**: Stores reminder settings even after power loss.
- 📱 **Bluetooth (HC-05)**: Optional interaction via serial communication.
- 🚫 **Stop Button**: Allows users to cancel the alert after taking medicine.

---

## 📦 Components Used

| Component             | Quantity |
|-----------------------|----------|
| Arduino Uno           | 1        |
| RTC DS3231            | 1        |
| HC-05 Bluetooth Module| 1        |
| 16x2 LCD Display      | 1        |
| Buzzer                | 1        |
| Push Buttons          | 4        |
| Potentiometer         | 1        |
| Breadboard + Wires    | -        |

---

## ⏱️ Default Reminder Times

| Time | Frequency |
|------|-----------|
| 08:11 AM | Daily |
| 01:15 PM | Twice a day |
| 08:20 PM | Thrice a day |

> ⚠️ These times can be easily changed in the Arduino code.

---

## 📁 File Structure
![image](https://github.com/user-attachments/assets/521adaee-c5b8-4b5e-a329-2350261ab55f)


---

## 🔧 Libraries Required

Make sure to install the following Arduino libraries:

- `LiquidCrystal`
- `Wire`
- `RTClib`
- `EEPROM`

---

## 🛠️ How to Use

1. **Assemble the Circuit** according to the wiring used in the code.
2. **Upload the Code** using Arduino IDE.
3. **Power On** the device. The LCD will display setup instructions.
4. **Select Reminder Mode**:
   - Press Button 1: Once/day
   - Press Button 2: Twice/day
   - Press Button 3: Thrice/day
5. At the scheduled times, the buzzer will sound and a message will be displayed.
6. **Press the Stop Button** to cancel the alert.

---

## ⚙️ Future Enhancements

- 🔗 Integrate with IoT cloud services for SMS/email alerts
- 📲 Add mobile app support
- 📈 Link with a full Patient Monitoring System

---

## 📄 License

This project is for academic and educational purposes only. Contributions and forks are welcome!
