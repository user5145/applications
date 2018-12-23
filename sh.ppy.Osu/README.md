# Osu!
The bestest free-to-win rhythm game

## Status

| Arch  | Installs | Runs | Notes |
| ----- | -------- | ---- | ----- |
| 32bit | Yes      | Yes  | None  |

## Build & Install
### Repo
#### 32bit

    flatpak-builder --force-clean builds --repo=winepak sh.ppy.Osu.yml
    flatpak --user install winepak sh.ppy.Osu

### Direct
#### 32bit

    flatpak-builder --user --force-clean --install builds sh.ppy.Osu.yml

## Run

    flatpak run sh.ppy.Osu

