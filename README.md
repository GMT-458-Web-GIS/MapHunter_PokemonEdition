# 📍 MapHunter: Pokémon Edition

**Project:** MapHunter: Pokémon Edition  
**Author:** Nur Sıla Özkan

---

**MapHunter** is a location-based spatial game built with **Leaflet.js** and **Turf.js**. Players take on the role of a Pokémon Trainer, navigating a digital map to track, locate, and catch Pokémon using a proximity sensor system before time runs out.

🚀 **Live Demo:** [Play 🎮 MapHunter](https://gmt-458-web-gis.github.io/MapHunter_PokemonEdition/)

---

<img width="100%" alt="MapHunter Gameplay" src="https://github.com/user-attachments/assets/e3e5c3cc-daac-4c1c-9524-ff1b71f2904b" />

---

## 🎮 Game Mechanics

### 1. The Mission
You have **120 seconds** to reach a target score of **400 points**.  
Your goal is to find hidden Pokémon scattered across the map using your radar and spatial awareness.

### 2. Pokémon Types & Difficulty
Strategies change based on the Pokémon you are hunting:

| Icon | Pokémon | Difficulty | Points | Behavior |
| :---: | :--- | :--- | :--- | :--- |
| <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/official-artwork/1.png" width="30"> | **Bulbasaur** | 🟢 Easy | **+25** | Always visible. Easy to catch. |
| <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/official-artwork/4.png" width="30"> | **Charmander** | 🟠 Medium | **+50** | **Timed!** Disappears after 20 seconds. |
| <img src="https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/official-artwork/94.png" width="30"> | **Gengar** | 🔴 Hard | **+100** | **Hidden & Fast!** Only visible at deep zoom levels. Flees in 10s! |

### 3. Proximity Sensor (Radar)
Since some Pokémon are hidden, you must rely on your sensor:
- **Signal Bar:** Fills up as you get closer to a target.
- **Alert:** The panel glows <span style="color:red">**RED**</span> and shakes when you are within **200m**.
- **Zoom Mechanic:** Rare Pokémon (like Gengar) only appear when you zoom in (Level 17+).

---

## 🕹️ Controls

| Key / Action | Function |
| :--- | :--- |
| **W / ▲** | Move North |
| **S / ▼** | Move South |
| **A / ◄** | Move West |
| **D / ►** | Move East |
| **Left Click** | **CATCH POKÉMON** (Single click only!) |
| **Scroll / Pinch** | Zoom In/Out (Crucial for finding hidden targets) |
| **Mouse Hover** | View coordinates |

> **⚠️ Important:** Double-click zoom is disabled to prevent accidental map jumps. Click once to catch!

---

## 🛠️ Technologies Used

* **[Leaflet.js](https://leafletjs.com/)**: For rendering the interactive map and markers.
* **[Turf.js](https://turfjs.org/)**: For geospatial analysis (calculating distance between trainer and Pokémon).
* **[PokéAPI](https://pokeapi.co/)**: Source for high-quality Pokémon sprites.
* **HTML5 & CSS3**: For the HUD, animations (Pulse, Bounce, Shake), and responsive design.

---

## 🎨 Features

- **Dark Mode Support:** The UI automatically switches to a dark theme when "Night Mode" map layer is selected.
- **Mobile Support:** On-screen D-Pad controls for playing on mobile devices.
- **Dynamic Spawning:** Pokémon spawn in safe locations, avoiding overlapping with the player instantly.
- **Visual Feedback:** CSS animations for walking, catching, and radar alerts.

---
*Gotta Catch 'Em All!* 🧢

---
![geogame](https://github.com/user-attachments/assets/877bedaf-3a8f-4df6-a753-33cde736bd76)

(Previous designed game scheme)
---


 **Clone the repository**
   ```bash
   git clone (https://gmt-458-web-gis.github.io/MapHunter_nursla/)

---
