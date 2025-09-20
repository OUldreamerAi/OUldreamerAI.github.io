# Text Fun Translators

A collection of simple web-based tools built with **HTML, CSS, and JavaScript**.  
This website currently includes three different text translators:

1. **Emoji Translator** – Replace words with emojis using a custom dictionary.  
2. **Morse Code Translator** – Convert letters and numbers into Morse code.  
3. **Weird Text Translator** – Transform text into fun Unicode styles (Upside Down, Small Caps, Full Width).  

Live demo: [https://ouldreamerai.github.io/](https://ouldreamerai.github.io/)

---

## Features

### Emoji Translator
- Converts words like `pizza`, `cat`, `love`, `sun` into emojis.  
- Handles punctuation (`.,!?`) correctly.  
- Dictionary is loaded from `text_to_emoji.json` for easy editing and expansion.  
- Keyboard shortcut: `Ctrl/Cmd + Enter` to translate instantly.  

### Morse Translator
- Converts A–Z and 0–9 into International Morse Code.  
- Uses `/` as a separator for spaces between words.  
- Output is displayed instantly.  
- Includes a **Copy to Clipboard** button for convenience.  

### Weird Text Translator
- Provides multiple transformation styles: 
  - **Upside Down** – flips text using Unicode equivalents.  
  - **Small Caps** – converts letters into small capital letters.
  - **Full Width** – converts letters into wide Unicode characters. 
- Clear button to reset input and output.  
- Output updates instantly when a style button is clicked.  

---

## Project Structure
- index.html # Emoji Translator (default homepage)
- morse.html # Morse Code Translator
- weird.html # Weird Text Translator
- text_to_emoji.json # Dictionary of words → emojis
- README.md # Project documentation

---

## Examples

### Emoji Translator
**Input:**
I love pizza and my cat. The sun, moon, and stars are beautiful!

**Output (depends on dictionary):**

I ❤️ 🍕 and my 🐱. The ☀️, 🌙, and ⭐ are beautiful!

---

### Morse Translator
**Input:**

SOS 123


**Output:**


... --- ... / .---- ..--- ...--


---

### Weird Text Translator
**Input:**


hello world


**Output examples:**
- **Upside Down:** `plɹoʍ ollǝɥ`  
- **Small Caps:** `ʜᴇʟʟᴏ ᴡᴏʀʟᴅ`  
- **Full Width:** `ｈｅｌｌｏ　ｗｏｒｌｄ`  

---

## Installation / Usage

1. Clone or download this repository.  
2. Open any of the HTML files in your browser:  
   - `index.html` → Emoji Translator  
   - `morse.html` → Morse Translator  
   - `weird.html` → Weird Text Translator  
3. Or simply visit the **live demo** at:  
   [https://ouldreamerai.github.io/](https://ouldreamerai.github.io/)  

---

## Future Ideas

- Add more weird text styles (Zalgo text, cursive/italic, mirror text).  
- Extend the emoji dictionary with categories (food, animals, emotions).  
- Add audio playback for Morse code.  
- Mobile-friendly refinements.  

---

## License

This project is open-source. You are free to use, modify, and share it.  
