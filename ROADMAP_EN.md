# TOOSIN Development Roadmap

> Last updated: July 30, 2026  
> This is a public development roadmap. Scope and ordering may change as stability testing progresses.

## Current Status

**TOOSIN** is currently available in Early Access and is preparing to leave Early Access in August 2026.

| Milestone | Target | Status |
|---|---:|:---:|
| STOVE Early Access | April 17, 2026 | Complete |
| Steam Early Access | May 6, 2026 | Complete |
| Ver.0.0.90 Build #1 · Ranked Beta Season 0 | June 14, 2026 | Complete |
| Version 1.0 Beta | Early to mid-August 2026 | In preparation |
| Version 1.0 Full Release · Early Access graduation | Late August 2026 | Planned |

## Milestones So Far

### April 2026 — STOVE Early Access

- Released the core roguelite combat loop and stage progression
- Established the weapon, combo, trait, shop, and random-event foundations
- Prepared achievements, leaderboards, saves, and platform-specific distribution

### May 2026 — Steam Early Access

- Prepared the global Steam build and demo distribution
- Expanded classes and weapon play styles
- Improved guard, stamina, hit reaction, knockback, and other core combat systems
- Refined localization and UI flows, including Korean, English, and Japanese

### June 2026 — Ranked Beta Season 0

- Added 1v1 Ranked, placement matches, rating points, and tiers
- Added opponent-build information, match presentation, and leaderboard flows
- Improved arena visuals and graphics options
- Tuned enemy guard, parry, dodge, spacing, and combat pacing

## Version 1.0 Scope

The following areas are being developed and validated for the Version 1.0 beta and full release. The final package may change based on beta results.

### Permanent Progression and Stage Rewards

- Rework rewards for stages ending in 3, 7, and 0
- Keep unlocked weapons, combos, class appearances, and special abilities after reincarnation
- Prevent duplicate grants of permanent rewards already owned
- Store Play Points as a permanent account-level resource
- Reset traits on death while refunding the Play Points invested in them

### Builds and Combat

- Seven special abilities and additional build combinations
- Extend standard weapon enhancement up to +30
- Class advancement and a Combat Power display
- Rebalance the attack-speed cap, weapons, traits, and stage scaling
- Improve hit, guard, parry, dodge, camera, and combat feedback

### AI and Locomotion

- Improve combat decisions by combining Behavior Trees, player-pattern statistics, and adaptive difficulty adjustment
- Tune spacing, attack selection, guard, dodge, parry reactions, and pattern variety
- Improve facing, strafing, and orientation-warping locomotion for players and enemies
- Audit unfair reactions and combat degradation during long play sessions

> TOOSIN does not use generative AI or a continuously trained online model. Its adaptive combat system uses in-game player-pattern data and rule-based decisions.

### UI, Input, and Accessibility

- Rework the combat HUD, stage progress, traits, rewards, and Ranked screens
- Unify mouse and keyboard flows with Xbox-style gamepad controls
- Improve duplicate key assignment, widget focus, cancel input, and option apply/save behavior
- Make Combat Power, rewards, and save results easier to understand

### Content and Release Readiness

- Prepare Ranked Season 1 and the season transition
- Overhaul the tutorial and early-game guidance
- Focus testing on crashes, memory use, GPU compatibility, and long-session stability
- Validate save timing and permanent unlock data
- Synchronize the demo after the full release

## Version 1.0 Save Compatibility

Version 1.0 introduces a major save-structure change and **will not be compatible with earlier Early Access saves.** Before joining the beta or installing the full release, capture any records you want to keep and back up the existing save folder.

- Ranked Beta Season 0 records may be preserved under separate rules.
- Beta-to-release save compatibility will be confirmed in the beta announcement.
- Modified or unofficially replaced save files may not be eligible for support.

See the [Support Guide](./SUPPORT_EN.md) for backup locations and troubleshooting.

## After Version 1.0

Post-release priorities will follow real play data and community feedback instead of unannounced fixed dates.

- Urgent fixes for crashes, saves, input, and performance
- Balance updates for classes, weapons, traits, and enemy AI
- Ranked season operation and competitive-integrity improvements
- Accessibility, localization, and UI/UX improvements
- Evaluation of new combat content and modes

Features and dates that have not been officially announced are not guaranteed.

## Official Channels

- [Steam Store](https://store.steampowered.com/app/4635530/TOOSIN/)
- [Steam News](https://store.steampowered.com/news/app/4635530)
- [Official Website](https://teamniriz.com/)
- [Discord](https://discord.gg/EHMwJSjWpA)
- [GitHub Issues](https://github.com/rhwjdtjs/Toosin_Public/issues)
- [Support Email](mailto:support@teamniriz.com)

---

[한국어 로드맵](./ROADMAP.md) · [Support Guide](./SUPPORT_EN.md) · [Changelog](./CHANGELOG_EN.md)
