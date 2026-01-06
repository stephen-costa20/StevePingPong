<p align="center">
  <a href="https://stephen-costa20.github.io/pingpong/"><img src="https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-brightgreen?style=for-the-badge" alt="Live Demo"></a>
  <a href="https://github.com/stephen-costa20/pingpong/blob/main/LICENSE"><img src="https://img.shields.io/github/license/stephen-costa20/pingpong?style=for-the-badge" alt="License"></a>
  <a href="https://github.com/stephen-costa20/pingpong/commits/main"><img src="https://img.shields.io/github/last-commit/stephen-costa20/pingpong?style=for-the-badge" alt="Last Commit"></a>
  <img src="https://img.shields.io/badge/Built%20With-JavaScript-yellow?style=for-the-badge" alt="Built with JavaScript">
</p>


# ⭐ Ping Pong 🏓

A browser-based Ping Pong game built with **HTML, CSS, and vanilla JavaScript**. Play against a simple AI directly in your browser — no build tools, installs, or dependencies required.

🎮 **Play the live demo:**  
https://stephen-costa20.github.io/pingpong/

<a href="https://stephen-costa20.github.io/pingpong/" target="_blank">
  <img src="assets/pingpong-preview.gif" alt="Ping Pong game preview" width="900" />
</a>

## Game Overview

This project is a lightweight implementation of the classic Ping Pong (table tennis) game using the HTML5 canvas and a simple JavaScript game loop.

It’s designed to be:
- fast to load
- easy to understand
- easy to modify or embed elsewhere

Perfect as a fun side project, learning reference, or interactive demo.



## Features

- 🏓 **Single-player gameplay** against a basic AI opponent  
- 🎯 **Smooth paddle movement** with real-time collision detection  
- 📊 **Score tracking** with win condition  
- 🖱️ **Mouse and touch controls**  
- ⚡ **Runs entirely in the browser** (no backend)



## Controls

- **Move paddle:** Mouse or touch
- **Pause game:** `P`
- **Restart game:** `R`

The AI paddle dynamically tracks the ball to keep gameplay engaging.



## Running Locally

### Option 1: Open directly
Clone the repo and open the HTML file:

```bash
git clone https://github.com/stephen-costa20/pingpong.git
cd pingpong
open index.html
```

Most browsers will run the game immediately.

### Option 2: Run a local server (recommended)

Some browsers restrict behavior when opening local files directly. If that happens, start a simple local server:

```bash
python -m http.server 8000
```

Then open:
```
http://localhost:8000
```



## Project Structure

```
pingpong/
├─ index.html
└─ README.md
```

No frameworks, no bundlers, no build step.



## Built With

- HTML5 Canvas
- Vanilla JavaScript



## Live Demo (GitHub Pages)

This project is deployed using GitHub Pages and is available here:

https://stephen-costa20.github.io/pingpong/
