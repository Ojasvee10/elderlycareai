# AI-Powered Elderly Care System

## Problem
Elderly individuals living alone often lack real-time monitoring for health anomalies and fall incidents, leading to delayed emergency response.

## Solution
An AI-powered system that monitors health vitals and detects falls in real time, triggering automated alerts for caregivers and emergency contacts.

## Key Features
- Fall detection using sensor-based ML models
- Health anomaly detection (heart rate, movement patterns)
- Automated SMS alerts for emergencies
- Fast patient history retrieval

## Architecture
Sensor Data → ML Models → Flask API → SQLite Database
↓
SMS Alert Service

## Why These Choices?
- **TensorFlow** for reliable ML model deployment
- **Flask** for lightweight, real-time API handling
- **SQLite** for fast read operations in low-to-medium scale systems
- **Twilio API** for near-instant emergency notifications

## Results
- Achieved **92% true positive rate** in fall detection
- Triggered alerts within **8 seconds** of anomaly detection
- Optimized queries to fetch **500+ records in 0.3 seconds**

## Tech Stack
Python, Flask, TensorFlow, SQLite, OpenAI APIs, Google Cloud

## Future Improvements
- Wearable device integration
- Predictive health trend analysis
- Mobile app for caregivers

