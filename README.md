# 🎮 Pod To Home
A side-scrolling platformer, take control of an astronaut attempting to reach the last Escape pod in a space station filled with hazards.

## 🛠️ Technology
- `Lua`
- `Pico-8`

## 🚀 Features
- **Platformer movement & collision system -** side scrolling ****player movement and physics.
- **Timed laser system -** lasers alternate on a fixed interval.
- **Tile-based environmental hazards** - lava tiles trigger a lose state on contact.
- **Win & lose state handling** - laser tiles only trigger the lose state when the active flag is enabled. Reaching an active terminal triggers a win state.
- **Level reset/Main Menu -** players can reset the level after losing, transitioning back to the main menu screen.

## 🧠 The Process
I wanted to make a project where I would  improve upon on a basic platformer system. I began by following a tutorial online for making the core movement of the player and the collision physics of the level. 

With the platforming system set up, I worked on and implemented the hazards. The first hazard is a laser that alternates on and off every second; this gives some leeway if the player accidentally lands into the laser. The second hazard is a floor-level platform hazard styled as lava, which spans multiple tiles. 

Next, I worked on the win and lose states to complete the game loop. The win condition is represented as a console terminal that, when the player walks up to it, causes the game to display a win screen. For the lost state, I designed it just like the console terminal, where if the player comes into contact with any of the hazards, it will trigger a lose screen and a button prompt to reset the level. 

Because the lasers alternate, I added logic for the laser that only the player will get hit with the lose condition, only if the laser is on. This is my first time trying to implement a main menu as well, so players could start the game properly rather than jumping straight into gameplay.

## 📦 Running the Project
1. Clone or download the repository
2. Open the project cartridge in your PICO-8 application (that being said, you need to have the PICO-8 Fantasy Console). Launch it to start playing.
3. Controls: Use **arrow keys** for movement, **“X”** key to jump. Navigate the level reaching the end goal without.

## 🖼️ Preview
https://github.com/user-attachments/assets/6a7e8ed7-19f3-4f4a-b3e9-5e4238e11562
