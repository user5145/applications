# Diablo II
Online Action RPG

## Status

| Arch  | Installs | Runs | Notes |
| ----- | -------- | ---- | ----- |
| 32bit | N/A      | N/A  |       |
| 64bit | Yes      | Yes  | Runs with no issues; Only campaign was tested, not multiplayer; If crashes during download rerun. |

## Build & Install
### Repo
#### 32bit & 64bit

    flatpak-builder --force-clean builds --repo=winepak com.blizzard.Diablo2.yml
    flatpak --user install winepak com.blizzard.StarCraft2

### Direct
#### 32bit & 64bit

    flatpak-builder --user --force-clean --install builds com.blizzard.Diablo2.yml

## Run

    flatpak run com.blizzard.Diablo2

