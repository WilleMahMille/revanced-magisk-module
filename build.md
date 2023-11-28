YouTube: 18.45.43  
YouTube-Extended: 18.45.43  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.2.1-all.jar  
Integrations: inotia00/revanced-integrations-0.124.1.apk  
Patches: inotia00/revanced-patches-2.201.1.jar  

YouTube
==
- feat(YouTube): add support version `v18.45.43`
- feat(YouTube/Hide description components): add `Hide shopping links` settings
- feat(YouTube/Hide navigation buttons): add `Hide notifications button` settings
- feat(YouTube/Hide shorts components): now hiding all shorts toolbar components does not hide the entire shorts toolbar (close https://github.com/inotia00/ReVanced_Extended/issues/1735)
- feat(YouTube/Overlay buttons): removed `pause after repeat` feature as it was likely to be buggy (close https://github.com/inotia00/ReVanced_Extended/issues/1736)
- feat(YouTube/Settings): now `Import / Export settings` exportable as text as well as file
- feat(YouTube/Settings): now `Import / Export settings` will not only `Revanced Extended settings`, but also `Return YouTube Dislike settings` and `SponsorBlock settings`
- feat(YouTube/Spoof app version): add target version 18.38.45 - Restore old default video quality behavior
- feat(YouTube/Swipe controls): restore `press-to-swipe gesture` and `press-to-swipe haptic feedback` settings
- fix(YouTube): replace variables declared as `List` with `Array`
- fix(YouTube/BrowseId): app crashes when browseId is not initialized
- fix(YouTube/Enable tablet layout): respect the original device layout
- fix(YouTube/Enable wide search bar): `Enable wide search bar` patch restores the old style search bar https://github.com/inotia00/ReVanced_Extended/issues/1733
- fix(YouTube/Hide navigation buttons): update side effect of `Switch create with notifications button` setting (close https://github.com/inotia00/ReVanced_Extended/issues/680)
- fix(YouTube/Hide shorts components): shorts header sometimes not hidden
- fix(YouTube/MicroG support): 
---
CLI: j-hc/revanced-cli-4.1.0-all.jar  
Integrations: ReVanced/revanced-integrations-0.124.1.apk  
Patches: ReVanced/revanced-patches-2.201.1.jar  

#### [2.201.1](https://github.com/ReVanced/revanced-patches/compare/v2.201.0...v2.201.1) (2023-11-27)
### Bug Fixes
* **Spotify - Hide premium navbar:** Support latest version ([b87005d](https://github.com/ReVanced/revanced-patches/commit/b87005de0c40293f85d3997f43b353a87a925156))
* **YouTube - Hide layout components:** Clarify custom filter usage ([cc16db5](https://github.com/ReVanced/revanced-patches/commit/cc16db56d1c9925852265fcebb459d9620cd1b92))

---  
