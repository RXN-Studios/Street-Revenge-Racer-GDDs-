# Gameplay Mechanics

## ⚔️ Lunge Combat (Primary Weapon)
The core mechanic of Infinite Blacklist is the aggressive lunge attack.
* **Execution:** Double-tap steering within 8 frames (0.13s).
* **Action:** The car slides 3 tiles sideways with screen shake and spark particles.
* **Hitbox:** The player's hitbox width doubles (16px to 32px) during the lunge.
* **Damage:** 100 base damage + (Engine Level x 20).

## 🚔 Heat System
Spawning is controlled by a dynamic Heat Meter (0-100).
* **Heat Gain:** +15 per wreck.
* **Heat Decay:** 2 per frame during no-collision periods.
* **Ranges:** * 0-39%: Blue Patrol Cars (100HP).
    * 40-79%: Red Armored Trucks (250HP).
    * 80-100%: Magenta Blacklist Bosses (500HP+).

## 🏁 Blacklist Bosses
* **Spawn:** Every 5 miles (Rank x 5).
* **AI:** Aggressive tracking of player X position.
* **Rewards:** Increases Rank, base speed, and cash multipliers upon defeat.
