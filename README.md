# ⏳ TeamLegacy Time Capsule 🚀

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Three.js](https://img.shields.io/badge/Three.js-black?style=for-the-badge&logo=three.js&logoColor=white)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-success?style=for-the-badge)

> **Create a sealed digital message, lock it until a future date, and save it as a standalone capsule file.**

Welcome to the **TeamLegacy Time Capsule**. This web application allows you to write a message to your future self (or a friend), lock it behind a specific date and time, and export it as a completely independent, self-contained HTML file. 

The exported file acts as the physical "capsule." When you open it, you are greeted with a sci-fi countdown timer. Only when the clock strikes zero will your message finally be revealed!

---

## ✨ Features

* **🧬 Self-Replicating Code:** The main app actually writes and downloads a *brand new*, custom HTML application containing your sealed message.
* **🌌 Futuristic 3D Interface:** Built with `Three.js`, the app features an immersive, rotating 3D wireframe torus knot, an icosahedron, a starry background, and retro CRT scanlines.
* **⏱️ Live Countdown:** The exported capsule features a real-time, ticking countdown clock calculating the exact days, hours, minutes, and seconds until unlock.
* **⚡ 100% Serverless:** Everything happens locally in your browser. No databases, no backends, no sign-ups. Your data never leaves your computer.
* **📱 Responsive Design:** Sleek, glass-morphism UI that looks stunning on desktops, tablets, and phones.

---

## 📸 Sneak Peek

*(💡 Pro-Tip: Add a GIF or screenshot of the glowing 3D interface and countdown timer here!)*

![Time Capsule UI](https://via.placeholder.com/800x400/061018/5bd0ff?text=Add+Screenshot+of+Time+Capsule+Here)

---

## 🛠️ How It Works (The Magic)

1. **Write:** Enter a title and write your heartfelt (or hilarious) message.
2. **Lock:** Pick a specific date and time in the future.
3. **Export:** Click **"Save Time Capsule"**.
4. **The Magic:** The app takes your message, encodes it (`Base64`), injects it into a customized HTML template, and downloads it to your computer.
5. **Wait:** Open your newly downloaded file. You will see a beautiful countdown screen. 
6. **Reveal:** Once the current time surpasses the unlock time, the countdown shatters and your message is revealed!

---

## ⚠️ Sentimental Security Notice

*This is a "sentimental" time lock, not a cryptographic vault!* 

The message is obfuscated using Base64 encoding to prevent accidental reading if you open the file in a text editor. However, anyone with basic coding knowledge could decode it early if they really wanted to. It operates on the **honor system**—designed for nostalgia, keepsakes, and fun!

---

## 🏃‍♂️ How to Run Locally

Because this project is delightfully simple and has zero build steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/2ndChances520/teamlegacy-time-capsule.git
Navigate to the folder:
code
Bash
cd teamlegacy-time-capsule
Open the App:
Simply double-click the index.html file to open it in your browser.
Note: An active internet connection is required the first time you load the page so it can fetch the Three.js library for the background animations.
🤝 Contributing
Want to add stronger encryption (like AES-256), new 3D background effects, or multiple message payloads? Contributions are welcome!
Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
<div align="center">
<p style="color: #5bd0ff;"><b>Leave your legacy. Send a message to the future. 🕰️✨</b></p>
</div>
