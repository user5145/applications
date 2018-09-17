# Diablo II
Online Action RPG

## Status

| Arch  | Installs | Runs | Notes |
| ----- | -------- | ---- | ----- |
| 32bit | N/A      | N/A  |       |
| 64bit | Yes      | Yes  | Runs with no issues; Only campaign was tested, not multiplayer; If crashes during download rerun. As a workaround for flatpak/flatpak#713 download Downloader_Diablo2_enUS.exe from battlenet.com manually |

## Build & Install
### Repo
#### 32bit & 64bit

    flatpak-builder --force-clean builds --repo=winepak com.blizzard.Diablo2.yml
    flatpak --user install winepak com.blizzard.Diablo2

### Direct
#### 32bit & 64bit

    flatpak-builder --user --force-clean --install builds com.blizzard.Diablo2.yml

## Run

    flatpak run com.blizzard.Diablo2

