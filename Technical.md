# Technical Specifications (NES)

## 📐 Pseudo-3D Rendering
The engine uses projection math to simulate 3D depth on a 2D plane.
* **Projection Distance:** 300.
* **Horizon Y:** 250 (Screen Center).
* **Z-Range:** -10 (Destroyed) to 1000 (Spawn).
* **Culling:** Sprites are hidden when $Z > 200$ to maintain the 8-sprite limit.

## 💾 Memory Layout (32KB PRG-ROM)
* **$8000-$FFFF**: Main code, physics, and AI.
* **$0200-$02FF**: OAM (Object Attribute Memory) for sprite data.
* **$0300-$04FF**: Active object pool (8 cars maximum).

## 🎨 Graphics (8KB CHR-ROM)
* **Total Tiles:** 512 (256 Background / 256 Sprites).
* **Color Palette:** 4 colors per tile using standard NES hex codes ($0F, $30, $16, $27, $3A).

## 🔊 Audio Engine
Uses 4-channel NSF audio.
* **Square Channels:** Melody and Harmony.
* **Triangle Channel:** Bassline and specific SFX like Nitro pulses.
* **Noise Channel:** Engine rumble, kick drums, and crash/explosion SFX.
