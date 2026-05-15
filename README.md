🎮 Just Divide

A fun and interactive number puzzle game built using React + Vite, where players strategically place tiles and divide numbers to clear the board and score points.

🚀 Live Demo

(I'll add it very soon)

📌 Features

🎯 Drag & Drop gameplay (Desktop)
📱 Touch Drag support (Mobile)
🧠 Smart merge logic (division rules)
⏱ Countdown timer
⏸ Pause / Resume functionality
♻️ Restart system
🧺 Trash system (limited uses)
📦 Keep tile feature
📊 Score & Level system
❓ Help popup
🔄 Landscape mode enforced for better gameplay

🎮 How to Play

Drag tiles from the tile holder to the grid
If two tiles:
Are equal → both disappear
Are divisible → larger ÷ smaller
Use:
KEEP to store a tile
TRASH to remove a tile
Clear tiles to gain score
Game ends when:
Timer runs out ⏱
No moves left ❌

🛠 Tech Stack

⚛️ React (Hooks)
⚡ Vite
🎨 CSS (Custom UI)
🧠 Game Logic (Custom Algorithms)

📁 Project Structure
just-divide/
├── public/
│   └── assets/
│       ├── images, tiles, backgrounds
├── src/
│   ├── App.jsx
│   ├── App.css
│   ├── main.jsx
├── package.json
├── vite.config.js

⚙️ Installation & Setup

# Clone the repo
git clone https://github.com/your-username/just-divide.git

# Go to project folder
cd just-divide

# Install dependencies
npm install

# Run development server
npm run dev
⚠️ Important Notes

Assets must be inside:

public/assets/

Use paths like:

/assets/image.png
For proper asset handling in Vite, ensure:
// vite.config.js
export default defineConfig({
  plugins: [react()],
  base: "./"
})
📱 Device Support
Platform	Support
Desktop	✅ Drag & Drop
Mobile	✅ Touch Drag
Portrait Mode	❌ Not Supported
Landscape Mode	✅ Recommended

🔥 Future Improvements

🔊 Sound effects
✨ Animations (merge, drop)
🏆 Best score system
📱 Full mobile polish
🎯 Difficulty levels

👨‍💻 Author

Mohammed Salman

📄 License

This project is open-source and free to use.
