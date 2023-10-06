YouTube: 18.39.38  
YouTube-Extended: 18.33.40  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-3.1.4-all.jar  
Integrations: inotia00/revanced-integrations-0.117.24.apk  
Patches: inotia00/revanced-patches-2.190.24.jar  

YouTube
==
- feat(youtube/default-video-quality): add `Skip dummy segment` setting (Experimental Flags)
- feat(youtube/litho-filter): commit reflected from official ReVanced
- feat(youtube/video-id): removes unnecessary fingerprints
- fix(youtube/disable-haptic-feedback): force close occurs in YouTube v18.27.36
- fix(youtube/enable-minimized-playback): change the method by which patches are applied
- fix(youtube/overlay-buttons): radio buttons in speed dialog always remember last selected value https://github.com/inotia00/ReVanced_Extended/issues/1484
- fix(youtube/swipe-controls): auto brightness value is not loaded properly https://github.com/inotia00/ReVanced_Extended/issues/1483
- rollback(youtube/hide-shorts-components): rollback hide the shorts shelf in search results (sometimes they hide the shorts section in the channel information)
- feat(youtube/translations): update translation
`Arabic`, `Brazilian`, `Bulgarian`, `Chinese Traditional`, `French`, `Hungarian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- feat(music): add support version `v6.22.51`
- feat(music/litho-filter): commit reflected from official ReVanced
- feat(music/replace-cast-button): change setting description
- feat(music/video-information): removes unnecessary fingerprints
- fix(music/enable-playback-speed): radio buttons in speed dialog always remember last selected value https://github.com/inotia00/ReVanced_Extended/issues/1484
- fix(music/hook-download-button): slightly improved action bar loading time
- fix(music/player-type-hook): player type is not hooked properly
- fix(music/return-youtube-dislike): wrong layout applied in RTL layout https://github.com/inotia00/ReVanced_Extended/issues/1475
- feat(music/translations): update translation
`Greek`, `Russian`


Etc
==
- build: bump dependencies


※ Compatible ReVanced Manager: [RVX Manager v1.10.3 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.10.3)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)


---
CLI: j-hc/revanced-cli-3.1.0-all.jar  
Integrations: ReVanced/revanced-integrations-0.118.0.apk  
Patches: ReVanced/revanced-patches-2.192.0.jar  

### [2.192.0](https://github.com/ReVanced/revanced-patches/compare/v2.191.0...v2.192.0) (2023-10-05)
### Bug Fixes
* **Relay for Reddit - Spoof client:** Prevent OAuth login being disabled remotely ([a0aa2be](https://github.com/ReVanced/revanced-patches/commit/a0aa2be86d25aab2803901b4100fdc75461e94bc))
* Remove `dependencies` from generated JSON file ([79bb3e1](https://github.com/ReVanced/revanced-patches/commit/79bb3e164f84094c639ac9e567dc0a5ce70300bd))
### Features
* **TikTok:** Constrain patches to last working version ([066023c](https://github.com/ReVanced/revanced-patches/commit/066023ca148b413b0848c0939e0bab2b3ff32b3a))
* **YouTube - Hide 
---  
