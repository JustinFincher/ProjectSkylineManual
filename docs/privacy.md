# Privacy Policy
<!--{h1:.massive-header.-with-tagline}-->

## TL,DR
No, Skyline don't collect or use your privacy data.  
I wrote this app for my own use first, then publish it on the Google Play. I don't care much about how much can I made with this app, and I have no reason to make money from user data.  
**But there are still some corner cases that should be addressed**, see below.

## Misc
- This app is based on Unity Engine. Unity have some basic analytics reporting user's device name, OS, Unity Engine version in an anonymous manner.  
- This app uses [HockeyApp](https://www.hockeyapp.net/) & [ACRA](https://github.com/ACRA/acra) to collect crash infos. ACRA crash reports are manually sent by pressing the crash notification and send mail, while HockeyApp crash reports are sent automatically. In the next few release cycles the HockeyApp reporter can be disabled by a opt out button, but currently it is always on.  
- From version 1.0.3 this app uses [Firebase Analytics](https://firebase.google.com/) to collect pirated copy infos. Normally users with a valid copy license won't get collected. The info, if collected, includes device name, app version, os version.  
- The app uses `ACCESS_FINE_LOCATION` permission because the Mapbox SDK demands it, and Skyline need this to locate you if you enable the location tracking feature. You can disable it if you are running on Android 6.0 and later.  
- The app uses `CAMERA` permission to scan the shared location QR code, you can disable it too if you are running on Android 6.0 and later.  

## Last Modified
2018.2.5
By [Justin Fincher (a.k.a Zheng Haotian)](https://fincher.im)  


