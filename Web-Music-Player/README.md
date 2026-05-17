# 🎵 Vanilla Web Music Player

A sleek, lightweight, and responsive web-based music player built from scratch using only vanilla HTML5, CSS3, and JavaScript (ES6+). No frameworks, no libraries, just pure code.

---

## 🌟 Overview

This project is a simple, yet functional music player. It demonstrates the use of the HTML5 `<audio>` element and how to control it with JavaScript. The UI is custom-styled with CSS3, including Flexbox/Grid for layout and custom-designed player controls.

---

## ✨ Features

* 🎵 **Play, Pause & Stop:** Full control over audio playback.
* ⏩ **Next & Previous:** Easily skip between tracks in the playlist.
* 📊 **Progress Bar:** Clickable and draggable progress bar to seek through the track.
* 🎚️ **Volume Control:** Adjust the volume with a clean vertical or horizontal slider.
* 📜 **Playlist:** Displays the current song list. Clicking a song changes the track.
* 🖼️ **Dynamic UI:** Updates album art, song title, and artist for the current track.
* 📱 **Responsive Design:** Looks and works great on both desktop and mobile devices.

---

## 🧰 Tech Stack

* **HTML5:** Semantic structure, using the `<audio>` element for the core player.
* **CSS3:** Custom styling, animations, Flexbox, and Grid for a fully responsive layout.
* **JavaScript (ES6+):** All logic is handled here, including:
    * DOM Manipulation: To update all UI elements.
    * Event Listeners: For all user interactions (clicks, slider moves, etc.).
    * HTMLAudioElement API: To control playback, volume, and track progress.

---

## 🚀 Getting Started

No installation or build steps are required! Just a modern web browser.

### Installation

1.  Clone this repository:
    ```sh
    git clone
    ```
2.  Navigate to the project directory:
    ```sh
    cd web-music-player
    ```
3.  Open the `index.html` file in your favorite web browser.

> **Pro Tip:** For the best development experience, run it with a local server (like the "Live Server" extension for VS Code) to avoid any potential CORS issues when loading audio files.

---

## ⚙️ How to Add Your Music

Adding your own music is simple:

**Add Audio Files & Album Art:** Place your `.mp3` files and cover image inside the `/songs/(playlist name)` folder.