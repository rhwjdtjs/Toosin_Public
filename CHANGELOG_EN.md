# 📋 Changelog

All notable changes to this project will be documented in this file.

[Official Website](https://teamniriz.com/) · [Discord](https://discord.gg/EHMwJSjWpA) · [Support](mailto:support@teamniriz.com)

---
## [Version 1.1] AI Learning, Blood Contract, Tutorial & UI Update - August 23, 2026

### Highlights
- Rebalanced the benefits and penalties of 12 Blood Contracts and stopped the event once every available contract is owned.
- Reduced Auto Parry from 7s to 3s and Aegis Shield and Time Stop from 5s to 3s.
- Enemy AI now collects current-combat attack, movement, defense, timing, ability, and dodge-to-heavy habits and applies them to the same enemy's next decisions.
- Added a hold-to-view TAB/Y panel for samples, confidence, applied weights, planned responses, and the last executed action.
- Added the first-launch controls tutorial and improved out-of-combat recovery wording, multilingual UI, the shared font, Trait-state colors, and Steam stability.
- Enemies can use Special Abilities from Campaign Stage 100 and Infinite Round 10.

[Full Version 1.1 notes and before/after tables](V1.1_UPDATE_EN.md)

---
## [Version 1.0] Full Release · Leaving Early Access - August 13, 2026

### 🚀 Full release
- Following the public 1.0 Beta on August 4 and final stabilization, Version 1.0 launched on Steam and STOVE on August 13, 2026.
- Added support for six languages: English, Korean, Japanese, Simplified Chinese, Traditional Chinese, and Russian.

### ✨ Progression and content
- **Three classes and expanded builds**: combine weapons, combos, appearances, 100+ Traits, 20+ Perks, Mastery, and Special Abilities including Time Stop.
- **Permanent rewards**: unlocked weapons, combos, appearances, and Special Abilities persist after reincarnation and leave the reward pool.
- **Play Point refunds**: run-based Traits reset on death, while Play Points spent on enhancements, Trait exchanges, the Mysterious Merchant, and other systems are refunded.
- **Weapon enhancement and Combat Power**: standard weapons can reach +30, while equipment, progression, and stats contribute to a Combat Power value up to 1,000,000.

### ⚔️ Combat and AI
- **Blood and impact**: improved enemy- and hit-location-aware blood, unarmed impacts, knockback, damage/low-Health screens, cameras, and controller vibration.
- **Adaptive AI**: rule-based analysis of attack, guard, parry, dodge, and spacing habits, communicated through enemy personalities and learning logs.
- **DDA**: player progression and combat patterns influence enemy decisions and battle flow.
- **Multi-enemy combat**: Infinite Mode attacks can hit multiple enemies in range, while player focus follows the nearest threat.

### 🏆 Modes and platforms
- **Infinite Mode**: added unlimited rounds that preserve Health and Stamina, scale up to 1 vs. 5 encounters, and post to a dedicated leaderboard.
- **Ranked Season 1**: added placement matches, platform leaderboards, profile images, tier rewards, and matched AI rivals.
- **Steam and STOVE**: integrated ownership checks, achievements, stats, leaderboards, and platform profile information.

### 🛠️ Stability
- Stabilized saving/loading for permanent unlocks, contracts, buffs, shops, rewards, Perks, Traits, class progress, and achievements.
- Improved long sessions, stage transitions, camera overlap, spawn collision and height, clipped UI, option persistence, and input flows.
- Separated light- and heavy-attack reuse cooldowns so switching attack types remains immediately responsive.

---

## [Ver.0.0.90 Build#1] 1:1 Ranked Match (Beta) Season 0 & Stage Graphics Renewal - June 14, 2026

### ✨ New Features
- **1:1 Ranked Match (Beta) Season 0**: Placement matches (5 rounds), rating point system, ranked tier progression, and permanent account stat buffs based on rank tier.
- **Ranked Match AI Matchmaking**: Rated AI matching, matchup confirmation popup showing opponent builds (traits/perks/contracts) with countdown, displaying "None" for empty slots.
- **Stage Visual Overhaul**: Upgraded floor/pillar material reflectivity and texture tones for a classic Colosseum aesthetic.
- **Crowd Performance Toggle**: Added a graphics settings option to disable spectators for improved FPS in performance-critical situations.
- **League & Leaderboard Simulation**: Added permanent local leaderboards registering encountered AIs, background simulation of other AI matches, and separate rank tracking per difficulty.
- **Difficulty-specific Ranks**: Leaderboard scores track independently across different game difficulty modes.
- **Ranked Hub Transition**: Skipped standard stage settlement sequences for faster pacing, redirecting players back to the hub with an immediate rank update notification popup.

### ⚖️ Balance & Bug Fixes
- **AI Decision Rework**: Refined guard/parry/dodge timings and cognitive learning for more engaging 1v1 engagements.

---

## [Ver.0.0.82] Demo Build Registration, Guard/Stamina Rework & Class Combos - June 10, 2026

### ✨ New Features
- **Steam Demo Registration**: Successfully registered the official Steam Demo build, set for release on June 16.
- **Weapon Guard Attribute (GuardMult)**: Reworked the guard formula to highlight weapon identity and reduce over-reliance on parrying.
- **Shield Guard**: Raised base damage reduction from 30% to 80% (max 90%), reducing guard stamina costs to 30% of blocked damage.
- **Sword Guard**: Raised base damage reduction to 40% (max 50-60%), reducing guard stamina costs to 20% of blocked damage.
- **Class Weapon & Combo Slot Rework**: Reworked classes (Warrior: 2 weapons swap, 1 slot each, HUD feedback; Swordsman: 1 weapon, instant 2 combo transitions; Fighter: barehanded, 3 combo slots).
- **7 New Perks Added**: Added Adrenaline, Shield Bash, Berserker, Lucky Strike, Giant Slayer, Combo Master, and Armor Breaker. Rebalanced Inferno and Bloodsucker.
- **Chance-based Guard Break**: Striking guarded enemies has a fixed 10% chance to force a Guard Break regardless of their stamina (exclusive to player attacks).
- **Guard Break Presentation**: Successfully guard-breaking an enemy triggers a slow-motion effect and stuns the target for 2.5 seconds.
- **Parry Slow Motion**: Landing a perfect guard (parry) applies a brief time dilation to all combatants, giving players time to react.
- **Knockback Physics**: Added force and angle-based physical knockback reactions on clean melee hits.
- **UI/UX Refinement**: Consolidated character info and combos into the Weapon/Combo Editor, added a real-time stat checker popup, improved hover tooltips, and optimized Training Room navigation.

### ⚖️ Balance & Bug Fixes
- **Special Enemy Spawn Delays**: Delayed spawn thresholds to smooth out the early game curve: Elite (St. 20), Epic (St. 30), Boss (St. 40), and Special (St. 50).
- **Boss Ambush Protection**: Disabled random enemy ambush events during boss and named enemy stages.
- **Dynamic Trait Scaling**: Reworked enemy trait/perk generation rules based on stage levels and player DDA indices across specific stage ranges.
- **Removed Trait (Thorn Mail)**: Removed the frustrating enemy perk 'Thorn Mail' to accommodate low-HP player perk builds.
- **Core Bug Fixes**: Resolved the brief freeze following execution sequences for Warrior/Swordsman and fixed the interrupted hit-reaction montages for Fighters.

---

## [Ver.0.0.81] Hotfix & System Stability - May 10, 2026

### ✨ New Features
- **TEAM NIRIZ Transition**: Official transition to a team-based development structure with a professional client developer joining on May 10th.
- **Achievement Queue System**: Introduced a queue system to prevent Steam achievement notifications from overlapping or missing.
- **Real-time Synchronization**: Optimized forced save points to ensure traits chosen in the Hub are immediately reflected in saves.
- **Shop Rebalancing**: Significantly lowered costs for Fighter (1,000 Gold) and Swordsman (10,000 Gold) classes.

### ⚖️ Balance & Bug Fixes
- **Physics Optimization**: Fixed ragdoll jittering after executions and enhanced ground alignment logic.
- **Training Dummy**: Fixed health bar refresh and attack mode control errors for training dolls.
- **UI & UX**: ESC key support for all windows, fixed skill preview flickering, and added scrolling for the perk list.
- **System Optimization**: Fixed BGM cutting issues and occasional crashes during scene transitions.

---

## [Ver.0.0.80] Steam Early Access Launch, New Character Classes & Major System Overhaul - May 6, 2026

### ✨ New Features
- **New Classes**: Added 'Fighter' and 'Swordsman' classes with unique weapons and combo skills.
- **Unlock System**: New shop tab for class unlocks using in-game gold.
- **Revival System Rework**: Choose a different owned character upon defeat for strategic re-challenge.
- **Dynamic Hub**: Hub theme (BGM and level design) now evolves based on stage progress.
- **Official Localization**: Official Japanese translation added; Steam/Stove achievements and leaderboards integrated.
- **New Options**: Added On/Off toggles for notification marks and stage guidance messages.

### ⚖️ Balance & Bug Fixes
- **Enemy Scaling**: Added new Boss/Special enemies and adjusted existing enemy tiers.
- **Training Room**: Fixed dummy guard bugs and shortened attack cycle to 1 second.
- **Combat & Animation**: Refined 0.18s hold charging logic, improved blood hit effects, and renewed major enemy animations.
- **System Stability**: Resolved achievement duplication bugs, charging trait unlock errors, and leaderboard call issues.
- **Save Migration**: Provided a naming guide for save file migration (ToosinGame.sav -> TOOSINGAME_STOVE.sav).

---

## [Ver.0.0.71] Platform Isolation & Global Optimization - April 20, 2026

### ✨ New Features
- **Platform Isolation (Stove SDK)**: Perfected decoupling via `#if WITH_STOVE` to prevent linker errors.
- **Localization**: Applied `NSLOCTEXT` to Mock Combat result screens for real-time translation.
- **SteamPipe**: Configured VDF scripts for Steam build deployment.

### ⚖️ Balance & Bug Fixes
- **TSRankingWidget**: Fixed compilation errors in Steam builds related to Stove ranking functions.
- **Save Data Safety**: Isolated Stove and Steam save data to prevent crashes and conflicts.
- **Supporter Recognition**: Added Tumblbug supporter nicknames to in-game credits.

---

## [Ver.0.0.70] Mock Combat Mode & Balance Overhaul - April 15, 2026

### ✨ New Features
- **Mock Combat**: Added a risk-free practice mode with dedicated BGM and UI.
- **UI Visuals**: Added Gaussian Blur effect to the perk selection screen.

### ⚖️ Balance & Bug Fixes
- **Base Stats**: Increased base stamina from 120 to 200.
- **Balance Overhaul**: Lowered gold/exp rewards and buffed Epic-tier enemy stats.
- **Stability**: Fixed runtime crashes during save file overwriting and data leaks in Mock Combat.
- **Leaderboard Sync**: Fixed ID identification errors where only the user's rank was fetched.

---

## [Ver.0.0.60] Stove SDK Integration & Final Polishing - April 08, 2026

### ✨ New Features
- **STOVE SDK**: Achievements and Leaderboards integration.
- **Visuals**: Main Arena map renewal and new opening/in-game cinematics.
- **Localization**: Full Korean/English support and UI anchor optimization.

### ⚖️ Balance & Bug Fixes
- **Achievements**: Fixed bugs preventing achievement triggers under specific conditions.
- **Optimization**: Resource and frame optimization for large arenas.
- **UI/UX Polishing**: Renewed combo guide videos and fixed option save errors.

---

## [Ver.0.0.51] Beta Update - New Classes & Convenience - March 30, 2026

### ✨ New Features
- **New Classes**: Added 'Ambush' (strategic) and 'Special' (high firepower) classes.
- **Camera**: Added FOV adjustment options.

### ⚖️ Balance & Bug Fixes
- **Graphics**: Fixed bugs where settings were not applied to rendering.
- **Stability**: Fixed stat bugs caused by random events.
- **Localization Foundation**: Structured Korean/English data for global support.

---

## [Ver.0.0.50] Random Events & Content Expansion - March 24, 2026

### ✨ New Features
- **4 Random Events**: Merchant, Blood Pact, Ambush, and Challenge events.
- **Enemy Traits**: Enemies gain unique traits after certain stages.
- **Gold Carry-over**: Inherit 50% of gold upon death.
- **UI Overhaul**: Modernized interface design and optimized user experience.
- **Achievements**: Fully launched achievement system and notifications.

### ⚖️ Balance & Bug Fixes
- **Combat Logic**: Precise attack speed calculation based on weapon base speed.
- **Real-time Stats**: Buffs and contracts are now reflected in the stat panel in real-time.
- **Lifesteal**: Fixed bugs where enemy lifesteal trait did not trigger.
- **AI Logs**: Fixed naming and data errors in AI learning records.

---

## [Ver.0.0.40] Global Rankings & Stabilization - March 21, 2026

### ✨ New Features
- **Global Rankings**: Integrated Steam/Stove leaderboards.
- **Platform Sync**: Automatic account linking for data preservation.
- **Options**: Added V-Sync, Frame Limit, Sound Volume, Mouse Sensitivity, and Key Bindings.
- **Damage Numbers**: Customizable floating text size.

### ⚖️ Balance & Bug Fixes
- **AI Behavior**: Applied DDA-based dodge and 5s guard limit for shield enemies.
- **Combat Fixes**: Resolved ragdoll freezing upon death and reinforced invincibility logic for revival traits.
- **Stability**: Eliminated crashes related to DLSS/Ray Tracing and improved loading transitions.

---

## [Ver.0.0.30 Beta] Demo Release & DLSS 4.5 - March 18, 2026

### ✨ New Features
- **DLSS 4.5**: Latest NVIDIA upscaling and Frame Generation support.
- **Intelligent Sound**: Location-based sound control (Hub/Arena/Training).
- **AI Advancement**: DDA score correction and win-streak difficulty balancing.
- **Growth Visualization**: UI notification for 'TP+1' and 2x stat scaling upon level-up.
- **Demo Balance**: Significant difficulty reduction for accessibility.
- **Control Polishing**: Final blow slow-motion balancing and 60-degree rotation limit for target tracking.
- **UI Rework**: Immediate combo equipping without slot selection.

### ⚖️ Balance & Bug Fixes
- **Sound Check**: Full audit and fix for sound output in Hub/Training maps.
- **Security**: Prevented media and markdown file exposure in packaging.

---

## [Ver.0020] First Beta Release (Beta Release) - March 13, 2026

### ✨ New Features
- **UI Localization**: Full Korean localization for all in-game UI.
- **Combo Video Preview**: Video tooltips for combo techniques in the shop.
- **Convenience**: ESC key support for all sub-menus in the Hub.

### ⚖️ Balance & Bug Fixes
- **Loading Stability**: Fixed infinite loading bugs and map flickering during cinematic transitions.
- **Visual Polish**: Fixed Korean encoding issues on weapon cards and video tooltip ghosting.

---

## [MVP-8] Production Polishing & AI Expansion (Ver.0011) - March 11, 2026

### ✨ New Features
- **Cinematics**: Global loading widget and Intro skip (Spacebar) functionality.
- **Hub UI**: Added 'AI Learning Log' panel.
- **Enemy Scaling**: Random perks and traits assigned to enemies based on stage rank.

### ⚖️ Balance & Bug Fixes
- **Combat Fixes**: Resolved attack speed multiplier bugs for non-longsword weapons.
- **AI Behavior**: Active strafing during guard/hit states and aggressive frontal dodging.
- **DDA Fix**: Normalizing DDA weights in the runtime data layer.

---

## [MVP-7] Motion, Traits & Bug Fixes - March 05, 2026

### ✨ New Features
- **Visuals**: AI root-motion stabilization and Dust particle effects.
- **New Traits**: Dodge Attack and Charge Strike (Weapon Arts rework with Super Armor).

### ⚖️ Balance & Bug Fixes
- **AI Stability**: Fixed stamina exhaustion idle bugs.
- **Data Parsing**: Fixed text parsing errors for Crit, DEF, and Regen stats.
- **Logic Fixes**: Resolved bugs where combos were maintained after death.

---

## [MVP-7] Arena Crowd, AI & Sound Manager - March 04, 2026

### ✨ New Features
- **Arena Crowd**: HISM-based optimized crowd system.
- **Sound Manager**: Centralized audio control via GameInstanceSubsystem.
- **Combat SFX**: Integrated hits, blocks, parries, and death groans.

### ⚖️ Balance & Bug Fixes
- **AI Core Fixes**: Fixed stamina recovery timer bugs and Low HP logic flaws.
- **Loop Prevention**: Resolved infinite retreat loops for AI.

---

## [MVP-7] Dodge, Smarter AI & Enemy Rework - March 04, 2026

### ✨ New Features
- **Dodge System**: 4-way root-motion based evasion with 'Dodge Parry' mechanic.
- **Character Pool**: Expanded enemy pool to 18 types with rank systems (Normal/Elite/Epic/Boss).
- **DDA Spectrum**: Expanded weights to -10.0 ~ +10.0.

### ⚖️ Balance & Bug Fixes
- **Sticky AI**: Resolved excessive proximity issues with Optimal Attack Range correction.
- **Double Hit**: Applied attacker-based debounce to dash attacks.

---

## [MVP-7] Economy, Shop & Training Remaster - March 02, 2026

### ✨ New Features
- **Economy**: Introduction of in-game gold currency and Hub Store.
- **Combo Editor**: Customizable combo slots with weapon group awareness.
- **Training Remaster**: Full custom dummy stats and live DPS monitoring.
- **Dummy AI**: 3s attack timer and guard toggle for practice.

---

## [MVP-1 to MVP-6] Core Development Phase (Summary)
- **MVP-6**: Roguelike growth, perk system, and weapon station.
- **MVP-5**: Game flow, Hub level structure, and save/load system.
- **MVP-4**: HUD system, stamina mechanics, and difficulty scaling.
- **MVP-3**: AI behavior trees and pattern learning.
- **MVP-2**: Blocking, parry, and directional hit reactions.
- **MVP-1**: Basic movement, enhanced input, and character foundation.
