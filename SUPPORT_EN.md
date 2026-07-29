# TOOSIN Support and Troubleshooting

If you encounter a problem, please contact us through one of the channels below. Email is recommended for crashes, save issues, or reports that require private file attachments.

| Channel | Best for |
|---|---|
| [GitHub Issues](https://github.com/rhwjdtjs/Toosin_Public/issues) | Reproducible bugs, suggestions, and public progress tracking |
| [Support Email](mailto:support@teamniriz.com) | Logs, save files, videos, or other private attachments |
| [Discord](https://discord.gg/EHMwJSjWpA) | Quick questions, community reports, and announcements |
| [Steam Store](https://store.steampowered.com/app/4635530/TOOSIN/) | Current Steam build and official announcements |
| [Steam Discussions](https://steamcommunity.com/app/4635530/discussions/) | Steam-build questions and player-to-player help |

Official website: [teamniriz.com](https://teamniriz.com/)

## Before You Report a Problem

1. Fully close the game and the Steam or STOVE client, then start them again.
2. Verify or repair the game files through your platform client.
3. Update Windows and your graphics driver to a current stable version.
4. If you use mods, replaced files, or custom launch options, check whether the issue also occurs with the original files.
5. Record the build number and the approximate time of the problem.

## Bug Report Template

Copy this template into a GitHub Issue or email. You do not need to know every field; include whatever you can confirm.

```text
Title: [Bug] Describe the problem in one sentence

Platform: Steam / STOVE
Game version or build:
Date, time, and time zone:
Game mode and stage:
Input device: Keyboard and mouse / Gamepad model

Steps to reproduce:
1.
2.
3.

Expected result:
Actual result:
Frequency: Always / Often / Sometimes / Once

PC information:
- Windows version:
- CPU:
- GPU and driver version:
- Memory:

Attachments: Screenshot / Video / Log / Crash folder / Save file
```

Send files that may contain personal information to [support@teamniriz.com](mailto:support@teamniriz.com) instead of posting them in a public Issue.

## Logs and Save Files

The default locations for a packaged Windows build are usually:

| Data | Default path |
|---|---|
| Runtime logs | `%LOCALAPPDATA%\Toosin\Saved\Logs\` |
| Save files | `%LOCALAPPDATA%\Toosin\Saved\SaveGames\` |
| Crash reports | `%LOCALAPPDATA%\Toosin\Saved\Crashes\` |
| User settings | `%LOCALAPPDATA%\Toosin\Saved\Config\Windows\` |

Some builds may use `WindowsNoEditor` instead of `Windows` for the settings folder.

To open a path:

1. Press `Win + R`.
2. Paste the path and press Enter.
3. Zip the files created around the time of the problem and attach the archive.

Before changing any file, copy the entire `Saved` folder to another location as a backup. If the folder does not exist, run the game once and check again.

## Common Problems

### Crash While Entering a Stage or During a Long Session

- Verify the game files.
- Update to a current stable graphics driver.
- Temporarily disable recording tools, overlays, and GPU tuning utilities, then test again.
- Lower crowd visibility, shadows, and effects quality before retrying the same stage.
- Do not run the game in Windows 7 or Windows 8 compatibility mode.
- If the crash is reproducible, send the latest log, the `Crashes` folder, and the mode or stage you were entering.

### Save, Reward, or Permanent Unlock Is Missing

- Do not force-close the game while a reward or results screen is finishing or while returning to the hub or main screen.
- Confirm that platform cloud synchronization has completed.
- Before choosing the reward again, check the currently owned weapons, combos, appearances, and special abilities.
- Immediately after reproducing the issue, close the game normally and back up both `SaveGames` and `Logs`.
- Do not edit save files or manually merge saves from different devices.

### Gamepad, Key Binding, or Menu Focus Problem

- Connect the gamepad before launching the game and temporarily disconnect other input devices.
- On Steam, test both enabled and disabled Steam Input for TOOSIN.
- Restore input settings to their defaults, then assign the controls again.
- If `Esc` or gamepad `B` does not close an open popup or results screen, report the exact screen and attach a short video.
- If an old assignment remains after rebinding a duplicate key, include the bindings before and after the change.

### Options Do Not Apply or the Unsaved-Changes Prompt Repeats

1. Change the option, then select **Apply** followed by **Save**.
2. Exit the game normally and launch it again to confirm the value persists.
3. If the problem continues, close the game and back up the settings folder.
4. Rename `GameUserSettings.ini` to `GameUserSettings.backup.ini`, then launch the game. A default settings file will be generated.

Resetting the settings file can restore graphics, resolution, and some input settings to their defaults.

### Visual Artifacts, Low Performance, or Resolution Problems

- Switch between fullscreen and windowed mode.
- Change resolution scale, upscaling, frame limit, and vertical sync one setting at a time.
- On a laptop, confirm in Windows Graphics settings that the game uses the dedicated GPU.
- Restore forced driver-control-panel settings to their defaults and compare the result.

## Version 1.0 Save Compatibility

Version 1.0 introduces a new save structure and **will not be compatible with earlier Early Access saves.** Back up the `Saved` folder before updating and read the save policy in the beta announcement.

Whether beta saves will carry into the full release will be confirmed separately with the beta build. See the [Roadmap](./ROADMAP_EN.md) for the current release schedule.

## Privacy and Attachments

- Never send passwords, platform credentials, verification codes, or API keys.
- Redact Windows user names, email addresses, Steam IDs, and other identifying information visible in logs or screenshots.
- Do not upload personal save files to a public Issue; use support email instead.
- Do not attach suspicious executables or unofficial patches.

Reports are used to reproduce issues and improve the game. We cannot guarantee an individual reply or a specific fix date for every report, but complete reproduction details are extremely valuable when setting priorities.

---

[한국어 지원](./SUPPORT.md) · [Development Roadmap](./ROADMAP_EN.md) · [Changelog](./CHANGELOG_EN.md)
