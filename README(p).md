# Infinite Blacklist 🕹️

**Infinite Blacklist** is a high-performance Arcade Combat-Racer designed specifically for the **NES/Famicone** hardware. This project serves as a technical showcase of 8-bit optimization, pseudo-3D rendering, and systemic design within a strict **40KB cartridge limit**.

## 💎 Technical Showcase
* **Constraint-Driven:** Designed for 60 FPS gameplay with a limit of 8 sprites per scanline.
* **Memory Management:** Optimized for 32KB PRG-ROM (Code) and 8KB CHR-ROM (Graphics).
* **Pseudo-3D Math:** Custom projection distance and Z-scaling equations for real-time scaling.

## ⚔️ Combat Mechanics: The "Lunge"
Unlike traditional racers, combat is central to the loop:
* **Lunge Attack:** Double-tap steering to slide 3 tiles sideways and wreck rivals.
* **Hitbox Expansion:** Player width doubles during a lunge for maximum impact.
* **Heat System:** Dynamic enemy spawning based on "Wreck Heat" (0-100%).

## 🏁 Arcade Loop
1. **Race:** Infinite pseudo-3D road.
2. **Smash:** Lunge-slam rivals for cash.
3. **Bosses:** Defeat a Blacklist Boss every 5 miles to increase Rank and Speed.
4. **Upgrade:** Spend cash in the Garage on Engine, Frame, or Nitrous.
