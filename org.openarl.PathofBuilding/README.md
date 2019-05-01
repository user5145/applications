## Status

| Arch  | Installs | Runs | Notes |
| ----- | -------- | ---- | ----- |
| x86_64| Yes      | Yes  |       |

## Build & Install
```code
flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo  
flatpak-builder --user --force-clean --install ../build-dir org.openarl.PathofBuilding.yml  
```  
  
Icon: reddit.com/r/pathofexile/comments/6tnhjh/path_of_building_alternate_icon/
