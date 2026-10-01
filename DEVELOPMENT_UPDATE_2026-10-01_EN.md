# TOOSIN 1.4 preparation

As of October 1, 2026.

[한국어](DEVELOPMENT_UPDATE_2026-10-01_KR.md) · [Game overview](README_EN.md) · [Roadmap](ROADMAP_EN.md)

TOOSIN 1.4 is in preparation. This repository contains public update records through 1.3.1; the work below describes the development scope for 1.4. A release date has not been confirmed.

## Work in progress

| Area | Work |
|---|---|
| Hub and UI | Mode dashboard, equipment and stat screens, event windows and option layouts |
| Appearance and class | Separate appearance and class selection; review new appearances with the three existing classes |
| Combat and AI | Attack, movement and dodge animations, equipment attachment, weapon contact, behavior statistics and AI decisions |
| Saving and records | Equipment, unlocks and learning data persistence, reapplication and ranking displays |
| Localization and input | Six-language text and layouts, menu focus and controller input paths |

Codex and Claude assist implementation, debugging and documentation. Proposed changes are checked against source, assets, builds and test results before being integrated. Combat AI itself uses in-game behavior statistics and rule-based decisions.

## Verification recorded

Development records include Editor and Game development builds, automated checks and runtime captures using isolated save copies. Selected menus have been checked in multiple languages and resolutions. Equipment persistence after restarting, AI learning save and restore, and combat actions have also been checked under stated conditions.

Results are interpreted with their execution conditions. Implementation in source, behavior observed at runtime and changes distributed to players are recorded separately. Passing an automated check or a selected screen review does not establish the quality of every play path.

## Remaining checks

- Full cooking and packaging, including assets and localization in the package
- Physical controller play and remaining screen, language and resolution combinations
- Platform reconnection and selected record-update paths
- Final demo checks for save isolation, progression limits and Ranked restrictions

The final change list will follow these checks. Separate release notes will record what is distributed, so the preparation items above should not be read as features already present in every installed build.

[1.3.1 public update record](V1.3.1_UPDATE_EN.md) · [Changelog](CHANGELOG_EN.md) · [Support and bug reports](SUPPORT_EN.md)