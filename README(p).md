# Infinite Blacklist 🕹️

**Infinite Blacklist** is a high-performance Arcade Combat-Racer designed specifically for the **NES/Famicone** hardware. [cite_start]This project serves as a technical showcase of 8-bit optimization, pseudo-3D rendering, and systemic design within a strict **40KB cartridge limit**[cite: 122, 123, 125, 128].

## 💎 Technical Showcase
* [cite_start]**Constraint-Driven:** Designed for 60 FPS gameplay with a limit of 8 sprites per scanline[cite: 125].
* [cite_start]**Memory Management:** Optimized for 32KB PRG-ROM (Code) and 8KB CHR-ROM (Graphics)[cite: 171, 210].
* [cite_start]**Pseudo-3D Math:** Custom projection distance and Z-scaling equations for real-time scaling[cite: 180, 181, 182].

## ⚔️ Combat Mechanics: The "Lunge"
Unlike traditional racers, combat is central to the loop:
* [cite_start]**Lunge Attack:** Double-tap steering to slide 3 tiles sideways and wreck rivals[cite: 142, 143, 144].
* [cite_start]**Hitbox Expansion:** Player width doubles during a lunge for maximum impact[cite: 149].
* [cite_start]**Heat System:** Dynamic enemy spawning based on "Wreck Heat" (0-100%)[cite: 150, 151, 152].

## 🏁 Arcade Loop
1. [cite_start]**Race:** Infinite pseudo-3D road[cite: 132, 134].
2. [cite_start]**Smash:** Lunge-slam rivals for cash[cite: 135, 138].
3. [cite_start]**Bosses:** Defeat a Blacklist Boss every 5 miles to increase Rank and Speed[cite: 136, 139].
4. [cite_start]**Upgrade:** Spend cash in the Garage on Engine, Frame, or Nitrous[cite: 137, 140, 162, 164].
