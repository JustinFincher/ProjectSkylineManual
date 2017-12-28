# Privacy Policy
<!--{h1:.massive-header.-with-tagline}-->

## General
No, I don't collect or use your privacy data.  
I wrote this app for my own use first, then publish it on the Google Play. I don't care much about how much can I made with this app, and I have no reason to make money from user data.  
**But there are still some corner cases that should be addressed**, see below.

## Misc
- This app is based on Unity Engine. Unity have some basic analytics reporting user's device name, OS, Unity Engine version in an anonymous manner.
- This app uses [Unity Analytics](https://unity3d.com/unity/features/analytics). It only collects events when users set a location (only collects the action itself, does not collect the location). It will also collect the total user count.
- The development version of this app uses `READ_EXTERNAL_STORAGE` permission because it is compiled with [leakcanary](https://github.com/square/leakcanary) to detect memory leak. The production version (a.k.a Google Play version) does not have this permission requirement.
- The app uses `ACCESS_FINE_LOCATION` permission because the Mapbox demands it. The later version of Skyline may have a "locate me" feature and will use this permission.

## Last Modified
2017.12.29  
By [Justin Fincher (a.k.a Zheng Haotian)](https://fincher.im)