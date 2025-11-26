## Elemental Escape

Elemental Escape is a fast-paced 2D survival game where the player dodges falling elemental hazards while collecting crystals for points. Inspired by the “Fruit Frenzy” mechanic, the game ramps up in difficulty over time and rewards skillful movement, quick reactions, and strategic combo-building.

### Gameplay Overview

Control a character running across a hazardous environment.

Avoid falling elemental hazards:
Fire, Water, Earth, and Air.

Collect elemental crystals to score points.

Survive as long as possible as hazards fall faster and in more complex patterns.

Trigger bonus mechanics such as:

Combo scoring (collect 3 same-element crystals in a row → 2× multiplier)

Occasional power-ups like shields or slow-motion.

### Controls
Desktop

Left/Right Arrow or A/D: Move left and right

Spacebar: Activate power-up (e.g., shield)

Mobile (Optional)

Swipe Left/Right: Move character horizontally

### Art Assets

The game requires the following assets:

Player character sprite

Falling hazards

Fireball

Water drop

Rock

Wind gust

Crystal collectibles

Backgrounds (static or tiled: desert, forest, sky)

UI elements

Score display

High score

Life bar / hearts

Combo meter

### Audio Assets

Crystal collection sound

Hazard collision (life loss)

Power-up activation

Combo multiplier sound

Optional ambient background (no music)

### Game Flow

Player starts with 3 lives.

Hazards fall at a base speed.

Player collects crystals to score points.

Colliding with hazards reduces a life (missing them is harmless).

Every 30 seconds, hazard speed and spawn complexity increase.

Game ends when all lives are lost → High score is saved.

Optional: Elemental Frenzy Mode triggers at 1000 points, spawning rapid hazards and rare bonuses.

### Challenges / Technical Considerations

Accurate collision detection (player ↔ hazards, player ↔ crystals)

Procedurally generated hazard patterns that feel fair

Combo system tracking consecutive element types

Balanced difficulty scaling

Performance optimization as hazard count increases

### Unique Features

Elemental Combo System:
Collecting 3 crystals of the same element consecutively gives a 2× score multiplier.

Dynamic procedural hazard patterns

Power-ups: Shield, slow-motion, etc.

Visual particle effects (fire trail, water splash, dust clouds)

Optional UI achievements system for extra fun

### Project Scope

Simple, single-scene 2D Unity game

Four core hazard types with scalable difficulty

Clean, functional UI (score, lives, combos)

Optional background parallax for visual depth

### Deliverables

Complete, playable Unity project

GitHub repository with neat commit history

Short gameplay video demonstrating:

Hazard interactions

Scoring

Combo system

Difficulty progression

A text report listing any deviations from this design document

### Technologies

Unity Game Engine (version optional)

C# scripts

Lightweight 2D assets

GitHub for version control
