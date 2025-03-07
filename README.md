
---

# 🥁 Drum Kit Website  

## 🎶 Overview  
This **Drum Kit** website is an interactive web application that allows users to play drum sounds by **clicking on the drum images** or **pressing specific keys on their keyboard**. The project uses **HTML, CSS, and JavaScript** to provide an engaging experience with sound and animation effects.  

## ✨ Features  
✅ Clickable drum images that play sounds  
✅ Keyboard support for playing drum sounds  
✅ Animated button effects when a drum is played  
✅ Uses pre-saved sound files for smooth playback  
✅ Responsive and lightweight design  

## 🛠️ Technologies Used  
- **HTML** – Defines the structure of the website  
- **CSS** – Provides styling and animations  
- **JavaScript** – Handles user interactions and plays sound files  

## 📁 File Structure  
```
/drum-kit
│── images/           # Drum images
│   ├── crash.png
│   ├── kick.png
│   ├── snare.png
│   ├── tom1.png
│   ├── tom2.png
│   ├── tom3.png
│   ├── tom4.png
│── sounds/           # Drum sound files
│   ├── crash.mp3
│   ├── kick-bass.mp3
│   ├── snare.mp3
│   ├── tom-1.mp3
│   ├── tom-2.mp3
│   ├── tom-3.mp3
│   ├── tom-4.mp3
│── index.html        # Main HTML file
│── styles.css        # CSS file for styling and animations
│── index.js          # JavaScript file for event handling
│── README.md         # Project documentation
```  

## 🚀 Installation and Setup  
1. **Clone the Repository**  
   ```sh
   git clone https://github.com/your-username/drum-kit.git
   cd drum-kit
   ```  
2. **Open the Project**  
   - Open `index.html` in a web browser.  
   - Ensure all sound files and images are in the correct directories.  

## 🎹 How to Use  
### 🖱️ Option 1: Click on the Drums  
- Click on any drum image to hear its sound.  

### ⌨️ Option 2: Use Keyboard Shortcuts  
- Press the following keys to play the corresponding drum sounds:  
  - **W** – Tom 1  
  - **A** – Tom 2  
  - **S** – Tom 3  
  - **D** – Tom 4  
  - **J** – Snare  
  - **K** – Crash  
  - **L** – Kick Bass  

## 📝 Code Breakdown  
### 📌 JavaScript (index.js)  
- **Click Event Listener** – Detects when a drum image is clicked and plays the respective sound.  
- **Keyboard Event Listener** – Detects when a key is pressed and plays the assigned drum sound.  
- **Sound Function (`makeSound`)** – Determines which sound file to play based on user input.  
- **Animation Function (`buttonAnimation`)** – Temporarily applies a "pressed" effect when a drum is played.  

## 🔥 Future Enhancements  
🔹 Add a recording feature to save and replay custom beats  
🔹 Implement volume control and sound effects  
🔹 Improve UI with more interactive animations  

---
