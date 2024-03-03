YouTube: 19.08.36  
YouTube-Extended: 19.08.36  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.4.1-all.jar  
Integrations: inotia00/revanced-integrations-0.140.1.apk  
Patches: inotia00/revanced-patches-2.220.1.jar  

YouTube
==
- feat(YouTube): add support versions `18.46.45`, `18.48.49`, `18.49.37`, `19.01.34`, `19.02.39` https://github.com/inotia00/ReVanced_Extended/issues/1929
- feat(YouTube/Hide button container): remove `Hide transcript button` setting https://github.com/inotia00/ReVanced_Extended/issues/1939
- feat(YouTube/Spoof app version): add target version 18.42.41 - Fixes issue where theme is not applied in search results (refer https://github.com/inotia00/ReVanced_Extended/issues/1820#issuecomment-1908949581)
- fix(YouTube): clarify patch description
- fix(YouTube/Hide comment component): changes description of `Hide emoji picker` setting (close https://github.com/inotia00/ReVanced_Extended/issues/1930)
- fix(YouTube/Hide layout components): `Hide browse store button` setting hides join button on tablets https://github.com/inotia00/ReVanced_Extended/issues/1948
- fix(YouTube/Hide layout components): `Hide join button` setting does not work https://github.com/inotia00/ReVanced_Extended/issues/1936
- fix(YouTube/Settings): move `Hide cast button` setting to `General` settings https://github.com/inotia00/ReVanced_Extended/issues/1947
- fix(YouTube/Settings): reset toast message is incorrect https://github.com/inotia00/ReVanced_Extended/issues/1938
- fix(YouTube/Shorts outline button): outline icon not applied when like/dislike button is clicked https://github.com/inotia00/ReVanced_Extended/issues/1886
- feat(YouTube/Translations): update translation
`Arabic`, `Brazilian`, `Chinese Traditional`, `Greek`, `Hungarian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- feat(YouTube Music): change patch name `Enable new player background` to `Enable old player background` https://github.com/inotia00/ReVanced_Extended/issues/1933
- feat(YouTube Music): change patch name `Hide emoji picker` to `Hide emoji picker and time stamp`
- feat(YouTube Music): change the description of the `Enable color match player`, `Enable zen mode` patches and exclude them by default https://github.com/inotia00/ReVanced_Extended/issues/1933
- feat(YouTube Music): remove `Enable sleep timer` patch (supported by default in latest YouTube Music)
- feat(YouTube Music/Hide general ads): remove `Hide interstitial ads` settings https://github.com/inotia00/ReVanced_Extended/issues/1940
- feat(YouTube Music/Hide player flyout panel): add `Hide subscribe / unsubscribe menu`, `Hide sleep timer menu` settings https://github.com/inotia00/ReVanced_Extended/issues/1932
- fix(YouTube Music): app is forced close when changing `Enable old player background` setting or the `Enable old player layout` setting (refresh automatically with a setting that does not cause forced to close)
- fix(YouTube Music/Enable force minimized player): fix typo https://github.com/inotia00/ReVanced_Extended/issues/1924
- fix(YouTube Music/Enable old style miniplayer): apply fingerprints compatible with the wider version
- fix(YouTube Music/Hide taste builder): apply fingerprints compatible with the wider version
- fix(YouTube Music/Replace dismiss queue): use built-in icons
- feat(YouTube Music/Translations): update translation
`Brazilian`, `Chinese Simplified`, `French`, `Greek`, `Japanese`, `Korean`, `Polish`, `Russian`, `Turkish`, `Ukrainian`, `Vietnamese`


Reddit
==
- feat(Reddit): add `Remove subreddit dialog` patch https://github.com/inotia00/ReVanced_Extended/issues/1934
- feat(Reddit): restrict support version (close https://github.com/inotia00/ReVanced_Extended/issues/1897)


Etc
==
- In the case of YouTube Music, [excluding some patches](https://github.com/inotia00/ReVanced_Extended/issues/1933), it is also compatible with YouTube Music v6.34.51+.
- In the case of Reddit, [supported versions are restricted](https://github.com/inotia00/ReVanced_Extended/issues/1897) due to the discontinuation of RVX, but patches are expected to be compatible regardless of Reddit's version for the time being.
- **This release is the final build of RVX.** [Migrate to ReVanced](https://revanced.app/) for ongoing support.

※ Compatible ReVanced Manager: [RVX Manager v1.18.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.18.1) or [RVX Manager v1.17.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.17.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revancedmusicextended)

---
CLI: j-hc/revanced-cli-4.3.0-all.jar  
Integrations: ReVanced
ReVanced/revanced-integrations-1.4.0.apk
revanced-integrations-1.4.0.apk.asc  
Patches: ReVanced
ReVanced/revanced-patches-4.3.0.jar
revanced-patches-4.3.0.jar.asc  

### [4.3.0](https://github.com/ReVanced/revanced-patches/compare/v4.2.0...v4.3.0) (2024-03-02)


### Bug Fixes

* Compile DEX without debugging information ([f5df957](https://github.com/ReVanced/revanced-patches/commit/f5df9578669f71a67411bc93a25a7e8da43610d0))
* **Override certificate pinning:** Always overwrite with a generic network security configuration ([2a842a1](https://github.com/ReVanced/revanced-patches/commit/2a842a1e14e1993eb028ae0bd1a93e227bb929a6))
* **YouTube - Spoof app version:** Remove broken versions ([#2776](https://github.com/ReVanced/revanced-patches/issues/2776)) ([9466d97](https://github.com/ReVanced/revanced-patches/commit/9466d973c6d7a2891e3fa9f283107b64399152ea))
* **YouTube - Spoof signature:** Fix tracking such as history or watch time ([bcd8b48](https://github.com/ReVanced/revanced-patches/commit/bcd8b48e70693dac1bfcc0bf4971d6b526065b59))


### Features

* **OpeningHours:** Add `Fix crash` patch ([#2697](https://github.com/ReVanced/revanced-patches/issues/2697)) ([0d011b8](https://github.com/ReVanced/revanced-patches/commit/0d011b876ecf05031a7daa54ab7e6d3506728a47))
* **Sync for Reddit:** Add `Fix /s/ links` patch ([f15ef3f](https://github.com/ReVanced/revanced-patches/commit/f15ef3f63460254236185f8e22c9395db4db9465))
* **Twitter - Unlock downloads:** Unlock GIF downloads ([d0f91c8](https://github.com/ReVanced/revanced-patches/commit/d0f91c8550592723e1252e1af2971b508591dd59))
* **VSCO - Unlock pro:** Constrain to last working version ([6dd4a7c](https://github.com/ReVanced/revanced-patches/commit/6dd4a7c29e48c3bc517bbdd7ed160624c36c2333))
* **X:** Add `Open links as query` patch ([#2730](https://github.com/ReVanced/revanced-patches/issues/2730)) ([ba75a51](https://github.com/ReVanced/revanced-patches/commit/ba75a51b71dbb9157db230b3e97a90361019fe30))
* **YouTube - Change start page:** Add more start pages ([cc1d9b7](https://github.com/ReVanced/revanced-patches/commit/cc1d9b743633c619fb6acc428e884c1c9b53e10b))
* **YouTube - Spoof app version:** Add target versions ([#2787](https://github.com/ReVanced/revanced-patches/issues/2787)) ([83a7bd8](https://github.com/ReVanced/revanced-patches/commit/83a7bd8d69e62623fc4d2ba73d9fb49e92751d89))
* **YouTube:** Reorganize settings menu ([#2737](https://github.com/ReVanced/revanced-patches/issues/2737)) ([36132df](https://github.com/ReVanced/revanced-patches/commit/36132df4be6a04c08b6f3dd79de1bcea93a80fb8))




---  
