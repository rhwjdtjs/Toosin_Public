# 📋 Changelog

All notable changes to this project will be documented in this file.

---
## [Ver.0.0.90 (Planned)] PHASE 2: Major Update & Combat Overhaul - Early July 2026

### ✨ New Features
- **Weapon Swap**: Implementation of a real-time weapon swap system, allowing players to equip 2 weapons per class.
- **Combat System Rework**: Additional slots for Light/Heavy attacks to enable deeper tactical gameplay.
- **New Class**: Either 'Samurai' or 'Spearman' will join the battlefield.
- **Enemy Class Diversification**: New types of enemies such as Fighter and Swordsman will be added along with the new classes.
- **Unique Abilities & Skills**: Specialized active/passive traits and skill systems assigned to all characters.
- **Leaderboard Overhaul**: Added Steam profile viewing from the leaderboard and expanded competitive categories like 'Fastest Clear Time'.
- **UX Improvements**: New popup to check currently owned contracts and perks in real-time.
- **Official Gamepad Support**: Official support for Xbox Controllers for a better control experience.

### ⚖️ Balance & Bug Fixes
- **Combat AI**: Optimized intelligent AI to react better to player actions; refined unnatural enemy animations.
- **UI Convenience**: Fixed a bug where the ESC key intermittently failed to close the in-game sub-UI.
- **Physics**: Resolved issues where corpses would abnormally stiffen after death; overall system stability improvements.

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

## [Ver.0.0.80] New Character Classes & Major System Overhaul - May 06, 2026

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
