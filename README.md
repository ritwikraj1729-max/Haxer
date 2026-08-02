# Hacker Typer – Desktop Windows

A fake hacker‑vibe terminal simulator that feels like a real desktop environment.  
Open multiple windows, drag and resize them, toggle auto‑typing, and watch the code scroll by.


---

## 🚀 Overview

This is a **single HTML file** that turns your browser into a hacker’s playground.  
It looks like a retro terminal, but every keystroke (or mouse click) reveals **fake code**, **binary streams**, or **shell commands**.  
Unlike a traditional single‑window terminal, this version runs **multiple draggable, resizable windows** – just like real applications on a desktop.

---

## ✨ Features

- **Multi‑window desktop** – create as many terminal windows as you want.
- **Drag, resize, minimize, maximize, and close** windows – exactly like a real OS.
- **Taskbar** – shows all open windows, click to restore/switch.
- **Auto‑Typing mode** – turn it on and watch the terminal type by itself.
- **Dynamic loading effects** – fake progress bars, network scans, compilation logs injected randomly.
- **Glitch flashes** – occasional CRT‑style visual glitches for extra atmosphere.
- **Three content modes** – Code (C, Python, JS, etc.), Binary, Terminal commands.
- **Five colour themes** – Classic Green, Blue, Red, Amber, White.
- **Adjustable speed & font size** – real‑time controls.
- **Keyboard sound** – optional click sound synthesized with Web Audio API.
- **Fullscreen support** – click the button or press F11.
- **No dependencies, no storage** – everything runs locally, no data is saved.

---

## 🖥️ Getting Started

1. Download or copy the `index.html` file.
2. Open it in any modern browser (Chrome, Firefox, Edge, Safari).
3. Start typing anywhere (or just click inside a terminal window).

That’s it! No server, no installation, no external libraries.

---

## 🎮 Usage Guide

### Toolbar (top)

| Control        | What it does |
|----------------|-------------|
| **Mode**       | Switch between `Code`, `Binary`, and `Terminal` content. |
| **Theme**      | Change the colour theme instantly. |
| **Speed**      | How many characters appear per keystroke. |
| **Font**       | Change the terminal font size. |
| **Auto‑Type**  | Toggle automatic typing (great for a hands‑off demo). |
| **Sound**      | Enable/disable keyboard click effects. |
| **Fullscreen** | Enter fullscreen mode. |
| **Clear**      | Reset the active window’s content. |
| **+ New Window** | Open a fresh terminal window. |

### Window Management

- **Drag** a window by its title bar.
- **Resize** by dragging any edge or corner.
- **Minimize** ( – ), **Maximize** ( □ ), **Close** ( ✕ ) using the buttons in the title bar.
- **Taskbar** at the bottom – click any window’s button to bring it to the front and restore it if minimized.

### Keyboard

- **Any key** (except modifiers like Ctrl/Alt) reveals more content in the active window.
- **Escape** exits fullscreen.
- Pressing any key while **Auto‑Type** is on **turns it off**, so you can take over manually.

---

## 🎨 Themes

The terminal appearance can be changed instantly via the **Theme** dropdown:

| Theme   | Colour   |
|---------|----------|
| Green   | #33ff33  |
| Blue    | #33befd  |
| Red     | #ff3b3b  |
| Amber   | #ffb000  |
| White   | #e8e8e8  |

The glow, cursor, and shadows all adapt automatically.

---

## 🛠️ Customization

All visual settings are adjustable **in real‑time** and **not saved** (no local storage).  
If you want to change defaults, edit the CSS variables in the `<style>` block or modify the `THEMES` object in the script.

To permanently add or change the fake content, look for:

- `CODE_SNIPPETS` – the code blocks.
- `TERMINAL_COMMANDS` – fake shell sessions.
- `generateBinaryChunk()` – binary streams.
- `generateLoadingSequence()` – the progress‑bar fake loading screens.

---

## 🧠 Technical Notes

- **Pure HTML, CSS, and vanilla JavaScript** – no frameworks, no build step.
- **Web Audio API** used for the click sounds (no audio files).
- **CSS animations** for scanlines, blinking cursor, and glitch effects.
- **Responsive** – works on desktops, tablets, and (with reduced features) phones.

Because it uses **no localStorage**, settings are not remembered between sessions.  
If you want persistence, a few lines can be added – but the current version is “privacy‑first”.

---

## 📄 License

MIT – do whatever you want with it. Have fun!

---

*Happy fake hacking!* 💻🔥
