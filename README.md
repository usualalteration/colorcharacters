# Extended Color UTF-8 (Concept & Demo)

> **Just to demonstrate my idea**  
> *Maybe we really need color-mixable characters, just like we mix letters to create words.*

---

## 🎨 About The Project

This project explores a visual extension to standard text encoding: **algebraic pigment mixing directly within text**.

Just as letters combine to form words, this prototype introduces base color "characters" (`[Yellow]`, `[Red]`, `[Blue]`, `[Cyan]`, `[Magenta]`, `[White]`, `[Black]`) that can be mixed using simple operators (`+` and `-`). The rendering engine intercepts these formulas in real time and transforms them into a single visual color block/emoji.

### Example Syntax:
- `[Yellow]+[Yellow]+[Red]` ➡️ Light Orange square/dot (`#FFAB00`)
- `[Yellow]+[Yellow]+[Red]-[Yellow]` ➡️ Darker Orange square/dot (`#D84315`)

---

## ✨ Features

- **Extended Character Table:** Quick-access panel for base color tokens and operators.
- **Real-Time Live Preview:** Dynamic pop-up showing the blended color and HEX code while typing.
- **Seamless Chat Interface:** Converts raw formulas into rendered color blocks upon sending, supporting standard text and regular emojis alongside color tokens.
- **Subtractive Color Engine:** Blends RGB/RYB coordinates dynamically.

---

## 🚀 Live Demo & Usage

1. Open `index.html` in any web browser.
2. Select pigments from the character panel or type formulas directly into the chat input.
3. Observe the live preview tooltip.
4. Press **Send** to see your text rendered with dynamic color blocks!

<img width="787" height="957" alt="Screenshot 2026-11-07 alle 16 13 34" src="https://github.com/user-attachments/assets/41820c1e-5c9b-44d5-9c84-acc83acfb2fc" />
