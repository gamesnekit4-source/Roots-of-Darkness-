# ⚔️ Roots of Darkness: Echoes of the Fallen Kings

**Roots of Darkness: Echoes of the Fallen Kings** is a dark fantasy roguelike game where players explore procedurally generated dungeons, fight monsters and bosses, collect artifacts, and build powerful combinations of items and abilities.

Every run is a new challenge. Rooms, enemies, items, and ability combinations encourage players to adapt their strategies, experiment with equipment, and discover their own playstyle.

The project draws inspiration from dark fantasy worlds and gameplay mechanics commonly found in roguelikes, dungeon crawlers, and action RPGs.

---

## 📖 Table of Contents

- [About the Game](#-about-the-game)
- [Key Features](#-key-features)
- [Playable Characters](#-playable-characters)
- [Items and Builds](#-items-and-builds)
- [Bosses and Progression](#-bosses-and-progression)
- [Creative Mode](#-creative-mode)
- [Installation and Launch](#-installation-and-launch)
- [Controls](#-controls)
- [Save System](#-save-system)
- [Technologies](#-technologies)
- [Future Plans](#-future-plans)

## 🌑 About the Game

The world has fallen under the influence of ancient powers. Twelve floors stand between the hero and the final challenge, with each level becoming more dangerous than the last.

Players must explore rooms, fight enemies, discover treasures, purchase useful items from merchants, and defeat powerful bosses. Death is part of the journey: every new run offers an opportunity to experiment with different combinations of items and abilities.

The main objective is to survive all 12 floors, defeat the final boss, and test your skills in increasingly difficult New Game+ cycles.

## ✨ Key Features

- **12 floors and multiple themed locations**, each with different enemies and challenges.
- **Dungeon exploration:** combat rooms, treasure rooms, traps, merchants, and boss encounters.
- **Real-time combat** featuring dodging, different attacks, and active abilities.
- **A wide variety of items and artifacts** that change your stats and playstyle.
- **Item rarity tiers** with different levels of value and power.
- **Mini-bosses** that can unexpectedly appear in eligible rooms.
- **Reward chests** after combat encounters.
- **Talent tree:** upgrade your character during a run using red crystals.
- **Creative Lab:** experiment with items, enemies, bosses, and character stats.
- **New Game+:** replay the game against stronger enemies.
- **Minimap** for navigating explored rooms.
- **Save system** with export and import functionality.
- **Sound effects and procedurally generated music.**

## 🧙 Playable Characters

The game features several characters with different abilities and approaches to combat.

| Character | Special Feature |
|---|---|
| Wanderer | A standard hero for learning the game |
| Architect | Customizable stats and item capacity |
| The Last One | Starts with 1 HP, a random buff, and additional items |
| Bandit | Uses a separate health system based on coins dropped by enemies |
| Shadow Marksman | Higher speed and damage, but limited vision |
| Alex | Fights using a close-range aura and flying projectiles |
| Star Exile | Uses powerful, progressively enhanced piercing shots |

Each character offers a different playstyle. Your choice affects combat tactics, item synergies, and the difficulty of your run.

## 🗡️ Items and Builds

Items are one of the core mechanics of the game.

They can:

- Increase health, speed, strength, and other attributes.
- Change how attacks behave.
- Add extra projectiles and elemental damage.
- Create defensive effects and helpful companions.
- Grant active abilities.
- Restore health or empower the hero under specific conditions.
- Interact with other items to create unusual combinations.

Most characters can carry up to ten items. The Architect can customize their item capacity.

Some items have active effects that require the player to trigger them manually.

## 👹 Bosses and Progression

Bosses appear at key stages of the journey, each featuring unique attacks and multiple combat phases.

As you progress:

- Enemies become more dangerous.
- Enemy stats increase.
- New threats and more complex attack patterns appear.
- Rewards help you create stronger builds.

After defeating the final boss, you can begin a New Game+ cycle with more powerful enemies.

The game also features a chance to recover from death under certain conditions, allowing the hero to return to a run while losing some items.

## 🧪 Creative Mode

The Creative Lab is designed for experimenting with and testing gameplay mechanics.

You can:

- Search for items by name.
- Test different builds.
- Spawn enemies and summon bosses.
- Test your damage on a training dummy.
- Experiment with character attributes.
- Explore interactions between items and abilities.

Searching for and granting any item is restricted to the Creative Lab and is not available during a normal run.

## 💻 Installation and Launch

The game is distributed as an HTML project using JavaScript and CSS. You do not need to compile C++ to play the main game.

### Option 1: Download from GitHub

1. Open the repository page.
2. Click **Code → Download ZIP**.
3. Extract the archive to a folder of your choice.
4. Open the project folder.
5. Launch `index.html` in a modern web browser.

If the project includes a Windows launcher, you can also try `Korni_Tmy.exe` or `START_GAME.bat`. Keep `index.html` and all required resources in their original locations.

### Option 2: Clone with Git

If Git is installed, run:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY
```

Then open `index.html` in your browser.

Replace `YOUR-USERNAME/YOUR-REPOSITORY` with your actual GitHub account and repository name.

### Troubleshooting

- Make sure the archive has been fully extracted.
- Verify that `index.html` is in the project folder.
- Try an up-to-date version of Chrome, Edge, or Firefox.
- If opening the file directly causes resource-loading or save-related issues, start a local server from the project root:

```bash
python -m http.server 8000
```

Then open this address in your browser:

```text
http://localhost:8000
```

Python must be installed to use this method.

## 🎮 Controls

Default keyboard controls:

| Key | Action |
|---|---|
| `W` | Move up |
| `A` | Move left |
| `S` | Move down |
| `D` | Move right |
| `E` | Pick up an item |
| `Esc` | Pause and open the character screen |
| `T` | Open the talent tree |
| `F2` | Open the Creative Lab |

Attacks, active items, and additional actions may depend on the current control settings. Check the in-game prompts if you need more information.

### 📱 Mobile Support

The settings include a mobile-control option with on-screen touch controls.

To play on a phone, open the game in a mobile browser. If the project is hosted on GitHub Pages, you can use the published repository page.

## 💾 Save System

The game uses the browser's local storage. Progress may be tied to a specific browser and device.

To back up your save:

1. Open the save menu.
2. Use the export function.
3. Store the exported JSON file somewhere safe.

To transfer progress to another device, import the saved JSON file.

**Important:** Clearing browser data may delete your local save. Regular backups are recommended.

## 🛠️ Technologies

- HTML5
- CSS3
- JavaScript
- Canvas API for rendering the game world
- Local Storage for saving local progress
- ZIP archives for distribution

The Windows launcher is designed to make the browser version easier to launch. It is not a standalone native C++ build.

## 🗺️ Future Plans

Potential areas for future development include:

- Additional characters, bosses, and locations.
- New items and item interactions.
- Improved animations and visual effects.
- An expanded talent system.
- Better mobile controls.
- Further balance changes and bug fixes.
- Additional sound effects and music themes.

## 📜 License

Before publishing, choose a license that matches how you want others to use your code and assets.

For example, the MIT License is suitable for many open-source software projects. However, make sure you have the right to distribute all included images, fonts, music, sound effects, and other assets under the selected license.

## ❤️ Support the Project

If you find a bug or have an idea for an improvement, create an **Issue** in the repository. Describe the problem and include the steps needed to reproduce it.

Thank you for your interest in **Roots of Darkness: Echoes of the Fallen Kings**!
