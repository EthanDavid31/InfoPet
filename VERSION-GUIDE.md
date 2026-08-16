# InfoPet - Version Guide

## Two Versions Available

### 1. **index.html** — User/Production Version
- Clean app without development tools
- No visible developer buttons
- For testing gameplay normally
- This is the version users would play

### 2. **index-dev.html** — Developer Version
- Includes the **🔧 Developer Stage Selector** in the top-left corner
- Open this file for testing different evolution stages

---

## Developer Features (index-dev.html only)

### Evolution Stage Dropdown
Click the **🔧** button in the top-left corner to open a dropdown menu with options to instantly switch to any stage:

- 🥚 Info Egg
- 🐣 Curious Hatchling
- 🧭 Explorer
- 🔎 Thinker
- 🛡️ Guardian

### Auto-Fill Requirements
When you select a stage from the dropdown, the game **automatically fills all the requirements** needed for that stage:

#### Explorer Requirements
- Curiosity: 40
- Places Visited: 3 (Home, Park, Library)

#### Thinker Requirements
- Curiosity: 50
- Judgment Calls: 15
- Beliefs Cleared: 1
- Places Visited: 3

#### Guardian Requirements
- Curiosity: 60
- Empathy: 50
- Judgment Calls: 30
- Verified Claims: 3
- Source Trails Done: 1
- Tactics Identified: 1
- AI Boundaries Kept: 1

### Reset All Stats
The dropdown also has a "Reset All Stats" option to instantly clear all progress and return to a fresh start.

---

## How to Use for Testing

1. **Open `index-dev.html`** in your browser
2. **Click the 🔧 button** in the top-left corner
3. **Select the stage** you want to test
4. All requirements are instantly filled
5. The pet evolves immediately with all needed stats loaded
6. Test the features and content for that stage

This makes it quick and easy to test all evolution stages without grinding through the game!
