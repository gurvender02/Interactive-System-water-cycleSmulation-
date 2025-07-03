🌦️ Interactive Water Cycle Learning Experience (For Kids)
👋 Welcome!
This project is a fun and interactive learning tool designed especially for young kids (around 7–8 years old) to help them understand the Water Cycle — how water moves in nature through the sun, clouds, evaporation, and rain!

It’s built using p5.js and ml5.js, with support for real body movement tracking (using BlazePose) and hardware triggers (like a fan and sprinkler) to create a real-world, playful experience.
Perfect for schools, exhibitions, or home learning!

✨ Features
🌞 Drag the Sun using your hand or mouse to evaporate water.

💨 Move Clouds using gestures — simulate the wind and cloud collisions.

🌧️ Rain starts falling when clouds collide.

⚡ Lightning and thunder effects with visuals and sound!

💡 LEDs and physical effects using Arduino: triggers a real fan for wind and sprinkler for rain.

🐄 Animated cows walk across the screen to make it visually fun.

🎵 Calming background music and nature sounds.

🧠 What Will Kids Learn?
This app visually teaches:

Evaporation (sun heats water)

Condensation (vapor forms clouds)

Precipitation (clouds collide → rain)

Water collection in lakes and how the cycle repeats

🛠️ Tech Stack
Tech	Usage
p5.js	Canvas drawing, interaction
ml5.js	BlazePose for body pose detection
Arduino + Serial Communication	To control real hardware: fan, LED, water pump
JavaScript	Main programming language
GIFs, Sounds, Images	For animation and realism

💡 How to Run the Project
Option 1: Run Online (Recommended for Non-tech users)
Open this project on editor.p5js.org.

Upload all the files (sketch.js, images, sound files, etc.)

Click the "Play ▶️" button.

Allow camera access when prompted (for pose detection).

Option 2: Run Locally
🧑‍💻 This option is for those with basic setup knowledge.

Download the full ZIP or clone the repo:

bash
Copy
Edit
git clone https://github.com/yourusername/water-cycle-kids.git
Open index.html in your browser.

Make sure the camera is enabled (used for hand tracking).

To use the hardware:

Upload the Arduino code to your board.

Connect the hardware components (fan, pump, LEDs).

Connect Arduino to your computer using USB.

Open a serial communication bridge in your code (using p5.serialport).

🔌 Hardware Integration (Optional but Awesome!)
You don’t need the hardware, but it makes it super fun!

Trigger	Real-World Effect
☀️ Sun dragged down	Fan turns ON (wind)
🌫️ Vapor rises	LED lights ON
☁️ Clouds dragged	Fan + wind sound
⚡ Thunder strikes	LED lightning effect
🌧️ Rain starts	Sprinkler ON

All these actions are controlled by sending signals from p5.js to an Arduino via serial communication.

📦 File Structure
bash
Copy
Edit
/project-folder
│
├── sketch.js               # Main p5.js code
├── index.html              # Entry point
├── /assets
│   ├── ocean.mp3           # Background music
│   ├── vapour.mp3          # Evaporation sound
│   ├── rain.mp3            # Rain sound
│   ├── cloud1.png          
│   ├── cloud2.png
│   ├── moutain.png
│   ├── crow.gif            # Cow animation
├── /arduino-code
│   └── waterCycle.ino      # Arduino code (optional)
🎯 Why This Project?
We believe learning should be playful, especially for children. This interactive simulation brings the science of water cycles to life using visuals, sound, movement, and even real-world elements like water sprayers and fans!

📸 Screenshots / Preview (optional)
Add here GIFs or images of your working system if available!

🙌 Made With Love
Created as an educational and engaging project to blend coding, science, hardware, and fun ❤️
By: Gurvender Singh

