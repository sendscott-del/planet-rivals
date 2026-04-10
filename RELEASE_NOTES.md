# Planet Rivals — Release Notes

## v2.0.0 — Multiplayer Update (2026-04-09)

### New Features
- **Multiplayer Mode**: Create or join rooms (up to 4 players) using Supabase Realtime
  - Room codes: 4-letter codes to share with friends
  - Host-authoritative architecture: room creator controls enemy spawns
  - Real-time player position sync across all connected clients
  - Enemies chase the nearest player in multiplayer
  - Shared Mo$ and score across the team
- **Team Blast**: A powerful team ability available in the shop's new TEAM tab
  - Costs Mo$ 500 to unlock
  - Press T when 2+ players are within 200px of each other
  - Creates a massive AoE explosion (280px radius)
  - One-shots all non-boss enemies (tanks, normals, fast, exploders)
  - Deals 55% of boss max HP (two-shots bosses)
  - 60-second cooldown after use
  - Custom sound effect and expanding ring visual
- **Lobby System**: Full room management UI with create/join/leave
- **Team Tab in Shop**: New shop tab for team upgrades (multiplayer only)
- **Player Colors**: Each player gets a unique color (blue, magenta, green, gold)
- **Teammate HUD**: See teammate names, HP bars, and ship positions on screen

### Changes
- Start screen now has "SOLO PLAY" and "MULTIPLAYER" buttons
- How to Play section updated with Team Blast instructions
- Controls hint updates based on game mode
- Added Supabase JS client (CDN) for Realtime communication

### Solo Mode
- All existing single-player gameplay is fully preserved
- No changes to solo mode mechanics

---

## v1.0.0 — Initial Release

- Wave-based shooter defending Earth from alien mobs
- 6 weapons: Blaster, Shotgun, Laser, Plasma, Rocket, Freezer
- 10 upgrades in the Mo$ Shop
- 5-life system with respawning
- Multi-planet progression (new planet every 10 waves)
- Global leaderboard via Supabase
- Mobile touch controls
- 5 enemy types: Normal, Fast, Tank, Boss, Exploder
