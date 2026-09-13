# DRUSHTI 👓

## Obstacle Detection Glasses for the Blind

DRUSHTI is a low-cost wearable assistive device designed to help visually impaired people detect obstacles and improve their mobility.

The system combines an ESP32-CAM, ultrasonic sensing and audio feedback to detect obstacles and provide real-time alerts to the user.

---

## 📌 Project Overview

DRUSHTI is designed in the form of smart glasses to provide a hands-free obstacle detection solution for visually impaired people.

The device is mounted on a spectacle frame and contains sensing, processing and power components. An ultrasonic sensor measures the distance of nearby obstacles, while the ESP32-CAM is used as part of the sensing and processing system. When an obstacle is detected within the defined range, an audio alert is provided to the user.

---

## 🎯 Problem Statement

Traditional white canes and other mobility aids can have limitations when detecting obstacles in certain situations.

There is a need for an affordable, wearable and hands-free assistive device that can help visually impaired people identify obstacles and receive timely alerts.

---

## 💡 Objective

The main objectives of DRUSHTI are:

- To design an affordable wearable obstacle detection device.
- To help visually impaired people detect nearby obstacles.
- To provide real-time audio alerts.
- To develop a compact and hands-free solution.
- To improve mobility and obstacle awareness.

---

## ⚙️ System Overview

The main hardware components used in the DRUSHTI prototype are:

- ESP32-CAM
- Ultrasonic Sensor
- Li-ion Battery
- Buck Converter
- Audio Earpiece
- Spectacle Frame

---

## 🔧 Hardware Components

| Component | Purpose |
|-----------|---------|
| ESP32-CAM | Camera-based sensing and system processing |
| Ultrasonic Sensor | Measures the distance of nearby obstacles |
| Li-ion Battery | Provides portable power |
| Buck Converter | Regulates the required voltage |
| Audio Earpiece | Provides audio feedback to the user |
| Spectacle Frame | Provides the wearable structure |

---

## 🔄 Working Principle

The system works through the following steps:

1. The device is powered using a rechargeable Li-ion battery.
2. The ESP32-CAM and ultrasonic sensor become active.
3. The ultrasonic sensor measures the distance between the user and nearby obstacles.
4. The system checks the detected distance against the defined threshold.
5. When an obstacle is detected within the required range, an audio alert is triggered.
6. The user receives the alert through the audio earpiece.
7. This helps the user become aware of obstacles while moving.

### Working Flow

```text
        ┌─────────────────┐
        │   ESP32-CAM     │
        │ Sensing System  │
        └────────┬────────┘
                 ↓
        ┌─────────────────┐
        │   Ultrasonic    │
        │     Sensor      │
        └────────┬────────┘
                 ↓
        ┌─────────────────┐
        │ Distance        │
        │ Measurement     │
        └────────┬────────┘
                 ↓
        ┌─────────────────┐
        │ Obstacle        │
        │ Detected?       │
        └────────┬────────┘
                 ↓
        ┌─────────────────┐
        │   Audio Alert   │
        └────────┬────────┘
                 ↓
        ┌─────────────────┐
        │     User        │
        └─────────────────┘
