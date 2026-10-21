# 🛺 Periwinkle E-Bike Dashboard

A custom, mobile-friendly web application designed specifically for the **Wayne's E-Bikes "Periwinkle" 60V 20Ah Electric Tricycle**. 

This app replaces the standard paper charging chart and adds smart tools for tracking battery health, planning trips, and recording GPS rides. It is built to be installed directly to your phone's home screen and works completely offline.

## ✨ Features

### ⚡ Charge & Range Tab
*   **Voltage to Percentage:** Type your current voltage (e.g., 58.5V) to get an accurate battery percentage based on the official 60V chart.
*   **Smart Charging Timer:** Calculates exactly how long you need to charge. It includes the mandatory **30-minute resting period** before you ride.
*   **Background Timer:** The timer saves to your phone's memory. If you close the app, it keeps counting down.
*   **Battery Health Bar:** A visual guide based on the manual's rules (Green = Perfect time to charge at 40-70%, Red = Do not charge).
*   **Trip Planner:** Enter a distance to see if you have enough battery to make it. Includes a **"Round Trip"** toggle for return journeys.
*   **Heavy Load Toggle:** Recalculates your estimated range if you are carrying heavy cargo (up to 300kg).

### 📍 GPS & Odometer Tab
*   **Lifetime Odometer:** Permanently tracks your total kilometers driven (saved forever in your browser).
*   **Live GPS Tracker:** Tracks your exact current trip distance and speed. Includes a **Pause/Resume** feature for when you are making stops.

### 🎨 Design
*   **Two Themes:** A standard "Dark Slate" theme, and a pure black **OLED Theme** (saves battery on modern phones).
*   **PWA Ready:** Can be added to your phone's home screen to look and feel like a native app.

## 📱 How to Install on Your Phone

1. Open your GitHub Pages link in your mobile browser (Chrome or Safari).
2. **On iPhone (Safari):** Tap the "Share" icon at the bottom, scroll down, and select **"Add to Home Screen"**.
3. **On Android (Chrome):** Tap the three dots in the top right corner, and select **"Add to Home screen"** or **"Install App"**.

## 🛠️ Built With
*   HTML5
*   CSS3 (Custom properties for dynamic theming)
*   Vanilla JavaScript (No external libraries or frameworks used)
*   HTML5 Geolocation API

## 📊 Data Source
The voltage and charging calculations are based on the official Wayne's E-Bikes **60V 20Ah Charging Guide**. 

*Note: The estimated range (20-30km) is based on the manufacturer's specifications for a 2000W motor under normal load. Real-world range may vary based on rider weight, terrain, and weather.*

## 📄 License
This project is open-source and free to use. Feel free to fork it and modify it for your own e-bike model!
