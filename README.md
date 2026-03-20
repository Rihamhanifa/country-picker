# 🎲 Live Random Country Picker Game

A real-time, synchronized web application built for an elimination-style musical chairs game. Developed exclusively for the **Mega Star Sports Club** (Salambaikerny-04) Eid-ul-Fitr Grand Sports Carnival.

## 🚀 Features
* **Real-Time Sync:** Powered by Firebase Realtime Database. No page refresh needed!
* **Two Separate Views:** * `index.html`: A highly visual, dark-themed screen for the audience (Projector/Smart TV).
  * `host.html`: A secure control panel for the game host (Mobile/Laptop).
* **Passcode Protected:** The Host Control panel is locked with a secret passcode to prevent unauthorized access.
* **Cool Animations:** Features a suspenseful shuffling text animation before revealing the eliminated country.

## 🛠️ Tech Stack
* HTML5, CSS3, Vanilla JavaScript
* Firebase Realtime Database (BaaS)
* Hosted on GitHub Pages

## 📱 How to Use
1. **Viewer Screen:** Open `index.html` on the main display (Projector). It will wait for the host's command.
2. **Host Screen:** Open `host.html` on your smartphone. Enter the passcode to unlock the controls.
3. Click **"Reset Game"** to load all 25 countries.
4. Click **"Pick Random Country"** to eliminate a country. The Viewer screen will instantly animate and display the result!

---
*Developed with ❤️ for Mega Star Sports Club.*
