# 🌦️ Interactive Water Cycle Learning Experience (For Kids)  

👋 Welcome! This project is a fun and interactive learning tool designed especially for young kids (around 7–8 years old) to help them understand the Water Cycle — how water moves in nature through the sun, clouds, evaporation, and rain!

[![Try it Online](https://img.shields.io/badge/Try_it_Online-p5.js_Editor-blue?style=for-the-badge)]((https://editor.p5js.org/gurvender22192/sketches/QUsCXOAB7)) 
## ✨ Features
- 🌞 Drag the Sun using your hand or mouse to evaporate water
- 💨 Move Clouds using gestures to simulate wind and collisions
- 🌧️ Rain starts when clouds collide
- ⚡ Lightning and thunder effects with visuals and sound!
- 💡 LEDs and real-world effects using Arduino: fan for wind, sprinkler for rain
- 🐄 Animated cows walk across the screen to make it visually fun
- 🎵 Calming background music and nature sounds

## 🧠 What Will Kids Learn?
This simulation visually teaches:
- **Evaporation** – sun heats up water
- **Condensation** – vapor forms clouds
- **Precipitation** – clouds collide → rain
- **Collection** – water gathers in lakes, restarting the cycle

## 🛠️ Tech Stack
| Technology | Purpose |
|------------|---------|
| p5.js | Canvas drawing and animation |
| ml5.js | BlazePose model for hand/body tracking |
| JavaScript | Logic and interactions |
| Arduino + Serial Communication | Connects fan, LEDs, and sprinkler |
| Images/Sounds | To make the environment immersive |

## 💡 How to Run the Project

### ✅ Option 1: Run Online (Easy)
1. Go to the project: [p5.js editor]([YOUR_P5_EDITOR_LINK_HERE](https://editor.p5js.org/gurvender22192/sketches/QUsCXOAB7))
2. Click the ▶️ Play button
3. Allow camera access when prompted (for hand detection)
4. Interact by moving your hand to drag the Sun or Clouds!

### 💻 Option 2: Run Locally

git clone https://github.com/gurvender02/Interactive-System-water-cycleSmulation-

Open index.html in your browser

Make sure the camera is enabled

(Optional) Hardware Integration:

Upload the provided Arduino code to your board

Connect LEDs, fan, and water pump

Connect Arduino to your computer via USB

Use p5.serialport to enable communication

🔌 Hardware Integration (Optional)
Action	Real-World Effect
☀️ Dragging the Sun	Fan turns ON (wind)
🌫️ Vapor rising	LED lights ON
☁️ Clouds moving	Wind sound + fan
⚡ Cloud collisions	Thunder LEDs ON
🌧️ Rain starts	Sprinkler turns ON
Communication is done using serial signals from p5.js to Arduino.

📂 File Structure
## 📂 File Structure
```
/project-folder
│
├── index.html          # Entry point
├── learn.js            # Main p5.js code
├── ocean.mp3           # Background music
├── vapour.mp3          # Evaporation sound
├── rain.mp3            # Rain sound
├── cloud1.png          # Cloud image
├── cloud2.png          # Cloud image
├── moutain.png         # Mountain image
├── crow.gif            # Cow animation
└── waterCycle.ino      # Optional Arduino code
```

🎯 Why This Project?
We believe learning should be fun and interactive, especially for children. This simulation blends science, visuals, sound, real-world hardware, and motion tracking to create a unique way of understanding the water cycle.

🙌 Made With Love
Designed and developed by Gurvender Singh ❤️
For learning, creativity, and curious young minds.
