# WindowsAquaShel

macOS-inspired Windows 11 desktop setup built from lightweight, modular tools instead of a full replacement shell.

> Work in progress.

## Goals

- macOS-like top menu bar using YASB
- dock-style Windows taskbar using Windhawk
- custom Start menu using Windows 11 Start Menu Styler
- matching Notification Center styling
- consistent glass/acrylic visual language
- multi-monitor support
- low RAM usage compared with all-in-one desktop shells

## Components

| Component | Tool | Status |
| --- | --- | --- |
| Top menu bar | YASB | In progress |
| Dock / taskbar | Windhawk | In progress |
| Start menu | Windows 11 Start Menu Styler | Next |
| Notification Center | Windhawk | Planned |
| Power menu | YASB | In progress |

## Repository structure

```text
configs/
  yasb/
    config.yaml
    styles.css
  windhawk/
    start-menu/
    taskbar/
docs/
```

## Notes

The project targets current Windows 11 builds and is being developed primarily around the redesigned Windows 11 Start menu.
