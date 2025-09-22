# Text Fun Translators

A collection of simple web-based tools built with **HTML, CSS, and JavaScript**.  
This website currently includes four different text translators:

1. **Emoji Translator** – Replace words with emojis using a custom dictionary.  
2. **Morse Code Translator** – Convert letters and numbers into Morse code.  
3. **Weird Text Translator** – Transform text into fun Unicode styles (Upside Down, Small Caps, Full Width).
4. **Cursed Text Translator** - Transform text into cursed looking code.

Live demo: [https://ouldreamerai.github.io/](https://ouldreamerai.github.io/)

---


##  Contributions and Credits

This project contains work from multiple sources. Here's a breakdown:

**Created by Me:**  
- **HTML structure and layout** for all translators (`index.html`, `morse.html`, `weird.html`, `cursed.html`)  
  - Built the basic page design with headers, navigation, input textareas, control buttons, and output/result sections.  

- **Custom CSS styling**  
  - Defined fonts, colors, spacing, and responsive rules to create a clean, user-friendly interface.  
  - Styled output areas, buttons, and page backgrounds so each translator has a distinct theme.

- **JavaScript — Emoji Translator (`index.html`)**  
  - Loads an emoji dictionary from `text_to_emoji.json` with a small built-in fallback.  
  - Tokenizes input and performs text → emoji substitutions while preserving punctuation and whitespace.  
  - Copy-to-clipboard and keyboard shortcut support (Ctrl/Cmd + Enter).

- **JavaScript — Morse Translator (`morse.html`)**  
  - Bi-directional conversion (text → Morse and Morse → text) using International Morse mapping.  
  - Normalizes spacing, marks unknown characters with `?`, and displays debug messages.  
  - Plays Morse audio via Web Audio API with adjustable dot timing.

- **JavaScript — Weird Text Translator (`weird.html`)**  
  - Implements Unicode-based transforms: Upside-Down, Small Caps, and Full-Width.  
  - Instant switching via buttons and Clear/Reset functionality for input/output.  
  - Preserves characters with sensible fallbacks for unmapped glyphs.

- **JavaScript — Cursed (Zalgo) Translator (`cursed.html`)**  
  - Generates randomized combining-mark (Zalgo) output using up/mid/down mark sets.  
  - Intensity controlled by a slider with live preview; caps marks per character to avoid freezes.  
  - Copy and Clear controls included.

- **AI-Assisted:**  
  - Code snippets and logic suggestions to improve readability and maintainability and some parts of the (`README.md`).

- **External Resources / References:**  
  - Emoji dictionary file (`text_to_emoji.json`) was created from Unicode Consortium's Emoji 13.0 dataset.

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

### Cursed Text Translator
- Transforms letters and numbers into cursed letters and numbers.
- Uses a slider to determin the cursed level.

---

## Project Structure

index.html # Emoji Translator (default homepage)
morse.html # Morse Code Translator
weird.html # Weird Text Translator
text_to_emoji.json # Dictionary of words → emojis
README.md # Project documentation
weird.html # Text into Cursed Text Translator

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

### Cursed text translator
**Input:**
Scary text

**Output:**
S̠̼̫͓͇̯̘͌͐ͧ̂͌͑c̶ͫ̃̄ͦ̀͋̃ͫá̻̣̝͔͎̫̕͘͜r̷̡̲̲͖͓͕̉̌ͪ̎ͮͩ̉͘͝y̧͉̗͎̰̮̥̺ t̷̢̯̗̘̠͍̔̽̊̉́͢ͅȩ̸̰̽́̀ͥ̓ͨ͐x͉̺̣̩͉͉ͥ̐̑͊̆̆ͧ̏͝t̫̻̜͇͙͔͍̭͉̉̌ͬ̓ͨ͋ͪ̆

---

## Installation / Usage

1. Clone or download this repository.  
2. Open any of the HTML files in your browser:  
   - `index.html` → Emoji Translator  
   - `morse.html` → Morse Translator  
   - `weird.html` → Weird Text Translator
   - `weird.html` → Weird Text Translator 
3. Or simply visit the **live demo** at:  
   [https://ouldreamerai.github.io/](https://ouldreamerai.github.io/)  

---

## License

This project is open-source. You are free to use, modify, and share it.  
