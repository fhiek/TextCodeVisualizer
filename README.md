# 🚀 TextCode Visualizer

> **Natural Language to Code Syntax Engine** — an interactive web application that transforms ordinary human text (poetry, prose, philosophy) into a structured code syntax stream with real-time heuristic tokenization, external dictionary configuration, and multiple visualization modes.

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## ✨ Features

- **🧠 Universal Dictionary Engine**: Loads customizable rules, keywords, functions, and suffixes dynamically from external text files in the `dicts/` folder.
- **🎨 6 Developer Themes**: Switch instantly between popular color schemes:
  - *Dracula*
  - *Nord*
  - *Matrix Green*
  - *Cyberpunk Neon*
  - *Monokai*
  - *Solarized Dark*
- **👁️ 3 Visualization Modes**:
  1. **IDE View**: Classic code editor layout with line numbers, gutter, and status bar.
  2. **Matrix Flow**: Cyberpunk stream view powered by an animated HTML5 matrix canvas.
  3. **Bento Cards**: Modern dashboard layout displaying category distribution charts, lexical complexity, and an interactive token inspector.
- **📤 Export & Share**: Copy clean HTML code snippets to clipboard or download standalone HTML files with embedded styles.
- **⚡ Zero Dependencies**: Built with vanilla JavaScript, Tailwind CSS (via CDN), and Lucide icons.

---

## 📂 Project Structure

```text
textcode-visualizer/
├── index.html             # Main application file
└── dicts/
    ├── keywords.txt       # Universal list of keywords (multi-language support)
    ├── functions.txt      # Universal list of functions/actions
    └── suffixes.txt       # Morphological suffixes for heuristic detection
```

---

## 🛠️ Quick Start & Installation

Because external dictionary files are loaded via `fetch()`, running the app requires a local development server (to avoid CORS restrictions on `file://`).

1. Clone or download the repository.
2. Open the project folder in your terminal or IDE (e.g., VS Code).
3. Run a local server (e.g., using Python):
   ```bash
   python3 -m http.server 8000
   ```
4. Open `http://localhost:8000` in your web browser.

---

## 🌐 Live Demo

Hosted on GitHub Pages:  
👉 [https://your-username.github.io/textcode-visualizer/](https://your-username.github.io/textcode-visualizer/)

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.
