# 📅 TOOSIN : Development Roadmap

## 📌 Goals

- **Stove Indie Early Access (EA)**: Completed (April 17, 2026)
- **Steam Global Launch**: Completed (May 06, 2026)
- **Official Release (Ver. 1.0)**: Targeted for Oct ~ Nov 2026
- **Major Update (Ver. 0.0.90)**: Targeted for July ~ Aug 2026

> This roadmap reflects the transition to the **TEAM NIRIZ Development Team** (May 10, 2026) and incorporates live feedback. Major feature updates are concentrated in July and October, with the periods in between focused on stabilization and bug fixes.

---

## 🚧 Post-Launch Update Plan

### 📅 2026 Quarterly Roadmap

#### **[Q2 2026] System Expansion & Platform Expansion (Completed)**
- **April 17**: STOVE Early Access (Ver. 0.0.70) Launched
- **April 20**: STOVE v0.0.71 Update Completed
- **May 6**: Steam Global Launch (Ver. 0.0.80) & STOVE Sync Update
- **May 10**: Transition to TEAM NIRIZ & v0.0.81 Hotfix
- **June 10**: Steam Demo Registered & v0.0.82 Update Completed
- **June 14**: Ver. 0.0.90 Build#1 Ranked Match (Beta) & Stage Graphics Renewal Completed
- **Key Updates**:
  - ✅ **Class System**: Added Swordsman & Fighter classes with shop unlock structure.
  - ✅ **Mock Combat & AI Bot**: Expanded enemy tiers in Mock Combat for efficient training.
  - ✅ **Options & Localization**: Refined On/Off features and official Japanese support.
  - ✅ **Guard & Stamina System**: Implemented GuardMult formulas, significantly buffing damage block rates and reducing stamina costs.
  - ✅ **Ranked Match Beta Season 0**: Introduced 1v1 matching, ranked points/tiers, lobby flow, and local leaderboards.
  - ✅ **Arena Graphics Renewal**: Upgraded background materials/textures and added an option to toggle crowd visibility.

#### **[Q3 2026] PHASE 2: July (Ver.0.0.90 Build#2 Major Update)**
- **Xbox Controller Support**: Full integration of Xbox gamepad with tailored vibration and control optimization.
- **UI/UX Overhaul**: Redesigning the entire user interface for menus and in-game HUD to improve visibility.
- **Visual Effects Improvement**: Complete revamp of all combat particles and camera presentation for enhanced immersion.
- **Unique Character Abilities**: Introducing character-specific active and passive special traits.
- **New Classes & Weapons**: Adding multiple new characters with unique gameplay mechanics and new weapons with custom action sets.
- **Enemy & AI System Overhaul**: Implementing a dedicated class system for enemies, refining behavior patterns, and fixing core bugs.
- **Out-of-Game Revamp**: Production of a new cinematic gameplay trailer and renewal of the Steam Store page.

#### **[Q4 2026] Official Release (Ver. 1.0 - Oct ~ Nov)**
- **Oct ~ Nov**: Official Release & Final Content Update
  - **Language Expansion**: Official support for Russian, Chinese (Simplified/Traditional), etc.
  - **New Mode 'Purgatory Mode'**: New battlefields with extreme difficulty.
  - **Battlefield Features**: Parkour elements within new battlefields (Under Review).
  - **AI Behavior Rework**: Smart and unpredictable AI pattern overhaul.
  - **Multi-Target Combat**: Rounds with 2-3 enemies appearing simultaneously.
  - **Leaderboard Expansion**: Account levels, stage rankings, and more competitive metrics.
  - **System Optimization**: Final code refactoring and stability for the 1.0 release.

---

## ✅ Completed Milestones

### Ver.0.0.90 Build#1: 1v1 Ranked Match (Beta) & Arena Graphics Rework
- **Period**: 2026.06.11 ~ 2026.06.14
- **Achievements**:
  - ✅ **1:1 Ranked Match (Beta) Season 0**: Placement matches (5 rounds), rating point system, ranked tier progression, and permanent account stat buffs based on rank tier.
  - ✅ **Ranked Match AI Matchmaking**: Rated AI matching, matchup confirmation popup showing opponent builds (traits/perks/contracts) with countdown, displaying "None" for empty slots.
  - ✅ **Stage Visual Overhaul**: Upgraded floor/pillar material reflectivity and texture tones for a classic Colosseum aesthetic.
  - ✅ **Crowd Performance Toggle**: Added a graphics settings option to disable spectators for improved FPS in performance-critical situations.
  - ✅ **League & Leaderboard Simulation**: Added permanent local leaderboards registering encountered AIs, background simulation of other AI matches, and separate rank tracking per difficulty.
  - ✅ **AI Decision Rework**: Refined guard/parry/dodge timings and cognitive learning for more engaging 1v1 engagements.

### Ver.0.0.82: Demo Launch & Comprehensive Guard/Stamina System Rework
- **Period**: 2026.05.11 ~ 2026.06.10
- **Achievements**:
  - ✅ **Steam Demo Registration**: Successfully registered the official Steam Demo build, set for release on June 16.
  - ✅ **Guard & Stamina Rework**: Implemented the `GuardMult` attribute logic. Raised Shield Guard block rate to 80% (max 90%) and Sword Guard to 40% (max 50-60%), while lowering stamina costs.
  - ✅ **Class Weapon & Combo Slot Rework**: Reworked classes (Warrior: 2 weapons swap, 1 slot each, HUD feedback; Swordsman: 1 weapon, instant 2 combo transitions; Fighter: barehanded, 3 combo slots).
  - ✅ **7 New Perks Added**: Added Adrenaline, Shield Bash, Berserker, Lucky Strike, Giant Slayer, Combo Master, and Armor Breaker. Rebalanced Inferno and Bloodsucker.
  - ✅ **Guard Break & Knockback**: Added a 10% fixed chance to trigger Guard Break on hit, rendering the target stunned for 2.5s. Implemented physics-based knockback and parry time-dilation.
  - ✅ **Difficulty & DDA Adjustments**: Delayed initial spawn stages for Elite (St. 20), Epic (St. 30), Boss (St. 40), and Special (St. 50). Disabled ambush events during boss rounds. Structured DDA trait scaling guidelines.
  - ✅ **UI/UX Refinement**: Consolidated character info and combos into the Weapon/Combo Editor, added a real-time stat checker popup, improved hover tooltips, and optimized Training Room navigation.

### Ver.0.0.81: Hotfix & System Stability (TEAM NIRIZ Transition)
- **Period**: 2026.05.07 ~ 2026.05.10
- **Achievements**:
  - ✅ **Team Expansion**: Recruited 1 game client developer; official launch of TEAM NIRIZ.
  - ✅ **Hotfixes**: Normalizing Steam Achievements (Popup Queue), enhanced real-time saving.
  - ✅ **Combat/Physics Optimization**: Fixed body jitter and execution ragdoll errors.
  - ✅ **Shop Balancing**: Significant price reduction for new classes.

### Ver.0.0.80: New Character Classes & Major System Overhaul
- **Period**: 2026.04.21 ~ 2026.05.06
- **Achievements**:
  - ✅ **New Classes**: Added Fighter and hidden class 'Swordsman'; character swap system.
  - ✅ **Dynamic Hub**: Hub BGM and level effects evolve based on progress.
  - ✅ **Japanese Localization**: High-quality official Japanese translation.

### Ver.0.0.70 - Ver.0.0.71: Mock Combat & Platform Isolation
- **Period**: 2026.04.08 ~ 2026.04.20
- **Achievements**:
  - ✅ **New Mode**: Added 'Mock Combat' for risk-free practice.
  - ✅ **Stamina Buff**: Increased base stamina from 120 to 200.
  - ✅ **Platform Isolation**: Perfected Stove SDK decoupling via `#if WITH_STOVE`.

### MVP-9: Stove Launch Preparation & Polishing (v0.0.60)
- **Period**: 2026.03.25 ~ 2026.04.08
- **Achievements**:
  - ✅ **STOVE SDK**: Achievements and Leaderboards integration.
  - ✅ **Visual Upgrade**: Remastered Main Arena map and new cinematics.
  - ✅ **Localization**: Support for Korean/English and UI anchor optimization.

### MVP-8: Content Expansion & Stability
- **Period**: 2026.03.11 ~ 2026.03.24
- **Achievements**:
  - ✅ **Random Events**: Implementation of Merchant, Blood Pact, Ambush, and Challenge events.
  - ✅ **UI Overhaul**: Modernized user-friendly design and UX optimization.
  - ✅ **Enemy Traits**: Random traits assigned to enemies after certain stages.
  - ✅ **Economy**: 50% gold carry-over system upon death.

### MVP-7: Shop, Epic Combat & Cinematic Polishing
- **Period**: 2026.02.24 ~ 2026.03.10
- **Achievements**:
  - ✅ **Currency & Shop**: Runtime purchase and equipping of combo parts.
  - ✅ **Combo Editor**: Custom combo crafting system (WBP_ComboEditor).
  - ✅ **Evade System**: 4-way root-motion based evasion.
  - ✅ **Charging Attacks**: Light/Heavy charge and release strike mechanics.
  - ✅ **Elemental Effects**: Particle effects for Fire (DoT), Ice (Slow), and Lightning (SP Drain).
  - ✅ **Cinematics**: Pre-combat cutscenes and dynamic execution montages.

### MVP-6: Roguelike System & Hub Interaction
- **Period**: 2026.02.20 ~ 2026.02.23
- **Achievements**:
  - ✅ **Perk System**: Perk data tables and selection UI.
  - ✅ **Post-Round Rewards**: Random card-based sub-perks.
  - ✅ **Exp & Leveling**: Level-up system based on combat performance.
  - ✅ **Weapon Station**: Real-time weapon equipping (One-hand, Two-hand, Shield, Spear, Hammer).
  - ✅ **Training Room**: Dummy with floating text and DPS meter.

### MVP-5: Game Flow & Hub Structure
- **Period**: 2026.02.15 ~ 2026.02.18
- **Achievements**:
  - ✅ **Hub Level**: Prison/Armory themed waiting area.
  - ✅ **Main Menu**: New Game, Continue, Options, Exit.
  - ✅ **Save/Load**: Persistent data for stages, stats, and records.

### MVP-4: Game Loop & HUD
- **Period**: 2026.02.14 ~ 2026.02.20
- **Achievements**:
  - ✅ **HUD**: HP/SP bars, stat texts (HP/SP/ATK/DEF).
  - ✅ **Stamina System**: Resource consumption for Light/Heavy attacks and Blocking.
  - ✅ **Difficulty Scaling**: Incremental enemy stats per round.

### MVP-3: Self-Learning AI
- **Period**: 2026.02.10 ~ 2026.02.14
- **Achievements**:
  - ✅ **AI System**: AIController and Behavior Tree based logic.
  - ✅ **DDA Algorithm**: Dynamic Difficulty Adjustment based on player patterns.

### MVP-2: Combat - Defense & Reaction
- **Period**: 2026.02.09 ~ 2026.02.10
- **Achievements**:
  - ✅ **Blocking & Parry**: Timing-based damage mitigation and Time Dilation.
  - ✅ **Hit Reactions**: Directional hit montages (Front/Back/Left/Right).

### MVP-1: Character Foundation
- **Period**: 2026.02.05 ~ 02.08
- **Achievements**:
  - ✅ **Movement**: WASD, Strafe, and Enhanced Input integration.
  - ✅ **Combo System**: Basic 3-hit combo and animations.
