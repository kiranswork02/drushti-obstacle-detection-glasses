# 👓 DRUSHTI - Obstacle Detection Glasses for the Blind

## 📌 Project Overview

DRUSHTI is a low-cost wearable obstacle detection system designed to assist visually impaired people in detecting obstacles around them.

The system uses an ESP32-CAM and an ultrasonic sensor to detect obstacles and measure their distance. When an obstacle is detected within a certain range, the system provides an audio alert to the user.

The main goal of DRUSHTI is to provide a simple, affordable, hands-free solution for safer mobility of visually impaired people.

---

## 🎯 Objective

The objective of DRUSHTI is to develop an affordable and wearable assistive device that helps visually impaired people detect obstacles and receive real-time audio alerts while moving.

---

## 🚨 Problem Statement

Visually impaired people often face difficulties while navigating their surroundings because they cannot easily identify obstacles in their path.

Traditional mobility aids such as white canes may not provide sufficient information about obstacles at different distances or heights.

DRUSHTI aims to address this challenge by detecting obstacles and providing real-time audio alerts to help the user navigate more safely.

---

## ⚙️ System Overview

DRUSHTI consists of an ESP32-CAM, ultrasonic sensor, battery, buck converter and audio feedback system integrated into a wearable glasses-based design.

The ESP32-CAM is used as the main processing and detection unit, while the ultrasonic sensor measures the distance of obstacles in front of the user.

When an obstacle is detected within the defined range, the system triggers an audio alert through the audio output, allowing the user to respond accordingly.

### 🔧 Hardware Components

- ESP32-CAM
- Ultrasonic Sensor
- Li-ion Battery
- Buck Converter
- Audio Earpiece
- Wearable Glasses Frame

## 🔄 Working Principle

The DRUSHTI system works in the following sequence:

1. **Obstacle Detection**  
   The ESP32-CAM detects objects in the user's surroundings.

2. **Distance Measurement**  
   The ultrasonic sensor measures the distance between the user and the detected obstacle.

3. **Distance Processing**  
   The system evaluates the measured distance to determine whether the obstacle is within the alert range.

4. **Audio Alert**  
   When an obstacle is detected within the defined range, an audio alert is triggered.

5. **User Response**  
   The user receives the audio feedback and can take appropriate action to avoid the obstacle.

### 📊 System Flow

```text
ESP32-CAM
    ↓
Obstacle Detection
    ↓
Ultrasonic Sensor
    ↓
Distance Measurement
    ↓
Distance Processing
    ↓
Audio Alert
    ↓
User Response
