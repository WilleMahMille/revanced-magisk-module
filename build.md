YouTube: 18.40.33  
YouTube-Extended: 18.40.33  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.0.3-all.jar  
Integrations: inotia00/revanced-integrations-0.119.8.apk  
Patches: inotia00/revanced-patches-2.193.8.jar  

YouTube
==
- feat(YouTube): add support version `v18.34.38`, `v18.35.36`, `v18.36.39`
- feat(YouTube): drop support version `v18.22.37`, `v18.23.36`
- fix(YouTube/Alternative thumbnails): Add check for DeArrow API https://github.com/inotia00/revanced-integrations/pull/22
- fix(YouTube/Default video quality): use more appropriate settings label https://github.com/inotia00/ReVanced_Extended/issues/1509
- fix(YouTube/Enable new splash animation): integrations sometimes return invalid values
- fix(YouTube/Minimized playback): controlling notification control nothing https://github.com/inotia00/ReVanced_Extended/issues/1519
- fix(YouTube/Overlay buttons): chang description of `Hook download button`
- feat(YouTube/Translations): update translation
`Arabic`, `Brazilian`, `Bulgarian`, `Chinese Traditional`, `French`, `Greek`, `Hungarian`, `Indonesian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- feat(YouTube Music): add `Enable new player background` patch
- feat(YouTube Music): remove `Enable new layout` patch https://github.com/inotia00/ReVanced_Extended/issues/1518#issuecomment-1759473731
- fix(YouTube Music/Enable color match player): `Enable color match player` patch not working in new player background
- fix(YouTube Music/Spoof app version): description of the side effect is too long
- feat(YouTube Music/Translations): update translation
`Brazilian`, `Chinese Traditional`, `Dutch`, `Greek`, `Indonesian`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


Etc
==
- When updating from YouTube v18.33.40 or lower to YouTube v18.34.xx or later, a clean install is recommended.


※ Compatible ReVanced Manager: [RVX Manager v1.11.3 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.11.3)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---
CLI: j-hc/revanced-cli-4.0.1-all.jar  
Integrations: ReVanced/revanced-integrations-0.119.2.apk  
Patches: ReVanced/revanced-patches-2.194.0.jar  

### [2.194.0](https://github.com/ReVanced/revanced-patches/compare/v2.193.0...v2.194.0) (2023-10-12)


### Bug Fixes

* **YouTube - ReturnYouTubeDislike:** Fix dislikes not showing on Shorts ([#3133](https://github.com/ReVanced/revanced-patches/issues/3133)) ([0e8a286](https://github.com/ReVanced/revanced-patches/commit/0e8a2868e8e4328a6f02fa31537abc5e5ed220eb))
* **YouTube - Spoof app version:** Recommend clearing the app data after turning off spoofing ([#3134](https://github.com/ReVanced/revanced-patches/issues/3134)) ([166bf5b](https://github.com/ReVanced/revanced-patches/commit/166bf5b1aec5f8868b3895f7e24d2abc9037a7de))


### Features

* **CieID:** Add `bypass root check` patch ([#3011](https://github.com/ReVanced/revanced-patches/issues/3011)) ([20cfa8a](https://github.com/ReVanced/revanced-patches/commit/20cfa8a5cdebc7e81128c820a2aa01415a068320))
* Do not support reading options from a properties file ([3d1c0c1](https://github.com/ReVanced/revanced-patches/commit/3d1c0c1a958271c358755220b97b9dd92eb81d54))
* Improve option descriptions and titles ([9f86daa](https://github.com/ReVanced/revanced-patches/commit/9f86daa82271591bcaa9144d300a4810458fdd28))




---  
