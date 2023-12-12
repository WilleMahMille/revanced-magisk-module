YouTube: 18.48.37  
YouTube-Extended: 18.48.37  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.3.1-all.jar  
Integrations: inotia00/revanced-integrations-0.127.1.apk  
Patches: inotia00/revanced-patches-2.204.1.jar  

YouTube
==
- fix(YouTube/Hide general ads): `interstitial ads` are closed too early
- fix(YouTube/Hide navigation buttons): update side effect of `Switch create with notifications button` setting
- feat(YouTube/Translations): update translation
`Arabic`, `Chinese Traditional`, `French`, `Greek`, `Hungarian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- feat(YouTube Music/Hide general ads): now patch hides new type of interstitial banner
- fix(YouTube Music): some patches are broken in `v6.31.55+`
- fix(YouTube Music/Enable old player layout): add version constraint (no longer available as legacy code has been completely removed in `v6.31.55+`)
- fix(YouTube Music/Hide general ads): `interstitial ads` are closed too early
- feat(YouTube Music/Translations): update translation
`French`, `Russian`, `Ukrainian`


Reddit
==
- feat(Reddit): change patch name: `Hide place button` → `Hide toolbar button`

Etc
==
- when updating from YouTube v18.33.40 or lower to YouTube v18.34.xx or later, a clean install is recommended.

※ Compatible ReVanced Manager: [RVX Manager v1.17.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.17.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revancedmusicextended)

---
CLI: j-hc/revanced-cli-4.3.0-all.jar  
Integrations: ReVanced/revanced-integrations-1.0.0.apk  
Patches: ReVanced/revanced-patches-3.0.1.jar  

#### [3.0.1](https://github.com/ReVanced/revanced-patches/compare/v3.0.0...v3.0.1) (2023-12-12)
### Bug Fixes
* **YouTube Music - GmsCore support:** Change from correct package name to prevent the patch from failing ([284a7f0](https://github.com/ReVanced/revanced-patches/commit/284a7f0b1a7b46e36b5f3dd132bb36d6d3fef584))

---  
