# Adaptive Rock Paper Scissors
Just the general design document, which some aspects carrying over to future games.

## Core Mechanic
The game uses **nested arrays** to simulate **probabilistic outcomes** based on **player input**. Each decision is mapped to a **nested array** of possible outcomes, and the **game world adapts** based on **probabilistic weighting**.

## Cryptographic Hangman
The **hangman game** uses **a shuffled alphabet** to **randomly replace wall textures**. This is **not cryptographically secure**, but it **provides procedural variation** in the game environment.

## Technical Implementation
- **Data Structures**: Nested tuples and arrays are used to **simulate complex scenarios**.
- **Encryption**: **Not cryptographically secure**, but **used for procedural dungeon generation** but changing the wall texture based on a Rot13 variation.
- **Game Engine**: Built **from scratch** using **basic Ruby** to **avoid reliance on external tools**.
