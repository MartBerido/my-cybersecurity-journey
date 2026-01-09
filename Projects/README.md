# DrownSaver – Automatic Inflating Anti-Drowning Device

## 📌 Project Overview
DrownSaver is a wearable safety device designed to help prevent drowning incidents by automatically inflating an airbag when drowning behavior is detected. The device also sends a real-time alert to lifeguards through a mobile application.

---

## 🎯 Objective
The goal of this project was to:
- Design a **wearable anti-drowning device**
- Automatically detect drowning behavior
- Inflate a CO₂-powered airbag for buoyancy
- Notify lifeguards via a **Bluetooth-connected mobile app**

---

## 🛠️ Tools & Technologies Used

### Hardware
- Arduino Pro Mini
- Tilt/Vibration Sensor
- Servo Motor
- CO₂ Cartridge
- Bluetooth Module
- 18650 Li-ion Battery
- Charging Controller & Voltage Regulator

### Software
- Arduino IDE (Embedded C)
- MIT App Inventor (Mobile App)
- Waterfall Development Methodology

---

## ⚙️ How It Works
1. The user wears the device on their wrist.
2. The tilt sensor detects abnormal body movement associated with drowning.
3. The Arduino processes the signal and:
   - Activates a servo motor
   - Pierces a CO₂ cartridge
   - Inflates an airbag for flotation
4. Simultaneously, a Bluetooth alert is sent to the lifeguard’s mobile application.
5. The system also supports **manual activation** via a button.

---

## 📊 Results & Key Findings
- **100% reliability** during experimental trials (automatic and manual modes)
- Mobile alerts successfully triggered at distances up to **10 meters**
- Lifeguard evaluation rated the system as:
  - Reliable
  - Functional
  - User-friendly
  - Efficient (Overall mean score: **4.28 / 5**)

---

## 📚 What I Learned
- Embedded system design using Arduino
- Sensor-based event detection
- Hardware-software integration
- Bluetooth communication
- Applying the Waterfall model to real hardware projects
- Translating real-world safety problems into technical solutions

---

## 🚧 Limitations
- CO₂ cartridge is single-use
- Bluetooth range limited to ~14 meters
- Designed primarily for swimming pool environments
- Not intended for children under 13 years old

---

## 🔮 Future Improvements
- GPS-based location tracking
- Longer wireless communication range
- Support for multiple devices per lifeguard app
- Smaller and more compact device design

---

## 📁 Documentation
Full project documentation is available in the `/documentation` folder.

---

## 👤 Author
**Mart Leonar Berido**  
Bachelor of Computer Science  
Post-Degree Diploma in Cybersecurity  

