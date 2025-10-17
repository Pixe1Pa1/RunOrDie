# RunOrDie
An Action-Packed Adventure Game in UE5

RunOrDie is a dynamic third-person action game I am building from the ground up in Unreal Engine 5. The mission is simple: collect coins, evade relentless enemies, and survive the chaos.

This project is my personal playground for mastering various powerful tools within UE5, and it is quickly evolving into a full-fledged game. The goal is to transform this core gameplay loop into a short, polished adventure complete with multiple levels, a storyline, and an epic finale.

Gameplay & Technology Highlights:

 - **Gameplay:** Fast-paced action that challenges the player to collect coins while strategically dodging enemy attacks using a Dash ability.
 
 - **Artificial Intelligence (AI):** Enemies utilize Pawn Sensing for player detection and AI Move To with a Nav Mesh for efficient pursuit. Their attacks are executed via a Sphere Trace that applies a knockback force.
 
 - **Complex Animation System:** The character is controlled by an Animation Blueprint featuring a State Machine for smooth transitions. A 1D Blend Space ensures realistic running, while the Dash is implemented using Animation Montages and Root Motion for precise movement.
 
 - **Optimized Architecture:** Interactions between objects (player and coins) are built on Blueprint Interfaces, which avoids direct casting and results in more flexible and performant code.
 
 - **Audio & VFX:** The project leverages Meta Sound for dynamic sound effects (randomized footsteps) and the Niagara/Cascade systems for visual effects. Legacy Camera Shake adds a sense of impact during attacks.

This repository will be actively updated to document the game's development process.
