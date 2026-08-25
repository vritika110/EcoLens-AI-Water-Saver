# EcoLens-AI-Water-Saver
# EcoLens: On-Device AI Water Conservation

EcoLens is a mobile-first application that transforms a smartphone into an on-device plumbing diagnostic tool. Designed for the iQOO Hackathon (Track 05: Smart Living), it uses computer vision to detect micro-leaks and optimize urban water usage.

## The Problem
Undetected household leaks and unmonitored water usage waste millions of liters annually. Traditional smart home sensors are expensive, cloud-dependent, and introduce latency and privacy concerns.

## The Solution
By leveraging the smartphone's camera and local Neural Processing Unit (NPU), EcoLens performs real-time visual analysis of household plumbing to identify micro-leaks. Data is processed entirely on-device, ensuring user privacy while delivering actionable conservation insights.

## Core Features
*   **AI Hardware Diagnostic:** Camera-based bounding box detection for pipe joints and faucets to estimate drip rates.
*   **On-Device Processing:** Zero-latency inference without sending private home data to the cloud.
*   **Smart Living Analytics:** Dashboard tracking daily water saved and system health.

## Tech Stack
*   **Frontend:** React, Tailwind CSS (Mobile PWA)
*   **Backend:** Python, FastAPI
*   **Machine Learning:** Edge AI / Local vision models (OpenCV, Scikit-learn)

*Our development approach bridges scalable environmental engineering with high-fidelity software dashboards to create a practical, privacy-first smart home solution.*
