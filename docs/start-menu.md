# AquaShell Start Menu

## Design goal

The Start menu is treated as a compact application launcher rather than a Windows account/control hub.

### Keep
- Search at the top
- Pinned applications
- Acrylic/glass background
- Compact launcher-sized window

### Remove
- User profile tile
- Power controls
- Recommended/recent section
- Bottom navigation/footer

User/account and power controls are intentionally handled by the YASB macOS-style menu bar at the top of the desktop.

## Visual direction

Approximate layout:

```text
╭──────────────────────────────╮
│  🔎  Search                  │
│                              │
│  App    App    App    App    │
│  App    App    App    App    │
│  App    App    App    App    │
│                              │
╰──────────────────────────────╯
```

The target is closer to a macOS launcher / Launchpad-inspired mini menu than the stock Windows 11 Start menu.

## Current draft

- `windhawk/start-menu/aquashell-redesigned-v0.1.yaml`
- Target: redesigned Windows 11 Start menu (25H2+)
- Status: experimental; selectors may need adjustment for specific Windows builds.
