# Text-to-Emoji Translator  

A fun little web app that converts words into emojis!

Live demo: [(https://ouldreamerai.github.io/)]

---

## 🚀 Features
- Type any sentence and press **Translate** (or use `Ctrl/Cmd + Enter`)  
- Words like `pizza`, `cat`, `sun`, `love` automatically turn into emojis  
- Handles punctuation (`.,!?`) correctly  
- Dictionary is loaded from `text_to_emoji.json` so you can easily add more words  

---

## 📂 Project Structure
─ index.html # Main page with UI and script
─ text_to_emoji.json # Dictionary of words → emojis
─ README.md # This file

---

## 🛠 How It Works
1. The app loads `text_to_emoji.json` (word → emoji mappings).  
2. User enters text into the textarea.  
3. The translator replaces matching words with emojis.  
4. Output is shown instantly on the page.  

---

## 📖 Example
Input:
I love pizza and my cat. The sun, moon, and stars are beautiful!


Output (depends on your dictionary):
I ❤️ 🍕 and my 🐱. The ☀️, 🌙, and ⭐ are beautiful!

