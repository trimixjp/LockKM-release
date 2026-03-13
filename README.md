# LockKM

<p align="center">
  <img src="screenshots/icon.png" alt="LockKM Icon" width="128">
</p>

<p align="center">
  <strong>A macOS utility to temporarily lock your keyboard and mouse</strong>
</p>

<p align="center">
  English | <a href="README-ja.md">日本語</a>
</p>

---

Want to prevent your child from accidentally pressing keys or moving the mouse? Need to avoid unintended input during a presentation? Want to clean your keyboard or mouse without triggering accidental inputs? **LockKM** has you covered.

Lock your keyboard and mouse with a single click, and unlock instantly with a customizable key combo. Built-in auto-unlock ensures you're never locked out.

## Screenshots

| Settings | Menu Bar | Lock Overlay |
|:---:|:---:|:---:|
| ![Settings](screenshots/screenshot-1.png) | ![Menu Bar](screenshots/screenshot-2.png) | ![Overlay](screenshots/screenshot-3.png) |

## Features

### Device Locking

- **Keyboard Group Lock** - Disables keyboard and keypad input
- **Pointing Device Group Lock** - Disables mouse and trackball movement, clicks, and scrolling; pins cursor position
- **Selective Locking** - Choose which device group to lock
- **Simultaneous Lock** - Lock keyboard and pointing device at the same time — perfect for cleaning them all at once

### Unlocking

- **Custom Key Combo** - Unlock with any key combination (default: `⌘ ⇧ Esc`)
- **Key Combo Recorder** - Intuitively record and change your unlock combo in settings
- **Auto Unlock** - Automatically unlocks after a set duration (30 seconds to 1 hour)

### Safety Features

- **Safety Timer** - Countdown always visible during lock
- **Overlay HUD** - Displays remaining time and unlock key combo in the top-right corner
- **Forced Timeout** - Auto-unlock guarantees you're never permanently locked out
- **Restart Clears Lock** - Restarting your Mac automatically releases the lock

### Menu Bar Integration

- **One-Click Operation** - Toggle lock/unlock instantly from the menu bar
- **Status Indicator** - See lock state at a glance via icon color
- **Device Selection** - Change lock target devices directly from the menu bar
- **Dock-Free** - Runs as a menu bar app without occupying the Dock

### Multilingual Support

Supports 7 languages:

| Language | Code |
|----------|------|
| English | en |
| 日本語 | ja |
| Español | es |
| Français | fr |
| 한국어 | ko |
| 简体中文 | zh-Hans |
| 繁體中文 | zh-Hant |

### Schedule Notification

- **Cleaning Reminder** - Get notified via notification banner when a specified number of days have passed — a reminder to clean your keyboard and mouse

### Other

- **Launch at Login** - Register as a macOS login item for automatic startup
- **Lightweight** - Minimal resource usage while running in the background

## System Requirements

| Item | Requirement |
|------|-------------|
| OS | macOS 14 (Sonoma) or later |
| Processor | Apple Silicon / Intel |
| Permissions | Accessibility permission required |

## Installation

1. Download the latest release from the [Releases](../../releases) page
2. Open the `.dmg` and drag LockKM to your Applications folder
3. Launch LockKM
4. Go to System Settings > Privacy & Security > Accessibility and enable LockKM

> **Note**: Accessibility permission is required on first launch. This permission is used to control keyboard and mouse events.

## Usage

1. Click the LockKM icon in the menu bar
2. Select the device group to lock (Keyboard / Mouse)
3. Click the "Lock" button
4. To unlock, press your configured key combo (default: `⌘ ⇧ Esc`)

## License

BSD 3-Clause License - See [LICENSE](LICENSE) for details.

LockKM has been available for free on Mac since 2026.
