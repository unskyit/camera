<div align="center">

# 📸 Iris Camera
**A Premium, Privacy-First Web Camera Experience**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![Vanilla JS](https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge&logo=webrtc&logoColor=white)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)](#)

</div>

<br/>

Welcome to **Iris Camera**, a beautifully crafted, offline-first web application that turns any browser into a high-performance camera. Built with a cozy, minimalist glassmorphic aesthetic and a deeply robust Vanilla JavaScript architecture, Iris ensures that your moments are captured with zero latency and absolute privacy. 

## 📐 The Architecture: Client-Side Perfection

By avoiding heavy component frameworks, this application achieves instant load times and seamless hardware interaction. 

* **Native WebRTC API:** Directly hooks into the device's media stream for hardware-accelerated video capture, frame extraction, and live filtering without lag.
* **100% Offline & Private:** Zero server uploads, zero telemetry, and no backend databases. Every photo is processed, rendered, and downloaded entirely locally on the user's device.
* **Vanilla Architecture:** Built purely with structural HTML, advanced CSS3, and highly efficient Vanilla JS to eliminate dependency bloat and complex state management overhead.
* **Premium Glassmorphic UI:** Features a cozy, ethereal interface with dynamic blur effects, smooth state transitions, and carefully weighted drop shadows that make the browser feel like a native premium OS application.

## ✨ Core Features

* **Instant Capture:** Zero-shutter-lag photography utilizing raw video track data.
* **Camera Switching:** Seamlessly toggle between front-facing and environment (rear) lenses on mobile devices.
* **Local Storage Optimization:** Instantly converts raw canvas data into optimized image formats for immediate, secure downloading.
* **Responsive Viewfinder:** The viewfinder dynamically scales and crops to ensure a perfect aspect ratio across mobile, tablet, and desktop screens.

## 🚀 Quick Start & Deployment

Because Iris is an offline-first, client-side application, it requires zero build steps, compilers, or local backend servers.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/unskyit/iris-camera.git
   ```
2. **Launch:**
   Simply open `index.html` in any modern web browser.
3. **Permissions Note:**
   For the WebRTC API to function, browsers require the site to be served over `HTTPS` or `localhost`. If testing on a mobile device on your local network, use a lightweight local server (like VS Code's Live Server) and access it via your local IP.

