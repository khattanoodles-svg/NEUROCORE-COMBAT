Neurocore — Robot Combat Game

2026 · Unreal Engine 5.5.4 · Blueprints · Ongoing

Neurocore is a robot combat game developed in Unreal Engine 5.5.4, built entirely using Blueprints. The project focuses on enemy AI, dynamic combat mechanics, Niagara visual effects, animation systems, collision logic, level design, and performance optimization.

The game has gone through multiple iterations, with the combat, enemy AI, visuals, and underlying game architecture continuously being redesigned and improved.

Features
Custom enemy AI with multiple combat stages
Player-state-based enemy attacks
Multiple combat grades and attack types
Dynamic enemy difficulty through size and health variation
Nav Mesh-based AI movement
Different Level mechanics and goals
Cinematic level introductions and death sequences
Niagara-based combat, collision, and death effects
Bullet-time mechanics
Enemy-specific mechanics and behaviors
Weapon modifications and upgrade system
Dynamic combat and collision logic
Custom sound design using Unreal Engine's built-in audio systems
Development Updates
Update 1

The initial version of Neurocore featured 2 enemy AI stages.

Enemy attacks changed depending on the player's current state:
Mid-air
Stationary
Moving
Moving while airborne
Damage calculations were adjusted based on the player's movement state.
Initial enemy patterns and combat logic were established.
Update 2

The project expanded to 3 enemy AI stages and introduced several visual and gameplay improvements.

Added new level designs with improved lighting and particle effects.
Added custom Niagara effects for enemy-player collisions.
Expanded combat mechanics into 2 combat grades.
Introduced bow-using enemies.
Improved the game's widget/UI interface.

View Update 2

Update 3

The third iteration focused heavily on visual improvements, cinematic presentation, combat, and enemy AI.

Enhanced materials, level design, and visual effects.
Added cinematic cameras and level sequences for:
Level introductions
Player/enemy death animations
Added a new combat ability modifier.
Introduced a new player maneuvering ability.
Improved enemy death effects.
Optimized enemy AI and introduced difficulty scaling through:
Enemy size variation
Health variation
Added a new enemy type that cannot be damaged and must instead be avoided.

View Update 3

Update 4

The fourth update expanded the game's combat system and introduced more complex level mechanics.

Enhanced the combat system.
Added several new levels.
Introduced bullet-time mechanics.
Added new collision effects.
Created levels involving:
Gravity manipulation
Rotation
Difficult terrain
Introduced a new enemy type: Drones.
Added weapon move modifications.
Introduced an upgrade shop.

View Update 4

Reboot — After Update 7

Following Update 7, the project underwent a major technical reboot. The entire game logic was rewritten with a focus on performance, optimization, and smoother gameplay.

AI & Performance
Rewrote the entire game logic to improve performance and optimization.
Rebuilt enemy AI from manually coded Event Tick logic to Nav Mesh-based AI movement.
Removed optimization issues caused by continuously running manual movement logic.
Enemy AI was redesigned to make future expansion and difficulty scaling easier.
Combat System

The combat system was redesigned around distinct attack types rather than the previous velocity-based system.

The player currently has 3 attack grades:

Defense
Attack
Heavy

Each attack serves a different combat purpose.

The previous velocity-based attack system has been shelved for the current version.

Enemy Systems
Enemies currently have 2 combat stages.
Added two new enemy parameters:
Bat Resistance
Temperature
Player and enemy behavior is now processed according to the type of attack being used.
Improved enemy attack and death behaviors.
Visual & Audio Improvements
Expanded visual presentation beyond basic Directional Lighting and Niagara effects.
Added improved Niagara effects for:
Enemy attacks
Player attacks
Collisions
Enemy deaths
Added more impactful sound design by combining multiple built-in Unreal Engine audio systems.
Current Development Direction

The next major goal is to introduce ML-based enemy AI.

Instead of relying entirely on hardcoded enemy behavior, the planned system will allow enemies to learn from player movement and combat patterns, creating more adaptive and unpredictable encounters.

Next: Incorporate machine-learning-based enemy AI that learns from player behavior rather than relying solely on predefined logic.

View Reboot / Latest Update

Tech Stack
Engine: Unreal Engine 5.5.4
Programming: Blueprints
AI: Nav Mesh-based AI
VFX: Niagara
Animation: Unreal Engine Animation Systems
Audio: Unreal Engine Built-in Audio Systems
Cinematics: Level Sequences & Cinematic Cameras
Status: Ongoing
Project Goals

Neurocore is primarily an exploration of gameplay programming and systems design within Unreal Engine using Blueprints-only development. The project continues to evolve through experimentation with:

AI architecture
Combat systems
Performance optimization
Procedural/dynamic gameplay behavior
VFX and animation
Cinematic presentation
Player behavior analysis
Machine-learning-based AI
