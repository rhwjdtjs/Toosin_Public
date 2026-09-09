<div align="right">
  <a href="README_KR.md">🇰🇷 한국어</a> · <strong>🇺🇸 English</strong>
</div>

<div align="center">

# TOOSIN : 투신

### Surpass the AI that learns from you

[![Steam](https://img.shields.io/badge/Steam-Full_Release-1b2838?style=for-the-badge&logo=steam)](https://store.steampowered.com/app/4635530/TOOSIN/)
[![Version 1.2](https://img.shields.io/badge/Version-1.2-c0c0c0?style=for-the-badge)](V1.2_UPDATE_EN.md)
[![Version 1.3](https://img.shields.io/badge/Version-1.3-c0c0c0?style=for-the-badge)](V1.3_UPDATE_EN.md)
[![Version 1.3.1](https://img.shields.io/badge/Version-1.3.1-c0c0c0?style=for-the-badge)](V1.3.1_UPDATE_EN.md)
[![1.1](https://img.shields.io/badge/Version_1.1-2026--08--23-c0c0c0?style=for-the-badge)](V1.1_UPDATE_EN.md)
[![UE 5.5](https://img.shields.io/badge/Unreal_Engine-5.5-0e1128?style=for-the-badge&logo=unrealengine)](https://www.unrealengine.com/)

**TOOSIN** is an **arena roguelike action game** about overcoming adaptive enemies that read your attack, guard, dodge, movement, and spacing habits. Combine three classes with weapons, combos, Traits, Perks, Mastery, and Special Abilities to build your own fighting style.

**Version 1.0 launched on August 13, 2026, concluding Early Access. Version 1.1 followed on August 23.**

[Steam](https://store.steampowered.com/app/4635530/TOOSIN/) ·
[STOVE](https://store.onstove.com/ko/games/104376) ·
[Website](https://teamniriz.com/) ·
[Discord](https://discord.gg/EHMwJSjWpA) ·
[Support](mailto:support@teamniriz.com)

[![Official TOOSIN 1.0 trailer](assets/toosin-1.0/hero.png)](https://youtu.be/TrSGI-_k3KQ?si=Ldi4LljXUcPoyivW)

<sub>Click the image to watch the official Version 1.0 trailer.</sub>

</div>

## [Version 1.3.1] 20 New Perks, Existing Perk Fixes and Sword Wave Improvements

- **20 new Perks**: up to three stacks with an additional effect at three stacks. Stack values are final totals, not additive. The detailed notes include all 20 effect rows.
- **Existing Perk fixes**: Combo Master now gains combo stacks only from light attacks dealing actual HP damage; Giant’s Grip defense was adjusted to 3% / 6% / 6%.
- **Description corrections**: clarified Lifesteal, Thunderbolt and Sturdy Guard. These corrections are distinguished from gameplay balance changes.
- **Application and save stability**: fixed leftover bonuses after resets or removal, duplicate Trait records, repeated application on load, and duplicate triggers and SP refunds.
- **Icons and Sword Wave**: dedicated white icons and six-language descriptions; improved wave visibility, travel speed while preserving range, and player/enemy parrying and reflection.

[Full update notes](V1.3.1_UPDATE_EN.md)

---

## [Version 1.3] 100 Advanced Traits, Rank Bonuses, Combat and Arena Improvements

- **100 advanced T6–T10 Traits**: 20 per branch across five branches, costing 3,000 TP in total. Unlocked Traits apply when their individual activation conditions are met.
- **Trait states and effects**: 42 status indicators, pose afterimages, barriers and shockwaves, plus progression-based advanced Trait assignments for enemies.
- **Infinite Mode rank bonuses**: apply one bonus set from the best currently confirmed rank among Stage, Season 2 and Infinite Mode, for ranks 1–9. Results distinguish the stage reached from the last stage cleared.
- **Season 2 risk and rewards**: territory influence affects enemy stats, AI difficulty and victory points; added local Ranked faction buffs and confirmed personal contributions over the last 14 days.
- **Combat, graphics and training**: white multi-enemy target outlines, weapon trails, blood and camera feedback, Roman arena materials and rendering optimization, and hands-on training based on successful actions.

[Full update notes](V1.3_UPDATE_EN.md)

---

## [Version 1.2] Season 2: Shattered Throne, 5v5 Territories, Combat and Progression — 2026.09.01

- **Ranked Season 2 — Shattered Throne**: one player and four allied AI fight five enemy AI in a new arena, with free spectator controls after death and team HUDs.
- **Factions and territories**: Blood Crown and Ashen Oath, seven territories, three weekly active fronts and rolling 14-day influence. Personal season score and territory influence are separate records.
- **Guard Shove and AI**: use a light attack while guarding to shove; improved AI learning for shoves, dodges and counters, alongside combat information.
- **Progression, rewards and achievements**: revised enemy growth using Stage/Round, difficulty, grade and Combat Power; extended rewards through Stage 1000 and reworked 11 achievements around stage rewards.
- **UI and convenience**: unified Combat Power and stat displays; improved Season 2 screens, six languages, Steam announcements, Overlay pause, borderless mode and ragdolls.

[Full update notes](V1.2_UPDATE_EN.md)

## Release history

| Milestone | Date | Status |
|---|---:|:---:|
| STOVE Early Access | April 17, 2026 | Complete |
| Steam Early Access | May 6, 2026 | Complete |
| Version 1.0 Beta | August 4, 2026 | Complete |
| Version 1.0 full release · Early Access graduation | **August 13, 2026** | **Released** |
| Version 1.1 AI learning, balance, and tutorial update | **August 23, 2026** | **Updated** |
| [Version 1.2 — Season 2: Shattered Throne, 5v5 Territories, Combat and Progression](V1.2_UPDATE_EN.md) | 2026.09.01 | Update notes |
| [Version 1.3 — 100 Advanced Traits, Rank Bonuses, Combat and Arena Improvements](V1.3_UPDATE_EN.md) | — | Update notes |
| [Version 1.3.1 — 20 New Perks, Existing Perk Fixes and Sword Wave Improvements](V1.3.1_UPDATE_EN.md) | — | Update notes |

## Version 1.1 update

- Rebalanced 12 Blood Contracts and shortened Auto Parry, Aegis Shield, and Time Stop.
- Current-combat light/heavy attacks, movement, defense outcomes, attack rhythm, abilities, and dodge-to-heavy habits now affect the enemy's next decisions.
- Hold TAB or gamepad Y to inspect samples, confidence, applied weights, planned responses, and executed actions.
- Added a first-launch controls tutorial and improved multilingual UI, the shared font, Trait-state colors, and Steam stability.

[Read the full Version 1.1 update and before/after tables](V1.1_UPDATE_EN.md)

## Core features

### Adaptive AI and combat memory

Enemies do more than repeat fixed scripts. Attack choices, defensive timing, dodge direction, spacing, and movement feed a session's combat memory and influence later decisions. Distinct enemy personalities and readable learning logs show what the AI has recognized.

> TOOSIN does not use generative AI or a continuously trained online model. Its adaptive combat system uses in-game player-pattern statistics and rule-based decisions.

### Reactive melee combat

- Light, heavy, and charged attacks with weapon- and class-specific combos
- Guarding, parrying, just dodges, guard breaks, and directional hit reactions
- Distance- and direction-aware knockback with camera, vibration, and screen feedback
- Improved blood and impact VFX based on enemy type and hit location

<p align="center">
  <img src="assets/toosin-1.0/combat-parry.png" width="49%" alt="Parry combat in TOOSIN" />
  <img src="assets/toosin-1.0/combat-close.png" width="49%" alt="Close combat in TOOSIN" />
</p>

### Progression and builds

- Three classes with interchangeable weapons, combos, and appearances
- 100+ Traits, 20+ Perks, Mastery, and Special Abilities including Time Stop
- Default-weapon enhancement up to +30 plus permanent account XP and Play Point growth
- Run-based Traits reset on death, while spent Play Points are refunded
- Unlocked weapons, combos, appearances, and Special Abilities remain permanently owned and leave the reward pool

### Modes and competitive records

- **Stage Mode**: the core run structure, combining rewards and random events into evolving builds
- **Infinite Mode**: unlimited rounds that preserve current Health and Stamina, feature encounters up to 1 vs. 5, and post to a dedicated leaderboard
- **Ranked Season 1**: placement matches, tier rewards, platform leaderboards, and matched AI rivals
- **Training and Mock Combat**: safe environments for testing combat systems and builds

### DDA and Combat Power

DDA uses play patterns and progression state to tune combat flow and enemy choices. Combat Power summarizes equipment, growth, and attributes on a scale recorded and compared up to **1,000,000**.

### Release quality

- Steam and STOVE achievements, stats, and leaderboards
- English, Korean, Japanese, Simplified Chinese, Traditional Chinese, and Russian
- Stabilized saving/loading, permanent unlocks, rewards, contracts, buffs, and option persistence
- Improvements to long sessions, map transitions, cameras, collision, clipped UI, and input flows

## Game information

| | |
|---|---|
| Developer / Publisher | TEAM NIRIZ |
| Engine | Unreal Engine 5.5 |
| Platform | Windows PC · Steam · STOVE |
| Genre | Action Roguelike · Action RPG · Single-player |
| Languages | English · Korean · Japanese · Simplified Chinese · Traditional Chinese · Russian |
| Steam features | Achievements · Cloud · Stats · Leaderboards · Family Sharing |

## System requirements

| | Minimum | Recommended |
|---|---|---|
| OS | Windows 10/11 64-bit | Windows 10/11 64-bit |
| Processor | Intel Core i5-8400 / AMD Ryzen 5 2600 | Intel Core i7-9700K / AMD Ryzen 7 3700X |
| Memory | 8 GB RAM | 16 GB RAM |
| Graphics | NVIDIA GeForce RTX 2060 | NVIDIA GeForce RTX 3060 |
| DirectX | Version 12 | Version 12 |
| Storage | 8 GB | 10 GB |

## Documentation and contact

- [Version 1.1 update](V1.1_UPDATE_EN.md) · [Release roadmap](ROADMAP_EN.md) · [Changelog](CHANGELOG_EN.md) · [Detailed patch notes](PATCHNOTE_EN.md) · [Support and bug reports](SUPPORT_EN.md)
- [Version 1.0 trailer](https://youtu.be/TrSGI-_k3KQ?si=Ldi4LljXUcPoyivW) · [Website](https://teamniriz.com/) · [Discord](https://discord.gg/EHMwJSjWpA) · [Support](mailto:support@teamniriz.com)

<div align="center">

© 2026 TEAM NIRIZ. All rights reserved.

</div>
