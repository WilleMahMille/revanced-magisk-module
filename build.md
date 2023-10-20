YouTube: 18.41.34  
YouTube-Extended: 18.41.34  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.0.3-all.jar  
Integrations: inotia00/revanced-integrations-0.119.18.apk  
Patches: inotia00/revanced-patches-2.193.18.jar  

YouTube
==
- feat(YouTube): add support version `v18.38.44`, `v18.39.41`
- feat(YouTube): add `Hide toolbar button` patch
- feat(YouTube/Disable haptic feedback): `Disable seek haptic feedback` now also disables `seek undo haptic feedback`
- feat(YouTube/Hide seek message): now the seek undo message (`Release to cancel`) is also hidden
- feat(YouTube/Hide shorts components): remove the `Hide toolbar` setting and add settings to hide each toolbar button
- fix(YouTube/Enable minimized playback): play button not available after playing Shorts https://github.com/inotia00/ReVanced_Extended/issues/1539
- fix(YouTube/Hide account menu): improve patch method
- fix(YouTube/Hide comment component): `Hide emoji picker` hides timestamps for chapters https://github.com/inotia00/ReVanced_Extended/issues/1556
- fix(YouTube/Hide general ads): reflection of changes in new layout
- fix(YouTube/Hide handle): handle is not hidden in You tab https://github.com/inotia00/ReVanced_Extended/issues/630
- fix(YouTube/Hide mix playlists): when MixPlaylists are included in my playlist (library), all playlists are hidden
- fix(YouTube/Hide player flyout panel): components are not hidden in new layout https://github.com/inotia00/ReVanced_Extended/issues/1410
- fix(YouTube/Return YouTube Dislike): dislike count for previous video is displayed after clicking dislike button in Shorts https://github.com/inotia00/ReVanced_Extended/issues/1547
- fix(YouTube/Settings): header for `Experimental Flags` is added even though `Experimental Flags` is empty
- fix(YouTube/Settings): patch names in Patches Information section do not match https://github.com/inotia00/ReVanced_Extended/issues/1555
- refactor(Litho filter): reduce memory requirement for prefix tree searching https://github.com/ReVanced/revanced-integrations/pull/501
- feat(YouTube/Translations): update translation
`Brazilian`, `Bulgarian`, `Chinese Traditional`, `French`, `German`, `Hungarian`, `Indonesian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- feat(YouTube Music/Translations): update translation
`Chinese Traditional`, `Japanese`, `Korean`, `Romanian`, `Russian`


Etc
==
- When updating from YouTube v18.33.40 or lower to YouTube v18.34.xx or later, a clean install is recommended.


※ Compatible ReVanced Manager: [RVX Manager v1.12.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.12.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---
CLI: j-hc/revanced-cli-4.0.2-all.jar  
Integrations: ReVanced/revanced-integrations-0.120.0.apk  
Patches: ReVanced/revanced-patches-2.195.0.jar  

### [2.195.0](https://github.com/ReVanced/revanced-patches/compare/v2.194.0...v2.195.0) (2023-10-20)
### Bug Fixes
* Indent option description correctly ([d4a9ea1](https://github.com/ReVanced/revanced-patches/commit/d4a9ea1f6c7ab9d25fd60695cce0965c7b5269a4))
* **Reddit - Sanitize sharing links:** Restore compatibility with newer versions of the app ([1671d8d](https://github.com/ReVanced/revanced-patches/commit/1671d8d826a08273fae5ccffc4a4ebfef9648fe2))
* **YouTube - Hide layout components:** Hide new channel watermark component ([cbfd569](https://github.com/ReVanced/revanced-patches/commit/cbfd5691d31ed144eac1d23de918ab5a6a905dfa))
### Features
* **YouTube - Theme:** Disable gradient loading screen ([90d5877](https://github.com/ReVanced/revanced-patches/commit/90d5877950095b7abacdca979bc7ad709192eee2))
* **YouTube:** Add `Announcements` patch ([#3166](https://github.com/ReVanced/revanced-patches/issues/3166)) ([f977983](https://github.com/ReVanced/revanced-patches/commit/f97798391ffc3477f781d43817664d31cfcd209a))
* **YouTube:** Add `Spoof device dimensions` patch ([c8d409e](https://github.com/ReVanced/revanced-patches/commit/c8d409e1dbda6ac45fef01912ce7afad1022b4b7))

---  
