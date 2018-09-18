# Diablo II
Online Action RPG

## Status

| Arch  | Installs | Runs | Notes |
| ----- | -------- | ---- | ----- |
| 32bit | Yes      | Yes  | As a workaround for flatpak/flatpak#713 download Downloader_Diablo2_enUS.exe from battlenet.com and put into com.blizzard.Diablo2; cinematics and multiplayer don't work |

## Build & Install
### Repo
#### 32bit

    flatpak-builder --force-clean builds --repo=winepak com.blizzard.Diablo2.yml
    flatpak --user install winepak com.blizzard.Diablo2

### Direct
#### 32bit

    flatpak-builder --user --force-clean --install builds com.blizzard.Diablo2.yml

## Run

    flatpak run com.blizzard.Diablo2

