This repo stores a multiplayer-first Vanilla+ NeoForge modpack focused on exploration, progression, automation, and shared survival play. It is structured more like a pack-maintainer project than a standard app repo.

### Repository layout

- `clientMods/` — client-side modpack manifest and override configuration
- `server/` — server config and server-side modpack manifest
- `README.md` — modpack notes for maintainers and contributors
- `LICENSE` — licensing info

### Pack direction

- Automation and economy: Refined Storage, Mystical Agriculture, Mystical Agradditions, Easy Mob Farm
- RPG progression: Puffish Skills, Spice of Life: Carrot Edition, Apotheosis and apothic modules
- Exploration and worldgen: Biomes O’ Plenty, YUNG’s structures, Dungeons & Taverns, major cave and monument expansions
- Multiplayer and survival: Simple Voice Chat, PlayerRevive, stronger night pressure, and co-op-friendly utility mods

### Core loop

Explore → Survive → Progress → Automate → Expand

The intended loop is to secure loot and scouting knowledge, survive tougher nights with teammates, build power through skills and dungeon rewards, then turn that power into larger automation and infrastructure for long-term SMP growth.

### Notes for maintainers

- Keep client/server manifests aligned with the intended NeoForge version.
- Store client-only tweaks in `clientMods/overrides/` and server-only changes under `server/config/`.
- The pack is designed for shared SMP play, so keep balance and progression changes tailored to multiplayer survival rather than solo play.
- When updating mods, validate both the `clientMods/manifest.json` and `server/mods/manifest.json` entries to avoid mismatched loader versions or missing dependencies."
  new_str: "# 🌿 Trails & Tribulations

A multiplayer-first Vanilla+ modpack built for exploration, teamwork, and long-term progression.

This pack is designed for shared survival play: cozy days of building, farming, and discovery, followed by dangerous nights that reward preparation, coordination, and smart progression.

> Multiplayer-focused: this pack is built for shared SMP play.

## Quick start

1. Use NeoForge 26.1.2.
2. Import the client modpack from `clientMods/manifest.json`.
3. Use the server manifest from `server/mods/manifest.json` for a dedicated server setup.
4. Run with at least 8 GB of RAM. The included server notes recommend `-Xms8G -Xmx8G` and include the pack’s JVM tuning.

## What this pack feels like

Trails & Tribulations blends familiar survival with a stronger sense of adventure and progression. You’ll spend your time:

- exploring richer biomes and structures
- surviving tougher nights with better gear and teamwork
- growing your character through skills, food, and dungeon rewards
- building automation and scalable resource systems
- expanding your base and your reach as the world opens up

## Core features

### Automation & economy

- Refined Storage for digital storage, autcrafting, and scalable logistics
- Mystical Agriculture, Mystical Agradditions, and Mystical Automation for long-term resource growth
- Easy Mob Farm and utility mods for reliable mob-drop automation

### RPG progression & survival

- Puffish Skills for character specialization and growth
- Spice of Life: Carrot Edition for food-based progression incentives
- Apotheosis and related modules for stronger loot, enchantment depth, and late-game combat scaling

### Worldgen, structures & adventure

- Biomes O’ Plenty with major structure expansion and world generation upgrades
- YUNG’s, Dungeons & Taverns, Moog’s, and other structure-heavy enhancements
- Better caves, monuments, strongholds, and overworld points of interest
- Travel support through Waystones, maps, and exploration-focused quality-of-life additions

### Multiplayer & immersion

- Simple Voice Chat for in-game communication
- PlayerRevive for cooperative survival and recovery
- Shared progression-friendly utilities
- Rich ambient and visual improvements for a more alive world
- Stronger night pressure with undead and invasion-style threats

## Core gameplay loop

Explore → Survive → Progress → Automate → Expand

The loop is simple but satisfying:

- Explore upgraded biomes and structures to find loot, knowledge, and strongholds.
- Survive harsher nights through better gear, enchantments, and team coordination.
- Grow stronger through skills, food-based progression, and dungeon-driven upgrades.
- Transition into automation, storage, and infrastructure for long-term play.
- Use your systems to support bigger builds, deeper expeditions, and stronger co-op play.

## Repository layout

- `clientMods/` — client-side modpack manifest and override configs
- `server/` — server config and the dedicated server manifest
- `README.md` — pack overview and contributor notes
- `LICENSE` — project license

## Developer notes

This repo is maintained more like a modpack configuration project than a typical app repo. Client-only tweaks belong in `clientMods/overrides/`, and server-only config should stay under `server/config/`.

When updating the pack, keep both manifests aligned to the intended NeoForge version to avoid mismatched loader versions or missing dependencies.

## Final note

If you enjoy vanilla survival with more depth, danger, and cooperative play, this modpack is built for exactly that kind of experience.