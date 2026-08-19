# Cage Trap — Project State

## Canonical status

- Project: Cage Trap
- Minecraft: 26.1.2
- Loader: NeoForge
- Current version: 1.1.0
- Mod ID: `cagetrap`
- Main package: `com.jeancedraz.cagetrap`
- Canonical JAR supplied by the user on 2026-08-19.
- Canonical JAR SHA-256: `92c22f13edfccaadb0fd284a676560fb38cd3643282383b895c92a6238b32533`

The supplied JAR is the authoritative runtime baseline for future development.

## Verified contents

The baseline contains:
- Cage Trap block and item
- Filled Cage Trap item representation
- Block Entity
- Client Block Entity Renderer
- Item decorator/render state
- Open and closed block models
- Capture-related English and Brazilian Portuguese tooltips
- Entity-type blacklist tag
- Crafting recipe and loot table

## Binary baseline storage

The exact 1.1.0 JAR is preserved losslessly in `baseline/parts/` as ordered Base64 chunks. Run `scripts/restore_baseline.py` to rebuild `baseline/CageTrap-1.1.0.jar`; the script verifies the canonical SHA-256.

## Safety rule

1. Read this file before changing Cage Trap.
2. Verify version and canonical SHA-256.
3. Do not recreate missing behavior from memory.
4. Preserve existing capture/carry/release behavior unless the user explicitly requests a redesign.
5. Record every future release in `CHANGELOG.md`.
