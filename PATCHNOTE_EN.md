# TOOSIN 📝 Patch Notes

[Official Website](https://teamniriz.com/) · [Discord](https://discord.gg/EHMwJSjWpA) · [Support](mailto:support@teamniriz.com)

---
<details open>
<summary><b>[📝Patch_Version_1.0 (In Development / Release Candidate Preparation)] Leaving Early Access (Late August 2026) (Click)</b></summary>

### 🚀 Update Highlights

Version 1.0 is the major transition that will bring TOOSIN out of Early Access. The **1.0 beta is planned for early to mid-August 2026**, followed by the **full release in late August 2026** after beta verification. The items below describe the current development and integration-test scope; final details may change in response to beta results.

- #### 🎁 Permanent Progression & Stage Rewards
  - **Stage Reward Structure**: rewards are being reorganized around stages ending in 3, 7, and 0.
  - **Permanent Unlocks**: weapons, combos, character appearances, and special abilities are being verified as permanent unlocks that remain after death and reincarnation.
  - **Play Points & Traits**: earned Play Points are intended to persist across runs. Traits reset on death, while invested Play Points are refunded; this flow is under verification.
  - **Save Compatibility Notice**: the save structure will change with the 1.0 beta. Early Access save files are not planned to be compatible with 1.0, so creating a backup before updating is recommended.

- #### ⚔️ Combat Progression & Class Expansion
  - **Seven Special Abilities**: seven special abilities that broaden class and build choices are included in the 1.0 scope.
  - **Weapon Enhancement & Advancement**: default weapons are planned to support enhancement up to +30, alongside class advancement.
  - **Combat Power**: a consolidated Combat Power display is being introduced, with its calculation and comparison flow under verification.
  - **Attack-Speed Balance**: the attack-speed cap is being adjusted to 1.5 to preserve combat readability and animation stability.

- #### 🧠 AI, Locomotion & Combat Feedback
  - **Enemy Combat AI**: player-pattern analysis, guard/parry/dodge choices, preferred-range movement, and action priorities are being tuned together. This is a rule-based adaptive combat system, not online-learning generative AI.
  - **Movement & Animation**: turning, eight-direction locomotion presentation, and synchronization between movement speed and animation are being refined for players and enemies.
  - **Combat-Reaction Verification**: hit montages, knockback, unintended airborne reactions, stamina checks, guard/parry/dodge feedback, and camera presentation are undergoing focused review.

- #### 🎮 UI/UX, Controllers & Ranked Play
  - **Input Support**: Xbox controller behavior, input rebinding, duplicate-binding removal, menu focus, and ESC/B closing behavior are being polished.
  - **Interface Rework**: the in-game HUD, trait selection, stage rewards, options, and ranked matchup screens are being revised for readability and consistent navigation.
  - **Ranked Season 1**: Season 1 is being prepared for the full release, with Combat Power and matchup information under renewed verification.
  - **Tutorial Rework**: onboarding is being rebuilt to introduce combat, progression, and rewards in a clearer sequence.

- #### 🛠️ Stability & Release Candidate Verification
  - **Crashes & Performance**: stage-entry crashes after long sessions, memory use, GPU compatibility, and loading stability are priority test areas.
  - **Options & Saves**: graphics-option application, change detection, apply/cancel behavior, and progression saving after ranked play, shops, rewards, and trait changes are being verified.
  - **Localization**: missing translations and layout problems caused by long text are being reviewed across supported languages.

</details>

<details>
<summary><b>[📝Patch_Ver_0.0.90 Build#1] 1:1 Ranked Match (Beta) Season 0 & Stage Graphics Renewal (Released June 14, 2026) (Click)</b></summary>

### 🚀 Update Highlights

To heighten arena immersion, we prioritized stage visuals and environmental graphics updates. Alongside this, the core 1:1 competitive mode 'Ranked Match (Beta) Season 0' was launched, and enemy AI decision-making has been enhanced.

- #### 🏟️ Stage Visuals & Environmental Graphics Renewal
  - **Material & Texture Upgrades**: Fine-tuned reflectivity and texture tones for floors, pillars, and structural elements, capturing a heavy, ancient Colosseum aesthetic.
  - **Crowd Toggle Option**: Added a graphics settings option to disable spectators, ensuring optimal frame rates during intense combat on lower-spec hardware.

- #### 🏆 New System: Ranked Match (Beta) Season 0 Launch
  - **Rank Rating & Tier System**: Initial placement is determined after 5 placement rounds. Wins and losses scale rating points. Tier progression starts at Class 10 and moves up to Class 1 (Challenger), where players can accumulate points infinitely.
  - **Permanent Account Bonuses**: Ranking tiers grant permanent account-wide bonus points and stat buffs.
  - **Ranked Match AI Matchmaking**: Rated matchmaking pairs you with a suitable rival AI based on your rank tier.
  - **Matchup Confirmation (Confirm) Popup**: Matchups show a countdown overlay displaying the opponent's name, tier, and currently equipped build (traits, perks, contracts, stats). Empty slots are cleanly marked as "None."
  - **Ranked Hub Transition**: Skipped standard stage settlement sequences for faster pacing, redirecting players back to the hub with an immediate rank update notification popup.
  - **Local Leaderboard Progression**: AI rivals defeated during ranked play are permanently logged on local leaderboards. Matches between other background AIs are simulated, making the league feel alive.
  - **Difficulty-specific Ranks**: Leaderboard scores track independently across different game difficulty modes.

- #### 🧠 Enhanced AI Behavior & Learning
  - **Cognitive Learning & Combat AI**: Enemy AI now analyzes player habits more closely, executing guards, parries, and dodges with more human-like timing and tactical logic.

</details>

<details>
<summary><b>[📝Patch_Ver_0.0.82] Demo Build Registration, Guard/Stamina Rework & Class Combos (Released June 10, 2026) (Click)</b></summary>

### 🚀 Update Highlights

To deliver a deeper combat experience, we overhauled guard calculation logic and refined class-specific weapons and combo systems. 7 powerful new perks, dynamic enemy behavior trees, and structured stage difficulty progressions have also been added.

- #### 🛡️ Guard & Stamina System Overhaul
  - **Weapon Guard Attribute (GuardMult)**: Reworked the guard formula to highlight weapon identity and reduce over-reliance on parrying.
  - **Shield Guard**: Raised base damage reduction from 30% to 80% (max 90%), reducing guard stamina costs to 30% of blocked damage.
  - **Sword Guard**: Raised base damage reduction to 40% (max 50-60%), reducing guard stamina costs to 20% of blocked damage.

- #### ⚔️ Class Identity & Combo System Segmentation
  - **Warrior**: Can equip and swap 2 weapons in real-time, utilizing 1 light/heavy combo slot per weapon. Switching weapons provides immediate HUD visual feedback.
  - **Swordsman**: Limited to 1 weapon, but features instant combo swaps between 2 slots (light/heavy combo sets) with zero animation delay.
  - **Fighter**: Unarmed combat style, but gains 3 custom combo slots to string together devastating punches and kicks.
  - **Combo Damage Scaling**: Precision formulas apply custom multipliers to individual combo animations, adjusting final damage output.

- #### 🔮 7 New Perks & Balance Adjustments
  - **7 New Perks**: Adrenaline, Shield Bash, Berserker, Lucky Strike, Giant Slayer, Combo Master, and Armor Breaker are now available.
  - **Existing Perks Rebalanced**: Inferno explosion damage buffed. Bloodsucker lifesteal rates and Blood Pact lifesteal stats adjusted downward to match combat pacing.

- #### 🥊 Combat & Enemy AI Upgrades
  - **Chance-based Guard Break**: Striking guarded enemies has a fixed 10% chance to force a Guard Break regardless of their stamina (exclusive to player attacks).
  - **Guard Break Presentation**: Successfully guard-breaking an enemy triggers a slow-motion effect and stuns the target for 2.5 seconds.
  - **Parry Slow Motion**: Landing a perfect guard (parry) applies a brief time dilation to all combatants, giving players time to react.
  - **Knockback Physics**: Added force and angle-based physical knockback reactions on clean melee hits.
  - **Dynamic AI Behaviors**: Overhauled the low-HP loop where enemies repeatedly backpedaled. AI now intelligently mixes dodges, guards, and high-threat special attacks at low health.
  - **Removed Trait (Thorn Mail)**: Removed the frustrating enemy perk 'Thorn Mail' to accommodate low-HP player perk builds.

- #### ⚖️ Difficulty Progression & DDA Adjustments
  - **Special Enemy Spawn Delays**: Delayed spawn thresholds to smooth out the early game curve: Elite (St. 20), Epic (St. 30), Boss (St. 40), and Special (St. 50).
  - **Boss Ambush Protection**: Disabled random enemy ambush events during boss and named enemy stages.
  - **Dynamic Trait Scaling**: Reworked enemy trait/perk generation rules based on stage levels and player DDA indices across specific stage ranges (50+, 45-49, 38-44, 30-37, 20-29, 11-19, 1-10).

- #### 🎨 UI/UX Convenience Rework
  - **Lobby Menu Rework**: Unified the Character Info and Combo menus into a single 'Weapon Select & Equip Combo' interface.
  - **Real-time Stat Viewer**: Added a popup button in selection screens to check current stats, perks, and active traits in real-time.
  - **Tutorial Tooltips**: Added hover descriptions for icons and menus in the tutorial screen.
  - **Shortened Training Flow**: Closing the training popup now teleports players directly into the training room.

- #### 🔧 Core Bug Fixes
  - **Execution Animations**: Resolved the brief freeze following execution sequences for Warrior/Swordsman and fixed the interrupted hit-reaction montages for Fighters.
  - **Stun Animation Logic**: Corrected the stun animation trigger loop following a guard break.

</details>

<details>
<summary><b>[📝Patch_Ver_0.0.81] Emergency Bug Patch & System Stabilization (Released May 10, 2026) (Click)</b></summary>

### 🚀 Update Highlights

This update addresses urgent issues reported after the Steam Early Access launch and improves overall system stability. In addition, the project transitioned to the **TEAM NIRIZ development team** structure to accelerate development.

- #### 🔧 System Stabilization & Bug Fixes
  - **Normalization of Steam Achievement Integration**: To solve the problem where achievements were not immediately reflected in the UI even after being unlocked, we introduced a **Popup Queue System**.
  - **Reinforcement of Trait Saving Logic**: To prevent data from being lost intermittently when closing the game after selecting traits in the Hub, we added **real-time synchronization and forced save points**.
  - **Physics Engine Optimization**: Fixed the phenomenon where corpses would tremble abnormally or float in the air in a ragdoll state after defeating an enemy in certain situations, and strengthened ground alignment correction.
  - **Training Map Improvement**: The attack control function of the training dummy has been reinforced, and the bug where the health bar was not normally updated when the dummy respawned has been fixed.

- #### ⚖️ Shop Balance & Convenience Improvements
  - **Adjustment of New Class Purchase Costs**: To provide a more diverse play experience, the purchase costs for classes have been significantly reduced. (Fighter: 1,000 Gold / Swordsman: 10,000 Gold)
  - **UI Control Stability**: We perfectly support the closing function via the **ESC key** in all sub-widget windows and solved the presentation error where the screen would flicker when previewing skills.
  - **Perk Scroll Added**: To solve the problem where the list would go off-screen if there were many perks owned, we introduced a scroll function.

- #### 🤝 Transition to TEAM NIRIZ Development Team System
  - **New Developer Joined**: As of May 10th, a professional client developer has joined to establish a faster and more stable development environment.

</details>


<details>
<summary><b>[📝Patch_Ver_0.0.80] TOOSIN: Detailed Update Information & Steam Early Access Launch (May 6, 2026) (Click)</b></summary>

### 🚀 Update Highlights

This Steam Early Access launch update introduced a major combat-system renewal, new classes, and system optimization. The new Fighter class and hidden Swordsman class joined the roster, alongside class unlocks in the shop, character switching upon revival, official Japanese support, and expanded combat analysis.

- #### 👤 Introduction of New Characters & Class System
  - **Integration of Class System**: For continuous update expansion in the future, the class system has been fully integrated into all characters in the game. (Default character: Warrior)
  - **New Classes Added**: The **'Fighter'** class using powerful gauntlets and the hidden class **'Swordsman'**, which will target the hearts of hidden challengers, have been newly added.
  - **Hidden Character Unlock**: Hidden characters are unlocked upon achieving specific hidden achievements in the game. After unlocking, they can be purchased with in-game gold in the shop and played.

- #### ⚔️ Major Renewal of Combat System & Animations
  - **Renewal of Enemy Motions**: All enemy character motions have been made cleaner and more threatening, and the flow of some attack patterns has been improved.
  - **Execution Presentation Improvement**: The execution presentation motion camera and character movements have been improved to be even smoother, and the hitting collision and judgment have been significantly modified accordingly.
  - **Large Introduction of New Animations**: By adding more than 50 types of new high-quality animation sequences, we have implemented an even more dynamic and crunchy combat feel.
  - **Increase in Attack Judgment Height**: Considering that the appearance mesh increases proportionally as the rank of the enemy (Elite/Epic/Boss) increases, the attack judgment height has been precisely adjusted accordingly.

- #### 🏟️ Arena & Mock Combat/Training Improvements
  - **Arena Rule Change**: The departure rule has been changed so that you cannot arbitrarily leave in the middle of a stage arena, inducing a tense and true match.
  - **Mock Combat Bug Fix**: Perfectly fixed a long-standing bug where the enemy rank was incorrectly entered as [Normal] during Mock Combat mode, but monsters of Elite or higher actually spawned, causing achievements to be incorrectly achieved.
  - **Training Bot Improvement**: Fixed a dummy bug where the bot would intermittently raise its guard during a flurry of hits, and shortened the bot's attack mode cycle to 1 second to create an efficient combat practice environment.

- #### 🏔️ Environment & Level Design Updates
  - **Reinforcement of Dynamic Stage Presentation**: Applied visual and auditory cinematic presentations where the dedicated arena BGM and main hub theme/lighting/design change dynamically when reaching certain core stages.
  - **Weapon Consistency**: Directivity and visual consistency have been increased by unifying enemies to appear wearing only fixed weapons suitable for their assigned unique class.

- #### 🌍 System Optimization & Convenience Option Reinforcement
  - **Official Japanese Support**: For global expansion, official high-quality Japanese (日本語) translation has been established.
  - **Combat Balancing**: Stats and health values of some normal-rank enemies that were set abnormally high were lowered, and overall pacing was adjusted.
  - **Charging Error Fix**: Fixed a critical system logic error that occurred when unlocking Charge-type traits.
  - **New Setting Options Added**:
    - Added an option to turn On/Off the 'Red Notification Mark' display that appeared when acquiring new traits and perk cards.
    - Added an option to turn On/Off the 'Guidance Message' displayed on the screen at the end of each stage settlement.
  - **Minor Bug Fixes**: Completed known minor UI layout consistency and frame optimization work in parallel.

- #### 💾 Save File Migration Guide (Important!)
  - With the release of this update, the save file structure has been fully renewed and initialized. Those who wish to continue using existing save data, please apply the following guide.
  - **Path**: `C:\Users\Username\AppData\Local\Toosin\Saved\SaveGames`
  - **Change Method**: Change the names of the `ToosinGame.sav` and `ai_learning.sav` files in that folder to `TOOSINGAME_STOVE.sav` and `AI_LEARNING_STOVE.sav`, respectively. (However, please note that crashes may rarely occur due to save file changes, so we recommend back-up in advance.)

- #### 🔗 Related Live Community Links
  - **Official Stove Indie Notice**: [Stove Indie v0.0.80 Announcement](https://page.onstove.com/indie/global/view/13234666?boardKey=145641&combined=false)
  - **Steam Community Update Notice**: [Steam v0.0.80 Patch Notes](https://store.steampowered.com/news/app/4635530/view/693133974951691065?l=koreana)

</details>

<details>
<summary><b>[📝Patch_Ver_0.0.71] Platform Isolation & Global Optimization (Released April 20, 2026) (Click)</b></summary>

### 🚀 Update Highlights

In this version, we completely isolated the Stove SDK into preprocessor branches to prepare for Steam build submission and review, and further advanced the multi-language real-time translation panel. In addition, the nicknames of Tumblbug supporters have been fully implemented in the in-game credits.

- #### 🔌 Stove SDK Isolation
  - **Linker Error Resolved**: Introduced `#if WITH_STOVE` pre-processing to completely separate the Stove plugin so that compilation errors do not occur even in platform environments where the plugin is not activated or installed.
  - **Subsystem Lifecycle Stubbing**: Lifecycle methods (`Initialize`, `Deinitialize`) have been stubbed to link normally from the outside so that normal execution is possible even when the plugin is not in use.

- #### 🌐 Real-time Localization & UI Fixes
  - **Diversification of NSLOCTEXT**: Changed the structure so that Mock Combat result windows and core in-game text respond in real-time when options are changed.
  - **TSRankingWidget Fix**: Perfectly fixed linker errors caused by Stove ranking-related methods when compiling Steam builds.

- #### 📦 Build Deployment Automation
  - **SteamPipe Script Application**: Completed the configuration of `app_build` and `depot_build` VDF deployment automation for smooth Steam build review and upload.

- #### 💖 Supporter Nickname In-game Reflection Completed
  - **Tumblbug Nickname Entry**: Successfully listed the precious nicknames of supporters in the in-game credits and 'Developer's Note' section. (All 49 respondents applied)

</details>

<details>
<summary><b>[📝Patch_Ver_0.0.70] Introduction of New Mode 'Mock Combat' & Overall Balance Adjustment (Released April 15, 2026) (Click)</b></summary>

### 🚀 Update Highlights

In this update, we have urgently introduced the 'Mock Combat' mode where players can hone their combat skills and test their specs without risk, and significantly increased the player's default maximum stamina to maximize control feel.

- #### 🎲 New Mode: Mock Combat Introduced
  - **Safe Practice Environment**: Added 'Mock Combat' mode where you can directly face enemies of the current stage without the risk of gold or experience deduction, facilitating tactical testing and practice.

- #### ⚔️ Stamina Significantly Increased to 200
  - **Exciting Flow**: By boldly increasing the maximum stamina from **120** to **200**, we guarantee a crunchy action tempo where the flow of attack-guard-dodge is not interrupted.

- #### ⚖️ Balancing & Difficulty Rearrangement
  - **Pacing Control**: Core stats of enemy characters of Epic rank or higher were reinforced, and the bonus acquisition ratio for round-clear gold and experience was slightly lowered for long-term growth.

- #### 🐛 Emergency Fixes for System Bugs
  - **Blocking Save Overlap Crashes**: Originally solved critical runtime crashes that occurred intermittently during the process of overwriting save files.
  - **Mock Combat Save Supplement**: Fully corrected logic bugs where acquired data was incorrectly aggregated and lost when exiting via `ESC` -> `Exit` during Mock Combat.
  - **Ranking ID Identification Fix**: Perfectly fixed the identification filter problem where only one's own ranking data was listed instead of the entire ranking when updating real-time ranking information.
  - **UI Blur Presentation Improvement**: Improved the visuals so that a soft Gaussian Blur effect is applied to the entire screen area when selecting perks after winning an arena stage.
  - **Live Emergency Notice Link**: [Stove Emergency Patch Detailed Information](https://page.onstove.com/indie/global/view/13058144?boardKey=145641&combined=false)

</details>

<details>
<summary><b>[📝Patch_Ver_0060 (Pre-release Build)] Stove SDK Integration & Final Polishing (Released April 08, 2026) (Click)</b></summary>
  
### 🚀 Update Highlights 

### This was a major update ahead of the STOVE Early Access launch. It completed STOVE SDK integration, final quality polishing, and the required review submission work.

- #### 🔧 Stove Service & System Integration
- **STOVE SDK Integration Completed**: Finished integrating the Stove Achievement and Leaderboard SDKs. Now your glorious records will be recorded in real-time on your Stove profile.
- **Achievement System Bug Fix**: Secured stability by fixing a long-standing bug where achievements were not triggered under specific conditions.
- **Optimization**: Optimized hardware resource usage to maintain stable frames even in large battlefield environments.
  
- #### 🎭 Battlefield & Visual Upgrade
- **Main Arena Map Change**: The Main Arena battlefield map, the core of 'Toosin', has been renewed to be more intuitive and colorful. Compete in a true match in the new arena.
- **Graphics & Cinematic Improvement**: Maximized the immersion of the game by modifying graphic quality and adding new cinematic presentations.
- **Combo System Presentation**: Improved the guide videos in the combo shop by modifying them to match the latest build, making it easier to learn skills.
  
- #### 🔧🌍 Global Localization & UI/UX Refinement
- **Multi-language Support (Korean/English)**: Fully introduced Korean and English translation functions. You can check all dialogues and system messages in the game in each language.
- **UI Anchor & Layout Optimization**: Redesigned anchor settings for all UI to prevent UI breakage according to text length during translation.
- **Option Menu Bug Fix**: Improved user convenience by fixing a bug where some setting values were saved abnormally.
  
- **[📝 A Word from the Developer]** We did our best until the last moment to provide the most perfect experience for Stove users and Tumblbug supporters. We look forward to meeting you soon in the Stove Store!

With this build, even the submission for review of the usage rating has been completed. We ask for your support. 
</details>

<details>
<summary><b>[📝Patch_Ver_0051] Beta Update Announcement - New Classes & Convenience Improvements (Released March 30, 2026) (Click)</b></summary>

### 🚀 Update Highlights
In this version, along with the **Beta 0.0.51** update, convenience improvements reflecting user feedback and new character classes have been added!
### 🔧 System & Graphic Improvements
- **Graphic Optimization**: Fixed a bug where set graphic options were not properly reflected in the game. You can now enjoy 'Toosin' in a more pleasant environment.
- **Field of View (FOV) Camera Option**: To resolve the stuffiness of the third-person perspective, we added a field of view camera adjustment option to the setting menu.
- **Reinforcement of Stability**: Solved a stat bug where the strength of the character changed abnormally due to random events, enabling fair game progress.
### 🎭 New Character Details
- **Ambush**: A class that changes the flow of the battlefield with unpredictable attack methods.
- **Special**: A special talented person with powerful firepower and a unique skill set.
### 🌍 Global Response
- The groundwork for simultaneous Korean and English support was completed, and translation quality continued to improve in later public builds.

</details>
<details>
<summary><b>[📝Patch_Ver_0050] Random Event System & In-game Content Reinforcement (Released March 25, 2026) (Click)</b></summary>
  
This **Ver.0.0.50** update includes the introduction of a **Random Event System** to relieve the boredom of combat, a full renewal of the UI, and convenience reinforcement and bug fixes.

---

### 🎲 1. 4 New Random Events Added
- **Mysterious Merchant**: Appears with a certain probability after a stage ends, and you can purchase permanent stats with gold.
- **Blood Pact**: At the start of a stage, you can strongly reinforce other stats at the cost of your specific stats.
- **Ambush**: A new enemy enters from the audience during battle, creating variables.
- **Challenge Event**: You can directly select the enemy rank for the next stage and acquire special rewards accordingly.

### 🎨 2. Full UI Renewal & UX Optimization (UI/UX Overhaul)
- **Application of Latest Design**: The entire UI design has been newly renovated reflecting the latest user-friendly trends.
- **Convenience Improvement**: Intuitively improved the buff list, contract list display, and button hover UI.

### ⚙️ 3. Precision of Combat Balance & Logic
- **Attack Speed Synchronization**: Modified the logic so that bonus values are accurately summed based on the weapon's default attack speed.
- **Gold Carry-over System**: For the fun of roguelike, we added a system to receive 50% of the gold possessed before death to the next round.
- **Enemy Trait System**: All enemies spawned after a certain stage possess unique traits to add to the fun of strategizing.

### 🐛 4. Major Bug Fixes & Stabilization
- **Trait Bug Fix**: Solved the problem where the enemy's lifesteal trait was not triggered.
- **Normalization of AI Learning Records**: Modified the recording system so that the current progress stage and cumulative rounds are not confused.
- **Achievements**: Officially launched the achievement system for various play goals.

---

🚀 **Roadmap at the time**: after this update, development moved into final polishing for the STOVE and Steam Early Access launches.

</details>
<details>
<summary><b>[📝Patch_Ver_0040] Global Ranking System & System Stabilization (Released March 21, 2026) (Click)</b></summary>
  
This **Ver.0.0.40** update focused on introducing a **Ranking System** for global competition and **System Stabilization** and polishing work to increase the perfection of the game.

---

### 🏆 1. Global Ranking System Introduced (Steam/Stove Leaderboard Integration)
- **Real-time Data Synchronization**: By introducing the unique leaderboard systems of Stove and Steam, you can compete for stage clear records and rankings with players around the world.
- **Platform Account Linking**: Without a separate back-end signup, you are automatically logged in in real-time with your Stove/Steam account to manage save data and participate directly in the competition.

### 🛠️ 2. System Stabilization & Final Polishing (Issue #61, #65)
- **AI Behavior Optimization**: Implemented even more exciting combat by applying DDA-based responsive dodging and a guard time limit (5s) for shield enemies.
- **Combat Bug Fix**: Solved the phenomenon of ragdoll freezing upon death and reinforced the invincibility logic (2s) and dedicated presentation when the revival trait is triggered.
- **Visual & Sound**: Optimized high-quality blood effects, stabilized intro videos, and improved hit sounds and BGM mixing balance.

### ⚙️ 3. Subdivision of Graphic Options & UX Convenience
- **Screen & Frame Options**: V-Sync and Frame Limit options have been added.
- **DLSS & Ray Tracing**: Fixed bugs in the latest upscaling technology and secured stability when setting Ray Tracing.
- **User Custom Settings**: Increased convenience by adding options to adjust detailed sound volume, mouse sensitivity, key bindings, and floating text size.

---

🚀 **Next Step (Roadmap)**: The final phase of MVP-8, featuring random stage events, AI battle observation mode, weapon purchase system, and Steam SDK integration, will be prepared.

</details>
<details>
<summary><b>[📝Patch_Ver_0030] Demo Version Release / DLSS 4.5 Support (Released March 18, 2026) (Click)</b></summary>

This **Ver.0.0.30 Beta** update is the official demo release version of 'Toosin'. The key features are the completion of the sound system, the dramatic improvement of AI intelligence, and performance optimization through the installation of the latest technology, **DLSS 4.5**.

> [!IMPORTANT]
> **Demo Test Difficulty Guide:** Considering that this demo version is an environment where permanent stat acquisition is impossible, for smooth testing and balance verification by players, **the overall game difficulty has been significantly lowered** compared to the original plan.

---

### 🔊 1. Advancement of Sound Manager (Sound System Overhaul)
- **Intelligent Sound Control by Situation**:
  - New logic for `IsCombatAllowed()` and `IsCrowdAllowed()` has been established to optimize sound playback suitable for each location such as the Hub, Arena, and Training Grounds. (Solved the phenomenon where crowd sounds were heard in the Hub or hit sounds were not heard in the training grounds)
- **Differentiation of Parry Success SFX**:
  - Separated shield parry and normal weapon parry sounds to increase the intuitiveness of feedback.
- **Improvement of Crowd Cheer System**:
  - Added urgent crowd cheering sounds when a character's HP drops below 50% / 20%, maximizing the tension of battle.

### 🧠 2. Intelligent Enemy AI & Pattern Prediction (Advanced AI & Prediction)
- **Frontal Dodge Added**:
  - The enemy AI does not simply run away but performs aggressive evasion maneuvers that target the player's gaps and dig in frontally.
- **Precision of DDA (Difficulty Adjustment) Algorithm**:
  - Depending on the player's skill, the enemy's aggressiveness, guard frequency, etc., change more naturally and organically.
- **Establishment of Pattern Prediction System Foundation**:
  - Analyzed the player's repetitive actions (forward dash, etc.) to lay the foundation for logic that allows the AI to respond in advance.

### 🎬 3. Execution System & Presentation Polishing (Execution & Visuals)
- **Improvement of Execution Sequence Timing**:
  - Removed the slow motion at the moment of the last hit and implemented the execution motion to operate.
- **Root-Motion Tracking Angle Limit**:
  - To prevent the phenomenon where the character rotates 180 degrees abnormally during an attack to chase the target, the allowed rotation angle was limited to 60 degrees to implement natural movement.

### ⚙️ 4. System Convenience & Technical Updates (Graphics & Options)
- **Implementation of Graphic Option Function**:
  - A function to directly adjust some graphic qualities such as textures and shadows through the in-game setting menu has been added.
- **DLSS 4.5 Installation & Frame Generation**:
  - By supporting NVIDIA's latest upscaling technology, **DLSS 4.5**, we secured high-quality visuals and high frames simultaneously.
### ⚖️ 5. Growth Reward & UI Visualization Reinforcement (Growth & UI)
- **Clear Specification of Rewards in Round Settlement UI**:
  - Added **'Trait Point (TP) +1'** reward text clearly in the settlement window when clearing a stage.
  - Doubled the stat increase values upon level-up (**HP+10, SP+6, ATK+2, DEF+1.0**) and improved it to reflect real-time in the information section at the bottom of the UI.
- **Adjustment of Growth Balance**:
  - Increased the accessibility of the demo version by adjusting the DDA difficulty weighting to be player-friendly (halved upon death, mitigated upward slope to 0.03f upon win streak).

</details>
<details>
<summary><b>[📝Patch_Ver_0020] Detailed Information for First Beta Version Release (Click)</b></summary>

This **Ver.0020** update is the first beta release of 'Toosin', focusing on improving user convenience and visual perfection. Along with a full renewal of the UI, it provides a stable game play environment by solving long-standing loading issues.
---

### 🎨 1. Full Renewal of UI Design & Korean Localization
- **All-in-One Korean Encoding Applied**:
  - Replaced all system and stat UIs, which were previously English-oriented, with Korean.
  - Applied the `NSLOCTEXT` standard specification to originally block text breakage according to the build environment.
- **Replacement with High-Quality Visual Assets**:
  - Replaced all design assets, such as widget backgrounds and button styles, with sophisticated images worthy of a beta version.

### 🎬 2. Combo Video Tooltip System Introduced
- **Preview Innovation**:
  - Established an asynchronous video tooltip system where users can immediately grasp the utility of a technology via video by hovering the mouse cursor over it before purchasing a combo in the shop.
- **Auto-Cleanup Logic**: Maintains a pleasant memory environment by immediately releasing media instances upon widget destruction.

### 🛠️ 3. System Stabilization & Bug Fixes
- **Infinite Loading Resolved**:
  - Secured game entry stability by exception-handling logic that failed to proceed to the next process when loading specific media sources failed.
- **ESC Integrated Closing Function**:
  - Applied a global input focus system that allows sequentially closing all layer widgets in the Hub with a single ESC key for user convenience.
- **Removal of Transition Map Flickering**:
  - Perfectly solved the flickering phenomenon where an unrendered map was exposed for 0.1 seconds just before cinematic playback after loading was completed through a loading screen-video synchronization logic.

</details>
<details>
<summary><b>[📝Patch_Ver_0011] Detailed Patch Notes (Click)</b></summary>

In this update, **[MVP-8] Presentation Polishing & Advancement of AI System** was focused on. Along with reinforcement of presentations such as the establishment of an intro skip system and introduction of loading scenes, we significantly upgraded the enemy's combat logic to create a more exciting action environment.
---

### 🎬 1. In-game Presentation & UI Visual Optimization

- #### Addition of Global Loading Widget:
  - Applied a full-screen loading widget when entering game play scenes and arenas to apply natural transitions and immersion improvement effects.
- #### Intro Video Playback & Skip Integration:
  - Completely finished integrating the in-game intro cinematic playback function.
  - A control skip module has been newly established that allows immediately skipping the intro video with **Spacebar** input when playing video during play.
- #### Addition of Hub UI AI Learning Panel:
  - establish visual flow of combat data by adding a dedicated button and text dialog guide to view the **'AI Learning Process'** within the main hub interface.

### 🎮 2. Advancement of Enemy AI Behavior & Improvement of Control Quality

- #### Active Movement & Guard Movement Logic:
  - Overhauled the monotonous pattern where enemies stood in a daze while being hit or with their guard up.
  - Now, enemies also actively **strafe (move via side-step, back-step, etc.)** without stopping even during guard maintenance or small hit animations to intelligently widen the distance.
- #### Frontal Dodge Added for Enemy AI:
  - Combat behavior logic where enemies, who previously only dodged backward or sideways based on the player's behavior, **boldly dodge into the player's arms (forward)** has been normally installed.
- #### Blocking Low HP 'Runaway' Loop:
  - Corrected a bug in the runaway logic where the opponent (AI), when their health was low, gave up attacking and repeatedly **dodged only to the outside of the arena**, focusing them back on the final match.

### 🤖 3. Difficulty System & Stat Bug Fixes

- #### Normalization of Weapon Attack Speed Bug:
  - Solved a serious bug where attack speed scaling (Multiplier) was not reflected at all when using weapon packs other than the existing Longsword.
  - With this, the **unique attack speed increase/decrease stat for each weapon is normally applied to both the player and the enemy AI**, significantly changing the tempo of combat.
- #### Fix for DDA (Self-Learning) Values & Stage Difficulty (Perk) Application:
  - Fixed an internal system error where DDA difficulty weighting values were not normally intervening in actual in-game data.
  - In addition to the existing difficulty increase proportional to the stage, we reformed the armament system so that the **enemy camp (AI) also appears equipped with random traits and perks** according to the stage rank and weight conversion upon starting.

</details>
<details>
<summary><b>[📝Patch_Ver_0010] Detailed Patch Notes (Click)</b></summary>

In this update, **[MVP-7] Elemental Effects (Systematization of Attributes) and establishment of Cinematic & Sound Manager** were completed. A deep attribute system leading from Fire, Ice, to Lightning, along with cinematic cutscenes, execution systems, and a sound manager that will increase the perfection of combat, have been fully established, concluding the grand journey of MVP-7.
---

### 🔥 1. Elemental Effects (Systematization of Attribute Effects)

- #### Attribute System & Trait Integration:
  - **Fire**: Applies continuous damage (DoT) to the target for a certain period to put pressure.
  - **Ice**: Slows down the movement and attack speed of the target to control the flow of battle.
  - **Lightning**: Additionally destroys the target's stamina (SP) upon hit to induce a guard break.
- #### Hitting Effect for each Attribute (Particle System):
  - Maximized visual hitting feel by adding red (fire), blue (ice), and purple (lightning) afterimages and crystal/electric particle effects specialized for each attribute.

### 🎬 2. Cinematic Cutscenes & Execution System (Cinematics & Executions)

- #### Intro & Arena Entry Cutscenes:
  - Sequence transition presentations for moving from the Hub to the Arena have been added.
  - A cinematic showing the tense confrontation between the player and the enemy just before the battle starts is played.
- #### Dynamic Execution Motion (Execution & Camera):
  - A unique execution montage (Finisher) for each weapon is executed when defeating a monster.
  - A dedicated camera walk is installed during execution, allowing you to appreciate more colorful and dynamic finish presentations.

### 🔊 3. Sound Manager & Funding Asset Preparation

- #### Final Polishing of Sound System:
  - Adjusted the balance between background music (BGM) and sound effects (SFX) and completed audio synchronization matching the cinematic presentations.
- #### Marketing & Funding Assets:
  - Finished preparing in-game presentation sources and cinematic cutscene data for filming high-quality trailers for Tumblbug funding.

</details>
<details>
<summary><b>[📝Patch_Ver_0006] Detailed Patch Notes (Click)</b></summary>

In this update, a large-scale build-up of **[MVP-7] Advancement of Combat Motion, Introduction of New Traits, and Critical System Bug Fixes** was carried out. With the addition of a new charge combat system and super armor trait, much more irregular and powerful action play has become possible, and we concluded the AI non-response bug and save combo rollback bug that were eating away at the play tempo.
---

### ⚔️ 1. Advancement of Combat Motion & Visual Effects

- #### AI Motion Malfunction Bug Fix:
  - Fixed the root-motion retargeting malfunction and twisting phenomenon that occurred when using animations missing the Root Bone, and fully activated root-motion.
- #### Addition of Dust Particle Effect:
  - To bring the feeling of intense combat to life, we inserted an effect where soil dust rises from the ground in accordance with the timing of the character's heavy movement or evasion maneuvers, improving the sense of presence.

### 💨 2. New Combat Trait System Activation

- #### Dodge Attack 1, 2 in connection with Forward Dodge:
  - Forward dodge that boldly digs into the enemy's arms is unlocked, and when practicing upper tiers, an immediate weapon slashing attack is automatically ignited immediately after the forward dodge motion ends.
- #### Charging System & Super Armor (Charge & Weapon Art):
  - A charge-and-hit (Charge Attack) mechanism triggered by holding down the mouse click has been newly applied.
  - The Epic trait of the 5th tier of the skill tree (Weapon Art 1, 2), which previously had a somewhat weak concept, has been replaced with a function to **completely ignore hitting stiffness (Super Armor) during light/heavy attack charging**, allowing strategic trade-off play.

### 🐛 3. Critical Bug Fixes

- #### Originally Solved Enemy AI Stamina Non-response (Idle):
  - Fixed a bug in the enemy logic where it could not transition to the rest phase even when stamina ran out, becoming a wide-eyed punching bag.
- #### Fix for Trait Value Non-application Data Parsing:
  - Tracked down and fixed text parsing errors where increases in defense (DEF), critical probability up, and health regen values were being discarded while being Split in the internal logic.
- #### Fix for Combo Save Rollback Issue upon Death:
  - Excluded the `CurrentSaveGame` entanglement where all owned economy should be reset according to the roguelike concept upon death in a stage, but the slots set in the shop window and hub were maintained as they were.

</details>

<details>
<summary><b>[📝Patch_Ver_0005] Detailed Patch Notes (Click)</b></summary>

In this update, a large-scale establishment of **[MVP-7] Introduction of Arena Crowd System, Intelligent AI Bug Fixes, and Sound Manager (TSSoundManager) system** was carried out. We fixed all the chronic AI bugs that were interrupting the tempo of combat, and introduced the crowd and BGM/SFX system that will greatly bring the sense of presence of the game to life for the first time.
---

### 🏟️ 1. Arena Crowd (HISM Crowd) System

- #### Optimized Placement of Crowd Mesh:
  - Applied HISM (Hierarchical Instanced Static Mesh) components to handle a large number of spectators, implementing a grand sense of presence in the Colosseum without dropping performance.

### 🧠 2. Combat AI (Enemy AI) Logic Modification & Bug Fixes

- #### Low HP Daze Phenomenon Fix:
  - Fixed a defect where the enemy character stood still when it had no health because it could not enter `DesperateMode` if the player's health was high.
- #### Blocking Infinite Retreat Loop:
  - Blocked the infinite retreat cycle where the `BTTask_StrafeEvade` task gave up attacking and only retreated through artificial cooldown manipulation.
- #### Solved Original Cause of Permanent Stamina Exhaustion (Idle):
  - Perfectly tracked and fixed a structural bug where the stamina delay timer was forcibly canceled immediately after a Dodge and was never recovered.

### 🔊 3. New Sound Manager (TSSoundManager) System Established

- #### Central Management Based on Singleton (Subsystem):
  - Established a sound core system based on `UGameInstanceSubsystem` so that songs are not cut off even when switching map scenes.
- #### Real-time Combat Sound (SFX) Hooks:
  - **Hub & Arena BGM / Crowd Cheering**: Linked waiting time for stage start, successful parry, and cheering sounds upon victory.
  - **Intuitive Hitting/Defending Sounds**: Separately plays sword flesh hit sound, shield hit sound, sword block guard sound, and parry impact sound.
  - **Action Sounds**: Applied hit groans, death sounds, and evasion wind sounds during stiffness (Stun).

</details>

<details>
<summary><b>[📝Patch_Ver_0004] Detailed Patch Notes (Click)</b></summary>

In this update, **[MVP-7] Active Combat Evasion (Dodge) System and- Intelligent AI & Large-scale Revision of Various Monsters**:
    - [New] **Round Start Taunt System**: Immersion enhanced by having characters play random emoticons or taunt animations during the 6-second waiting time after entering the arena.
    - [New] **Secured Entire Character Pool of 18 types**: Significantly expanded combat diversity by adding 15 new characters today.
---

### 💨 1. DODGE (Evasion Function) & Special Attack (Charge)

- #### Direction-based 4-way Evasion System (Root-Motion):
  - Performs evasion maneuvers optimized for the character's movement direction, not the camera direction, through `A / S / D + Shift` input. Maximized control feel by applying 3 types of dedicated montages suitable for situations such as rear distancing and left/right side-steps.
- #### Dodge Parry (Perfect Evasion) Function Added:
  - Established an advanced technique where if an enemy's attack touches in a very short moment immediately after starting evasion, damage is nullified and the flow can be taken along with a 'Dodge Parry!' effect.
- #### Implementation of Basic/Heavy Attack Charging Pattern:
  - A charge system has been completed that gathers energy by holding down the attack button and delivers a strike with even more powerful power and a long range upon release.
- #### Player Parry Reaction & Animation Optimization:
  - Improved hitting feel by completely modifying the previously awkward parry hit montage.

### 🧠 2. Smarter AI & MORE Enemy

- #### Subdivision of Enemy Character Types & Ranks (Rank System):
  - Escaped from the single class structure and subdivided enemy classes into Normal, Elite, Epic, and Boss. **Significantly expanded the entire character pool to 18 types (15 added today)** to provide a new environment each round.
- #### Round-Proportional Spawn Auto-Scheduler:
  - Established a sophisticated system to appear at every Epic (Stage 8) and Boss (Stage 12).
- #### Large-scale Renewal of Self-Learning AI (DDA):
  - Significantly expanded the DDA weight spectrum to a range of **-10.0 ~ +10.0** so that the enemy's aggressiveness, distance maintenance, guard frequency, etc., change more finely and extremely.
- #### Recognition of Player Heavy Attack & Response Evasion by Enemy AI:
  - Advanced the Behavior Tree so that the enemy AI recognizes the player's heavy attack with a long pre-delay and takes its own distance or evasion action.

### 🛠 3. Bug Fixes & Stabilization

- #### Resolved AI Sticky Phenomenon:
  - Solved the problem where the AI was excessively sticky to the player at the start of combat through supplementation of Optimal Range logic.
- #### Prevention of Long-range Dash Attack Double Hit:
  - By applying attacker-based debounce (0.25 seconds) during hitting judgment, we fundamentally blocked the phenomenon of overlapping damage in a single dash attack.
- #### Exception Handling for High-Rank Monster Non-spawn:
  - Established a safety device where if a monster class of a specific rank is missing, it is summoned from a lower rank instead, but stat scaling is applied appropriately for the rank.

</details>

<details>
<summary><b>[📝Patch_Ver_0003] Detailed Patch Notes (Click)</b></summary>

This update added a currency system, the core growth cycle, and laid the foundation for a combo system that designates custom actions. In addition, we created an ecosystem that can systematically increase game understanding by introducing an extreme punching bag training ground.
[📸 Jump to Result Images](#v0003-result-images)
---

### 💰 1. Economy & Shop System

- #### Introduction of In-game Combat Currency:
  - Players can earn gold, with stable difficulty scaling applied after defeating monsters and winning arenas, as settlement rewards. Acquired gold is partially left as account-affiliated currency even upon death via save files.
- #### Combo-only Shop Opened:
  - Through the hub store area, you can purchase and permanently own various weapon technology montage items (Quick Slash, Rising Strike, etc.) that can be used in the game in combo units.

### ⚔️ 2. Combo Modification

- #### Application of Weapon Diversification:
  - The shop and custom menu automatically recognize the player's current equipped weapon class (Normal one-handed weapon vs. Shield equipped setup) and expose only the montage items dedicated to that class.
- #### Establishment of Double Storage Base:
  - Storage space for shield and non-shield equipped combos is completely split into two and managed, blocking the combo disturbance phenomenon that occurs when swapping weapons.
- #### UI & Icon Output:
  - Individual motion icon images of the equipped animation set are intuitively output in my combo (`MyCombo`) window.

### 🛠 3. Full Renewal of Training Room (Training Remaster)

- #### Dummy Stat Full-Custom:
  - You can directly set the health/defense/attack of the training dummy punching bag through the menu window before entering.
- #### Live Control of Combat Indicators:
  - Along with processing floating damage text showing cumulative damage, a debug panel that back-calculates the dummy's current health and cumulative DPS in real-time has been newly established, enabling explosive combo training.
- #### Reinforcement of Fighting AI:
  - Escaped from the wall-facing punching bag and gave a living behavioral logic that repeatedly toggles random patterns of attack/guard every 3 seconds. When parrying successfully against this, a stiffness animation is normally played, and the mechanic has been reworked to respawn on the spot immediately after execution.

### 🛠 4. Full Renewal of User Interface (GUI Remaster)

- #### Full Renewal of User Interface:
  - Changed the user interface to be more visually comfortable.

<h3 id="v0003-result-images">🖼️ V0003 Result Images</h3>

#### [Main Menu]

<img width="2533" height="1164" alt="main" src="https://github.com/user-attachments/assets/8956c8ab-6617-49b6-a7b7-639b39dad36a" />

#### [Hub Level]

<img width="2523" height="1155" alt="hub" src="https://github.com/user-attachments/assets/15261b03-d285-4ce9-a7e5-3fc0bcbbf3ef" />

#### [Training Level]

<img width="2521" height="1156" alt="training" src="https://github.com/user-attachments/assets/ee4d99d1-9563-4572-afda-70bd6d7e75e2" />

#### [My Combo Menu]

<img width="2512" height="1051" alt="combo" src="https://github.com/user-attachments/assets/f2b018d3-6fcf-473c-88ba-83f8b9609674" />

#### [Stat Panel]

<img width="2491" height="1213" alt="stat" src="https://github.com/user-attachments/assets/c88f63f0-ba4f-487f-8e4b-2f455c383ee0" />

#### [Shop Menu]

<img width="2312" height="1046" alt="shop" src="https://github.com/user-attachments/assets/21bd49bb-bd5a-48c1-9bea-a4d59672ec89" />

#### [Arena Level]

<img width="2527" height="1217" alt="arena" src="https://github.com/user-attachments/assets/fd11ecd0-b79e-4801-b2ae-6367ab1355df" />

</details>

<details>
<summary><b>[📝Patch_Ver_0002] Detailed Patch Notes (Click)</b></summary>

Update notes for 0002 that significantly improved UI and convenience based on user feedback and introduced a meta-growth system, increasing the perceived quality of the combat system.
[📸 Jump to Result Images](#v0002-result-images)
---

### 1. Combat & Controls

#### 👊 Improvement of Close-range Hitting Reliability & Range Judgment

- #### Cause: Each weapon has a different range, and attack judgments are concentrated at the end of the weapon, causing a 'penetration phenomenon' when close.
- #### Solution: Introduced a **sphere-shaped auxiliary detection logic (120cm)** at the start of an attack.

#### 🛡️ Improvement of Guard Mechanism & Normalization of Rewards

- #### Guard Priority Granted: When inputting guard during an attack, it immediately transitions to a defensive posture.
- #### Guard Experience Bug Fix: Experience bonuses for successful guards in the arena are now normally counted.

#### 🎥 Camera Lock-on & Control Feel Adjustment

- #### Improvements: Adjusted interpolation values so that camera movement feels smoother and more free even in the lock-on state.

---

### 2. Meta-Progression

#### 🌟 Introduction of Account Level & Permanent Stat Bonuses

- #### Account Leveling: **10% of the in-game EXP acquired each round is accumulated as account experience (Account EXP)**.
- #### Permanent Growth Factors: Acquire **HP +10, SP +6, ATK +2, DEF +1** and **Permanent Trait Points (PTP)** per account level.

#### 📜 Experience Acquisition Increase System

- #### Perk Reflection: Multipliers are normally applied when holding 'Experience Acquisition Increase' perks/traits.

---

### 3. User Interface & Visuals

#### 📊 Full Renewal of Exp Summary Window

- #### Numerical Readability Improvement: Check bonus experience with real-time animation and see a **summary of permanent bonuses** at the bottom.

#### ✨ Visualization of Trait Tree Requirements

- #### Solution: Clearly indicate the minimum required points and prerequisites for unlocking specific tier traits.

#### 🩸 Visual & Presentation Correction

- #### Screen Effects: Fixed blood screen anchor and optimized parrying reaction animation speed.

---

### 4. Optimization & Stability

- #### Graphic Option Optimization: Supplemented test build settings and secured frame stability.

---

<h3 id="v0002-result-images">🖼️ V0002 Result Images</h3>

#### [Main Menu]

![Main](https://github.com/user-attachments/assets/10dcf699-27f7-43ed-8b81-279d7e3f9492)

#### [Hub Level]

![Hub](https://github.com/user-attachments/assets/97e0e98c-1aec-46d8-b25e-579f3db0d0b5)

#### [Weapon Select]

![weapon select](https://github.com/user-attachments/assets/cfc7659c-c080-40f6-b2d9-9547c7f48db0)

#### [Trait Tree]

![Trait](https://github.com/user-attachments/assets/25368513-6d29-4d91-87a4-5b5eeae2f8b3)

#### [Perk System]

![Perk](https://github.com/user-attachments/assets/3035604e-9ade-4c5c-9438-aa7b826c7e09)

#### [Stat Panel]

![Stat](https://github.com/user-attachments/assets/9fca4b7c-f78c-428d-a1c9-fcdddf0b84bd)

#### [Perk Selection Card]

![Perk Select](https://github.com/user-attachments/assets/1dac5024-fe85-4fda-a6f6-8179910ca7ff)

#### [Round Summary UI]

![Round Summary](https://github.com/user-attachments/assets/6efd1fad-f0af-451a-af09-7937242a8962)

</details>

# TOOSIN 📝 Developer's Notes

---

<details>
<summary><b>[📝Dev_Ver_0050] View Planned Patch Details (Completed) (Click)</b></summary>
  
## 📋 Task List

### 🏆 1. PlayFab Ranking & Achievement System (Completed Record)
- [x] **Global Ranking**: Completed implementation of leaderboards for stage clear count and account level.
- [x] **Achievement System**: Established a system for popups and data recording upon achieving specific conditions.

### 🎲 2. Even More Colorful In-game Adventures (Phase 2)
- [x] **2.1 Random Stage Event Generation**: 
  - Random encounter logic for Mysterious Merchant, Blood Pact, Enemy Ambush, etc.
- [x] **2.2 Addition of New Enemy Characters & Traits**: 
  - Enemy-only perk system and information display at the bottom of the health bar.

### 📢 3. Marketing & Funding (Completed Record)
- [x] **Tumblbug Funding**: Completed from March 13 to April 13, 2026.
- [x] **Official Video Production**: Official gameplay and cinematic videos were produced and published.

</details>

<details>
<summary><b>[📝Dev_Ver_0011] View Planned Patch Details (Completed) (Click)</b></summary>

## 📋 Task List

### 🎬 1. In-game Presentation & UI Improvement

- [x] **Video Playback & Skip Integration**: Finished establishing an immediate video skip mechanism based on in-game intro video playback function insertion and Spacebar input.
- [x] **Global Loading Display**: Activation of a cut frame loading widget to hide delays occurring during map transitions.
- [x] **Visualization of AI Learning Process**: Added a dedicated button (`AILearningLogButton`) and dialog panel to grasp the learning process of recent battles in the hub UI module.

### ⚔️ 2. Active AI Behavior Logic & Combat Flow Inspection

- [x] **Frontal Dodge Installed**: Added a behavior node where enemy AI boldly digs into the front (arms), not simply dodging backward/sideways from player attacks.
- [x] **State Movement Fixed (Freeze on spot) Fix**: Renewed monster movement constraints to actively strafe (move) and press by limiting AI `StopActiveMovement` calls in guard, waiting, and hit states.
- [x] **Blocking Runaway (Low HP Retreat) Loop**: Overhauled the behavior tree branch where the enemy, in a pinch state (dying), did nothing and repeatedly ran away backward infinitely.

### ⚙️ 3. Combat System Balancing & Scaling Supplement

- [x] **Normalization of Weapon Attack Speed Multiplier**: Fixed a combat component bug where attack speed increase/decrease values for special weapons (other than Longsword) were not normally applied to both players and enemy AI and were ignored.
- [x] **DDA Learning Weight Integration Fix**: Solved the data entanglement phenomenon where cumulative difficulty adjustment correction values in the game were not reflected in the actual spawning actors.
- [x] **Introduction of Enemy Boss Scaling (Perk)**: Armament system reformed so that the spawning enemy also appears with random traits and perks like the player, proportionally to the difficulty DDA and stage breakthrough count, ensuring an unreasonable strength.

</details>

<details>
<summary><b>[📝Dev_Ver_0010] View Planned Patch Details (Completed) (Click)</b></summary>

## 📋 Task List

### 🔥 5. Elemental Effects (Systematization of Attribute Effects)

- [x] **Attribute Type Definition & Trait Integration**: Installed Fire (DoT), Ice (Slow), and Lightning (SP destruction) gimmicks.
- [x] **Hitting Effects & Particles for each Attribute**: Added colorful visual afterimages and effects matching each attribute.

### 🎬 6. Cinematic Cutscenes & Execution System (Cinematics & Executions)

- [x] **Combat Intro & Cutscenes**: Cinematic presentation showing the encounter with the enemy before each round starts.
- [x] **Dynamic Execution**: Unique execution montages and dedicated camera presentations for each weapon when defeating an enemy.
- [x] **Sound Manager Establishment**: Finished BGM and sound effect full placement and control system.

</details>

<details>
<summary><b>[📝Dev_Ver_0004] View Planned Patch Details (Completed) (Click)</b></summary>

## 📋 Task List

### 💨 1. DODGE & Special Attack (Charge)

- [x] **Systematic Direction-based Evasion System**
  - S + Shift: Rear Evasion
  - A / D + Shift: Left/Right Lateral Evasion
  - Applied 3 types of accurate evasion montages based on root motion, not relying on existing camera controls.
- [x] **Enemy AI Feedback Evasion Integration**
  - Expanded AI nodes so that enemy characters can also recognize powerful player attacks and use evasion themselves.
- [x] **Implementation of Basic/Heavy Attack Charging Pattern**
  - Upon trait unlock, charge montage (energy gathering) loop plays when holding mouse left/right click.
  - Collision link configuration where enhanced hitting technology is triggered upon click release.

### 🧠 2. Smarter AI & MORE Enemy

- [x] **Enemy Character Spawn Method & Rank Subdivision**
  - Escaped from the single AI structure and registered multiple enemy character Blueprints in the pool. (**Secured 18 types in total**)
  - Wave spawns separated into Normal, Elite, Epic, and Boss ranks according to stage progress.
- [x] **Large-dimensional Renewal of Self-Learning AI (DDA) Algorithm**
  - Significantly expanded the weight spectrum itself from **-10.0 to +10.0** or more, and subdivided distance maintenance habits, guard/parry frequency, hitting aggressiveness, etc., into branch behavior patterns.
  - Aimed for a natural difficulty curve by securing human-like AI daze routines or repeated long-range checks when weights drop low.

</details>

<details>
<summary><b>[📝Dev_Ver_0003] View Planned Patch Details (Completed) (Click)</b></summary>

## 📋 Task List

### 💰 1. Economy & Shop System

- [x] **Currency (Money) Function Introduced**
  - Added logic to acquire a certain amount of currency upon each battle victory.
  - Linked saving and loading of acquired and consumed currency (utilizing `CurrentSaveGame`).
- [x] **Hub Shop UI Established**
  - Implemented exhibition and purchase functions for combo animation sequence items in the shop.

### ⚔️ 2. Combo Customization Setting (Combo Modification)

- [x] **Combo Slot UI (`WBP_ComboEditor`) Implemented**
  - Right panel: Visualization of player's current stat information.
  - Left panel: Listing of combo animation sequences for the weapon currently possessed (Light attack 1~3 hits / Heavy attack 1 hit).
  - Provided visualization of the selected motion's combo configuration (linked with video/preview function).
  - Separated dedicated slot UI and usable combo restrictions for each weapon type.
- [x] **Dynamic Animation Montage Assembly Logic Implemented**
  - Implemented UI logic to drag and drop animation sequences possessed after purchasing in the shop into the COMBO 1, 2, 3 slots of the weapon.
  - Implemented to trigger as actual attack motions by having a single montage concatenated and combined according to custom slot settings at runtime.

</details>

---

We will continue to be a Toosin that develops based on your precious feedback. Thank you!

*Toosin Development Team*
