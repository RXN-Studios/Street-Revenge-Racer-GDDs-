# Technical Specifications (NES)

## 📐 Pseudo-3D Rendering
[cite_start]The engine uses projection math to simulate 3D depth on a 2D plane[cite: 180].
* [cite_start]**Projection Distance:** 300[cite: 181].
* [cite_start]**Horizon Y:** 250 (Screen Center)[cite: 181].
* [cite_start]**Z-Range:** -10 (Destroyed) to 1000 (Spawn)[cite: 183].
* [cite_start]**Culling:** Sprites are hidden when $Z > 200$ to maintain the 8-sprite limit[cite: 184].

## 💾 Memory Layout (32KB PRG-ROM)
* [cite_start]**$8000-$FFFF**: Main code, physics, and AI[cite: 212].
* [cite_start]**$0200-$02FF**: OAM (Object Attribute Memory) for sprite data[cite: 214].
* [cite_start]**$0300-$04FF**: Active object pool (8 cars maximum)[cite: 215, 217].

## 🎨 Graphics (8KB CHR-ROM)
* [cite_start]**Total Tiles:** 512 (256 Background / 256 Sprites)[cite: 172].
* [cite_start]**Color Palette:** 4 colors per tile using standard NES hex codes ($0F, $30, $16, $27, $3A)[cite: 188, 189, 191, 192, 195, 198].

## 🔊 Audio Engine
[cite_start]Uses 4-channel NSF audio[cite: 201].
* [cite_start]**Square Channels:** Melody and Harmony[cite: 203, 204].
* [cite_start]**Triangle Channel:** Bassline and specific SFX like Nitro pulses[cite: 205, 208].
* [cite_start]**Noise Channel:** Engine rumble, kick drums, and crash/explosion SFX[cite: 205, 207, 208].
