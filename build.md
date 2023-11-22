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
Patches: ReVanced/revanced-patches-2.200.0.jar  

### [2.200.0](https://github.com/ReVanced/revanced-patches/compare/v2.199.0...v2.200.0) (2023-11-22)
### Bug Fixes
* **Spotify - Custom theme:** Add more background surfaces coloring options ([#3285](https://github.com/ReVanced/revanced-patches/issues/3285)) ([869ec26](https://github.com/ReVanced/revanced-patches/commit/869ec26966f7750c45355ac0acc18b81a2abce87))
* **YouTube - Remove tracking query parameter:** Sanitize shared URLs in remaining places ([2442902](https://github.com/ReVanced/revanced-patches/commit/2442902dacc25f2c932a6689e9788e5a02fdff6b))
### Features
* **Twitch:** Constrain patches to versions known to work ([65b55a5](https://github.com/ReVanced/revanced-patches/commit/65b55a5189df52dc7e99b7e9c68b908fbca92434))
* **Twitch:** Support version `16.9.1` ([c70e4a6](https://github.com/ReVanced/revanced-patches/commit/c70e4a66bd65b42db88dcabd412ec985226bd1e7))

---  
