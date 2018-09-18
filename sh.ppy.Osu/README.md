# Osu!
The bestest free-to-win rhythm game

## Status

| Arch  | Installs | Runs | Notes |
| ----- | -------- | ---- | ----- |
| 32bit | N/A      | N/A  | None  |
| 64bit | Yes      | No   | None  |

## Build & Install
### Repo
#### 32bit

    flatpak-builder --arch=i386 --force-clean builds --repo=winepak sh.ppy.Osu.yml
    flatpak --user install winepak sh.ppy.Osu
    
#### 64bit

    flatpak-builder --arch=x86_64 --force-clean builds --repo=winepak sh.ppy.Osu.yml
    flatpak --user install winepak sh.ppy.Osu

### Direct
#### 32bit

    flatpak-builder --user --arch=i386 --force-clean --install builds sh.ppy.Osu.yml
    
#### 64bit

    flatpak-builder --user --arch=x86_64 --force-clean --install builds sh.ppy.Osu.yml

## Run

    flatpak run sh.ppy.Osu

