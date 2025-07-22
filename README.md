# ⌨️ Keyboard Key Checker

A simple web app that displays which **keyboard key** you press, along with its `key`, `keyCode`, and `code` values. Built using HTML, CSS, and JavaScript.

## 🔗 Live Demo

👉 [Check it out here](https://anmol-sharma7011.github.io/KeyBoard-Check/)

## 📸 Preview

When you press any key, you'll see:

- **Key**: The actual key (like "A", "Enter", "Shift")
- **KeyCode**: The numeric code for the key
- **Code**: The physical key location on the keyboard

## 🚀 Features

- Real-time key detection
- Displays key, keyCode, and code
- Simple and responsive UI

## 🛠 Tech Stack

- HTML
- CSS
- JavaScript

## 📁 Folder Structure

KeyBoard-Check/
│
├── index.html # Main HTML file
├── style.css # Styling
├── script.js # Logic for capturing key events
└── README.md # Project documentation


## 🧠 How It Works

- Listens for `keydown` event using `addEventListener`
- Captures the event object to extract `e.key`, `e.keyCode`, and `e.code`
- Updates the HTML dynamically using `innerHTML`

---

## ❤️ Made with love by [Anmol Sharma](https://github.com/anmol-sharma7011)

