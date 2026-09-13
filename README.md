# DRUSHTI 👓

## Obstacle Detection Glasses for the Blind

DRUSHTI is a low-cost wearable assistive technology project designed to help visually impaired people detect nearby obstacles and improve their mobility.

The system uses an ESP32-CAM, ultrasonic sensing and audio feedback to provide real-time obstacle alerts to the user.

---

## 📌 Project Overview

DRUSHTI is designed in the form of smart glasses to provide a hands-free obstacle detection solution for visually impaired people.

The device integrates an ESP32-CAM, ultrasonic sensor, portable power supply and audio feedback system into a wearable spectacle frame.

The ultrasonic sensor measures the distance of nearby obstacles. The ESP32-CAM is used as part of the sensing and processing system. When an obstacle is detected within the defined range, the system provides an audio alert to the user.

---

## 🎯 Problem Statement

Visually impaired people can face difficulties while detecting obstacles during walking and navigation.

Traditional mobility aids such as white canes may have limitations in detecting certain obstacles and providing information about obstacles from a distance.

DRUSHTI aims to provide an affordable, wearable and hands-free solution for obstacle detection with audio feedback.

---

## 💡 Objectives

The main objectives of DRUSHTI are:

- To develop a wearable obstacle detection system.
- To help visually impaired people detect nearby obstacles.
- To provide real-time audio alerts.
- To create a compact and hands-free assistive device.
- To develop an affordable solution for safer mobility.
- To explore the use of embedded systems in assistive technology.

---

## 🧩 System Architecture

The DRUSHTI prototype consists of sensing, processing, power and audio feedback components.

```text
              ┌──────────────────┐
              │    ESP32-CAM     │
              │ Processing Unit  │
              └────────┬─────────┘
                       │
                       ↓
              ┌──────────────────┐
              │    Ultrasonic    │
              │      Sensor      │
              └────────┬─────────┘
                       │
                       ↓
              ┌──────────────────┐
              │ Distance         │
              │ Measurement      │
              └────────┬─────────┘
                       │
                       ↓
              ┌──────────────────┐
              │ Obstacle         │
              │ Detected?        │
              └────────┬─────────┘
                       │
                       ↓
              ┌──────────────────┐
              │   Audio Alert    │
              └────────┬─────────┘
                       │
                       ↓
                    👤 User
