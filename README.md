# ORTHO

## Overview

ORTHO is a modern web-based translation and dictionary application. It provides an intuitive interface for translating text between multiple languages and retrieving word meanings, with special support for the Bengali language and a stylish, responsive design. ORTHO is built using only HTML, CSS, and JavaScript (all contained in a single HTML file), making it highly portable and easy to use.

---

## Features

### 1. Multi-Language Translation
- **Supports numerous major languages:** Bengali, English, Spanish, French, German, Italian, Portuguese, Russian, Japanese, Korean, Chinese, Arabic, Hindi.
- **Auto-detect input language option.**
- **Uses Lingva Translate API:** Translates typed or spoken text.

### 2. Bengali Language Support
- **Special Bengali font:** "Noto Sans Bengali" ensures clear rendering.
- **Auto-applied styles for Bengali selection.**
- **Seamless switching between English and Bengali (and other supported languages).**

### 3. Modern UI/UX
- **Beautiful glassmorphism panels.**
- **Dark mode & light mode:** Auto-detects system preference, can be toggled manually.
- **Intro animation for visual appeal.**
- **Fully responsive:** Optimized for desktop, tablet, and mobile usage.
- **Mobile navigation bar.**
- **Stylish headers, buttons, and action panels.**
- **Glow & depth effects with shadows and gradients.**

### 4. Input Options
- **Manual text input.**
- **Voice recognition:** Uses browser’s built-in speech recognition (if supported).
- **Automatic character count display.**
- **Quick clear button for input.**

### 5. Output Options
- **Translated text displayed instantly.**
- **Copy translation to clipboard.**
- **Listen to translation via text-to-speech.**

### 6. Dictionary/Meanings Lookup
- **Retrieve word meanings for single words using a simulated API (demo purpose, extendable for real APIs).**
- **Word meanings grouped by grammar type (noun, verb, adjective etc.).**
- **Show/hide word meanings panel toggle.**

### 7. Accessibility
- **Keyboard shortcuts:** `Ctrl+Enter` to translate.
- **Voice features:** Both speech-to-text & ability to listen to translations.

### 8. User Guidance
- **Help button:** Displays instructions.
- **Notifications for operations:** Success, error, info alerts in stylish popup style.

---

## Technology & Architecture

- **Frontend only:** A single HTML file with embedded CSS and JavaScript.
- **No backend required.**
- **Primary translation via Lingva API:** Calls `https://lingva.ml/api/v1/[src]/[dest]/[text]`.
- **Word meanings via mock dictionary (can be updated for production).**
- **Modern styling with CSS variables, transitions, and keyframe animations.**
- **Font loading via Google Fonts (Inter & Noto Sans Bengali).**
- **No external JS frameworks or dependencies.**

---

## How the Application Works

### 1. Startup
- Displays animated "ORTHO" logo.
- Switches to main app interface after intro animation.

### 2. Main Workflow

#### a) Input Panel:
- Select source language (or auto-detect).
- Enter text manually or use the voice input button.
- View live character count.
- Clear text option.

#### b) Action Bar:
- Swap source and target languages instantly.
- Click **Translate** to get output.

#### c) Output Panel:
- Select target language.
- See translation.
- Listen to translated text.
- Copy result.
- Toggle "Word Meanings" panel for definitions.

#### d) Word Meanings:
- Enter a single word in input and use "Show Meanings" to view dictionary results.

#### e) Additional Navigation:
- Mobile nav button for quick access on mobile devices.

---

## Customization & Extending

- **API endpoints for translation/meanings:** Easily replace Lingva and Google Translate mock logic with your preferred services.
- **Add more languages:** Update the `<option>`s in both source and target language selectors.
- **Styling:** All theme colors are CSS variables for effortless customization.

---

## Screenshots

> _For best results, open ortho.html in your browser and test the lively UI, dark/light theme, translation, pronunciation, and meanings features._

---

## Getting Started

1. **Clone the repository:**
   ```
   git clone https://github.com/Sabirtanvir12/ortho.git
   ```

2. **Open the application:**
   - Simply open `ortho.html` in any modern browser.

---

## Credits

- [Lingva Translate API](https://lingva.ml/)
- [Google Fonts: Inter & Noto Sans Bengali](https://fonts.google.com/)
- Designed and developed by [Sabirtanvir12](https://github.com/Sabirtanvir12)

---

## License

[MIT](LICENSE)
