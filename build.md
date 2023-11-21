YouTube: 18.45.41  
YouTube-Extended: 18.45.41  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.1.1-all.jar  
Integrations: inotia00/revanced-integrations-0.123.1.apk  
Patches: inotia00/revanced-patches-2.199.1.jar  

YouTube
==
- fix(YouTube/Default video quality): `Skipped preloaded buffer` is also applied to live stream video
- fix(YouTube/Hide mix playlists): check if the byte parameter is null
- fix(YouTube/Minimized playback): buffer symbol showing up instead of play button https://github.com/inotia00/ReVanced_Extended/issues/1482
- fix(YouTube/Return YouTube Dislike): improve layout padding
- fix(YouTube/SponsorBlock): skip segments breaks autoplay https://github.com/inotia00/ReVanced_Extended/issues/1714
- fix(YouTube/Spoof player parameters): frozen video on playback start
- feat(YouTube/Translations): update translation
`Bengali`, `Brazilian`, `Bulgarian`, `French`, `Greek`, `Hungarian`, `Indonesian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`


YouTube Music
==
- feat(YouTube Music/Translations): update translation
`French`, `Greek`, `Indonesian`, `Japanese`, `Korean`


Etc
==
- build: bump dependencies
- when updating from YouTube v18.33.40 or lower to YouTube v18.34.xx or later, a clean install is recommended.


※ Compatible ReVanced Manager: [RVX Manager v1.15.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.15.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---
CLI: j-hc/revanced-cli-4.1.0-all.jar  
Integrations: ReVanced/revanced-integrations-0.123.0.apk  
Patches: ReVanced/revanced-patches-2.199.0.jar  

### [2.199.0](https://github.com/ReVanced/revanced-patches/compare/v2.198.0...v2.199.0) (2023-11-20)
### Bug Fixes
* **Twitch - Settings:** Constrain to last working version ([941c1dd](https://github.com/ReVanced/revanced-patches/commit/941c1dd5cf9f43b4f6d023eacd6cfb31d87c2cd3))
* **YouTube - Settings:** Remove unnecessary punctuation ([#3301](https://github.com/ReVanced/revanced-patches/issues/3301)) ([c50ee82](https://github.com/ReVanced/revanced-patches/commit/c50ee8281f2b90a2721839047bdc8cd59c4c913a))
* **Yuka - Unlock premium:** Constrain to last working version ([81900fb](https://github.com/ReVanced/revanced-patches/commit/81900fb8db79284f57b5fd9e9ee0fe97cc0e7451))
### Features
* **YouTube:** Add `Disable rolling number animations` patch ([#3298](https://github.com/ReVanced/revanced-patches/issues/3298)) ([a0121ae](https://github.com/ReVanced/revanced-patches/commit/a0121ae7b60de88f0f2113ad0cefdb538f370780))

---  
