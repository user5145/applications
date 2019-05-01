## Status

| Arch  | Installs | Runs | Notes |
| ----- | -------- | ---- | ----- |
| x86   | Yes      | Yes  |       |
| x86_64| Yes      | Yes  |       |

## Build & Install
```code
flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo  
flatpak-builder --user --force-clean --install ../build-dir com.gog.Settlers2.10thanniversary.yml  
```
