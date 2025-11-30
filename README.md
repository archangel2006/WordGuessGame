# WordGuessGame
> Finivesta WebDev Task

A simple and interactive browser-based word guessing game built using **HTML, CSS, and JavaScript**.  
The player tries to guess a randomly selected programming-language name one letter at a time.

---

## 🎮 Features
- Random word selection from a predefined list  
- Shows live progress of the guessed word (`_ _ t h o n`)  
- Prevents duplicate guesses  
- Alerts for empty input  
- Instant win detection when all letters are guessed  
- Fully client-side, no backend required

---

## 🛠️ Tech Stack
- **HTML** – Page structure  
- **CSS** – Basic styling  
- **JavaScript** – Core game logic (DOM updates, input validation, gameplay)

---

## 📁 Project Structure
```bash
WordGuessGame/
│── index.html        # UI layout
│── style.css         # Styling
│── script.js         # Game logic
│── README.md         # Project documentation
```
---

## 📌 How It Works

- A random word is selected from a list in script.js
- User enters letters one by one
- Correct letters reveal themselves in the display
- Once all letters are guessed, the game shows a success alert
