# 🤖 Low-Cost Facial Gesture-Based Robotic Limb

A cost-effective, IoT-enabled system that enables bedridden or limb-impaired individuals to communicate and interact using facial gestures. This project integrates real-time sensing, cloud-based alerting, and a robotic limb controlled through Android accessibility features — offering a novel assistive solution for those with limited mobility.

---

## 🧠 Why This Project?

Thousands of individuals lose limbs each year and cannot afford prosthetic or robotic arms. Additionally, those who are bedridden often:
- Struggle to interact with their environment
- Lack access to high-end assistive technology
- Face challenges in expressing needs or emotions

This project addresses these problems by:
- Using **facial gestures** for control
- Leveraging **IoT platforms** for real-time sensing and alerting
- Building the system using **low-cost, open-source components**

---

## ⚙️ How It Works

1. **Sensing**  
   - Ultrasonic sensors detect when someone approaches the patient.
   - Sensor data is sent via **NodeMCU ESP8266** to **ThingSpeak**.

2. **Notification System**  
   - When a person is nearby, **IFTTT** triggers an alert.
   - The **Shouter App** reads out the alert aloud to the patient.

3. **Gesture Input & App Control**  
   - The patient uses Android’s **Camera Switches** to make facial gestures.
   - These gestures trigger **predefined responses** via an app made in **MIT App Inventor**.

4. **Robotic Limb Control**  
   - Corresponding gestures activate a **servo motor-based prosthetic arm**.
   - The limb performs actions like greeting or signaling needs.

---

## 🔧 Technologies Used

- **NodeMCU ESP8266**  
- **Ultrasonic Sensors**  
- **ThingSpeak** (Cloud data visualization)  
- **IFTTT + Shouter App** (Voice notification)  
- **Android Camera Switches** (Face gesture input)  
- **MIT App Inventor** (Gesture-triggered commands)  
- **Servo Motors** (Robotic limb actuation)

---

## 📝 Springer Publication

This project is published in **Lecture Notes in Electrical Engineering (LNEE, volume 1300)** by Springer Nature:

**Citation:**

> S. Rubeena Grace Tamilarasi, G. Aldrin, Shebin Sam, Roopa Jayasingh, J. Samson, G. Josemin Bala,  
> **"Low-Cost Facial Gesture-Based Robotic Limb"**,  
> *In:* N. R. Shetty et al. (eds) Advances in Communication and Applications,  
> Springer Nature Singapore, 2025.  
> DOI: [10.1007/978-981-96-0165-3_1](https://doi.org/10.1007/978-981-96-0165-3_1)

---

## 📌 Key Outcome

- Enables bedridden individuals to communicate using only facial gestures
- Provides audio alerts when someone enters the room
- Offers pre-defined responses and robotic limb movement
- Designed for **accessibility**, **affordability**, and **real-time interaction**

---

## 👨‍🔬 Authors

- **S. Rubeena Grace Tamilarasi**  
- **G. Aldrin**  
- **Shebin Sam**  
- **Roopa Jayasingh**  
- **J. Samson**  
- **G. Josemin Bala**  
Karunya Institute of Technology and Sciences, Coimbatore, India

# GestureRoboticLimb
