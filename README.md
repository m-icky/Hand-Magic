# ✨ Hand Magic

A real-time interactive hand-tracking visual experience built using **MediaPipe Hands** and **HTML5 Canvas**. This project uses your webcam to detect hand movements and renders dynamic glowing effects, particles, and animated connections between fingers.

---

## 🚀 Features

- 🖐️ Real-time hand tracking (up to 2 hands)
- 🎨 Multiple visual themes:
  - Purple
  - Gold
  - Cyan
  - Rainbow (dynamic hues)
- ✨ Particle effects based on finger motion
- 🔗 Dynamic hand skeleton rendering
- ⚡ Cross-hand energy connections when two hands are detected
- 📷 Live webcam integration
- 🌌 Smooth animations with glow effects

---

## 🛠️ Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)
- Canvas API
- MediaPipe Hands (Google)

CDN used:
https://cdn.jsdelivr.net/npm/@mediapipe/hands@0.4/hands.js

---

## 📂 Project Structure

hand-magic/
│
├── hand-magic.html   # Main application file
└── README.md         # Project documentation

---

## ▶️ How to Run

1. Download or clone the project
2. Open the file:
   hand-magic.html
3. Allow camera permissions
4. Show your hands to the camera

---

## 🎮 Usage

- Move your fingers to create glowing trails
- Use both hands to activate cross-hand energy effects
- Switch themes using the top UI buttons
- Keep hands visible for best tracking performance

---

## ⚙️ Configuration (Optional)

You can tweak detection sensitivity inside the script:

hands.setOptions({
  maxNumHands: 2,
  modelComplexity: 1,
  minDetectionConfidence: 0.65,
  minTrackingConfidence: 0.55
});

---

## ⚠️ Requirements

- Modern browser (Chrome recommended)
- Webcam access
- Internet connection (for MediaPipe CDN)

---

## 🧠 How It Works

1. Webcam feed is captured using getUserMedia
2. MediaPipe detects 21 landmarks per hand
3. Landmarks are mapped to canvas coordinates
4. Custom rendering engine draws:
   - Finger connections
   - Glow effects
   - Particles
   - Cross-hand links

---

## 🔮 Future Enhancements

- Gesture-based controls (pinch, swipe)
- Mobile optimization
- Recording / export feature
- AR effects integration
- Sound-reactive visuals

---

## 📄 License

This project is open-source and free to use for personal and experimental purposes.

---

## 👨‍💻 Author

Developed by Mack 🚀
