# Elemental Rush (3D Endless Runner)

**Elemental Rush** is a 3D endless runner built in Unity. The player navigates a constantly evolving world filled with obstacles, elemental traps, and collectible orbs. The objective is to survive as long as possible while the world becomes faster and more challenging.

---

## Gameplay Overview

- The player runs forward automatically.
- Move **left**, **right**, and **jump** to avoid obstacles.
- Collect **elemental orbs** to increase your score.
- Ground tiles spawn and despawn dynamically for an endless world.
- Difficulty increases over time as speed ramps up.
- Rare power-ups appear to assist the player.

### Obstacles
- Rolling boulders  
- Fallen trees  
- Fire pits  
- Moving barriers  

### Power-Ups
- **Shield** – one-hit protection  
- **Magnet** – pulls nearby orbs  
- **Slow Motion** – temporarily reduces game speed  

---

## Controls

### Keyboard (PC)
- **A / D** or **Left / Right Arrow Keys** — Move sideways  
- **Spacebar** — Jump  
- **Left Shift** — Activate stored power-up (optional)  

### Mobile (Optional)
- **Swipe Left / Right** — Move sideways  
- **Swipe Up** — Jump  

---

## Core Features

- 3D lane-based or free-movement endless runner
- Procedural track generation
- Obstacle spawn patterns with increasing complexity
- Score system (distance + orb collection)
- Difficulty scaling based on time/speed
- Power-up system (shield, magnet, slow-motion)
- High score saving
- Clean UI with score and power-up indicators

---

## Art Assets Needed

**Characters**
- 3D player model  
- Run, jump, and idle animations (Mixamo recommended)

**Environment**
- Ground tiles  
- Decorative environment props  
- Skybox  

**Obstacles**
- Rocks  
- Logs  
- Fire traps  
- Barriers  

**Collectibles**
- Glowing orb model  

**UI**
- Score text  
- High score  
- Power-up icons  

---

## Audio Assets Needed

- Orb pickup sound  
- Obstacle collision sound  
- Jump sound  
- Power-up activation  
- Ambient background audio  

---

## Game Flow

1. Player spawns at base running speed.  
2. Procedural tiles generate endlessly ahead of the player.  
3. Obstacles and orbs spawn with pattern variation.  
4. Player collects orbs and avoids obstacles.  
5. Speed increases gradually to raise difficulty.  
6. Collision → Game Over (unless shield is active).  
7. Final score and high score are displayed.  
8. Player can restart instantly.  

---

## Technical Challenges

- Track tile procedural generation  
- Smooth lane switching / horizontal movement  
- Jump physics  
- Obstacle spawn fairness  
- Power-up logic  
- Performance (object pooling recommended)  

---

## Project Scope

- Single 3D environment theme  
- 3–5 obstacle types  
- 1–2 power-ups  
- Basic UI for score + high score  
- One player character with basic animations  
- Runs on PC (mobile optional)

---

## Deliverables

- Complete Unity 3D project  
- GitHub repository with clean commits  
- Short gameplay demo video  
- Brief documentation of deviations from this plan  

---

## Optional Enhancements

- Day/night cycle  
- Additional environments  
- Character skins  
- Achievements (distance milestones, orb streaks)  
- Element-themed zones  

---
