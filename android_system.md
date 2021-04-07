# Android System

- [**Android Internals**](#android-internals):
  - [Android OS Architecture](#zygote)
  - [Dalvik & ART](#dalvik--art)
  - [App Internals](#app-internals)
  - [APK file](#apk-file)
- [**Android Versions**](#android-versions)
  - [Android 5/5.1 (L - API level 21/22)](#android-551)
  - [Android 6 (M - 23)](#android-6)
  - [Android 7/7.1 (N - 24/25)](#android-771)
  - [Android 8/8.1 (O - 26-27)](#android-881)
  - [Android 9 (P - 28)](#android-9)
  - [Android 10 (Q - 29)](#android-10)
  - [Android 11 (R - 30)](#android-11)
  - [Android 12 (S - 31)](#android-12)

## Android Internals

### Android OS Architecture

- [Understanding Android Architecture](https://medium.com/@deepamgoel/understanding-android-architecture-1f0fb4b52f90)
- [Android Boot Up Process ( System Server)](https://medium.com/@khetanrajesh/android-boot-up-process-system-server-940f210d0194)
- [Android Boot Process](https://android.jlelse.eu/android-boot-process-8f7d94ff9889)
- [Who lives and who dies? Process priorities on Android](https://medium.com/androiddevelopers/who-lives-and-who-dies-process-priorities-on-android-cb151f39044f#.565lzw8kv)

**Zygote**

- [The Zygote Process](https://medium.com/masters-on-mobile/the-zygote-process-a5d4fc3503db)
- [What the Zygote!?](https://medium.com/@voodoomio/what-the-zygote-76f852d887d9)

### Dalvik & ART

- [Virtual Machine in Android: Everything you need to know](https://android.jlelse.eu/virtual-machine-in-android-everything-you-need-to-know-9ec695f7313b)
- [Android Internals: ART vs DVM deep dive](https://android.jlelse.eu/android-internals-art-vs-dvm-deep-dive-def34cf664d7)
- [A Garbage Collection Story](https://proandroiddev.com/a-garbage-collection-story-2421b96e4c84)
 
### App Internals

- [AndroIdiots Podcast 16: Android Process LifeCycle](https://medium.com/androidiots/androidiots-podcast-16-android-process-lifecycle-5cdba10fa431)
- [Android Internals #1: How Android Starts Your Main Activity](https://medium.com/martinomburajr/android-internals-1-how-android-starts-your-main-activity-8fcf80e65222)

### APK file

- [From Code to Dex — A Compilation Story](https://medium.com/upday-devs/from-code-to-dex-a-compilation-story-e1d62f63ad6a)
- [The internals of Android APK build process](https://medium.com/androiddevnotes/the-internals-of-android-apk-build-process-article-5b68c385fb20)

## Android Versions


- [SDK Platform release notes](https://developer.android.com/studio/releases/platforms)

### Android 5/5.1

**What's new:**
- ART
- Vector images support

### Android 6

**What's new:**
- Runtime Permissions
- DozeMode & App Standby
- Text Selection Toolbar
- App Linking

**Articles:**
- [Android 6.0 Changes](https://developer.android.com/about/versions/marshmallow/android-6.0-changes)
- [Doze Mode — Android](https://medium.com/cashify-engineering/doze-mode-android-6905d693af37)

### Android 7/7.1

**What's new:**
- Multi-window Support

**Articles:**

- [5 tips for preparing for Multi-Window in Android N](https://medium.com/androiddevelopers/5-tips-for-preparing-for-multi-window-in-android-n-7bed803dda64)
- [Sharing files through Intents: are you ready for Nougat?](https://quiro.dev/posts/sharing-file-intent-nougat/)
- [Android 7.1 Static Shortcut](https://medium.com/@tonyowen/android-7-1-static-shortcut-6c42d81ba11b#.jxwhq8108)
- [Quick Settings Tiles on Android 7.0](https://medium.com/androiddevelopers/quick-settings-tiles-e3c22daf93a8#.6oty9then)

### Android 8/8.1

**What's new:**

- Notification Channels
- Autofill

**Articles:**
- [Android 8.1 Developer Preview](https://android-developers.googleblog.com/2017/10/android-81-developer-preview.html)
- [Random Musings on the O Developer Preview 3](https://commonsware.com/blog/2017/06/08/random-musings-o-developer-preview-3.html)
- [Hidden Gems of Android O](https://medium.com/@ianhlake/hidden-gems-of-android-o-7def63136629)
- [Android O and the Implicit Broadcast Ban](https://commonsware.com/blog/2017/04/11/android-o-implicit-broadcast-ban.html)
- [O-h yeah! What we look forward to in Android O](https://blog.novoda.com/o-h-yeah-what-we-look-forward-to-in-android-o/)
- [Exploring Android O: Notification Channels](https://medium.com/exploring-android/exploring-android-o-notification-channels-94cd274f604c)
- [Notification in Android 8.0(oreo): Implementing Notification Channels](https://medium.com/cr8resume/notification-in-android-8-0-oreo-implementing-notification-channels-d65b0f81ca50)
- [Securing Apps From Android 8.0 Autofill](https://commonsware.com/blog/2017/06/13/securing-apps-android-8p0-autofill.html)
- [ACTION_BOOT_COMPLETED, IntentService, and Android 8.0](https://commonsware.com/blog/2017/06/12/action_boot_completed-intentservice-android-8p0.html)
- [Pitfalls of a foreground Service lifecycle](https://proandroiddev.com/pitfalls-of-a-foreground-service-lifecycle-59f014c6a125)

### Android 9

**What's new:**
- Slices
- App Actions
- Biometric prompt
- Text Classifier and Smart Linkify
- Neural Networks API

**Articles:**
- [Introducing Android 9 Pie](https://android-developers.googleblog.com/2018/08/introducing-android-9-pie.html)
- [Random Musings on the P Developer Preview 1](https://commonsware.com/blog/2018/03/08/random-musings-p-developer-preview-1.html)
- [Migrating from FingerprintManager to BiometricPrompt](https://medium.com/androiddevelopers/migrating-from-fingerprintmanager-to-biometricprompt-4bc5f570dccd)
- [Exploring Android P: Fingerprint Dialog](https://medium.com/exploring-android/exploring-android-p-fingerprint-dialog-fa672ae62c6f)
- [App Standby Buckets In Android](https://medium.com/mindorks/app-standby-buckets-in-android-ada2d2929350)

### Android 10

**What's new:**
- Dark Theme
- Sharing shortcuts
- Scoped storage

**Articles:**
- [Exploring Android Q: Bubbles](https://joebirch.co/android/exploring-android-q-bubbles/)
- [Exploring Android Q: Sharing Shortcuts](https://joebirch.co/android/exploring-android-q-sharing-shortcuts/)
- [Exploring Android Q: Settings Panels](https://joebirch.co/android/exploring-android-q-settings-panels/)
- [Exploring Android Q: Location Permissions](https://joebirch.co/android/exploring-android-q-location-permissions/)
- [All You Need to Know About Scoped Storage in Android 10](https://medium.com/better-programming/all-you-need-to-know-about-scoped-storage-in-android-10-e621f40bc8b9)
- [Handling Files in Code After Android 10 Released](https://android.jlelse.eu/handling-files-in-code-after-the-android-10-released-2bea0e16d35)

### Android 11

**Articles:**
- [The Quick Developers Guide to Migrate Their Apps to Android 11](https://proandroiddev.com/the-quick-developers-guide-to-migrate-their-apps-to-android-11-e4ca2b011176)
- [Android 11 storage FAQ](https://medium.com/androiddevelopers/android-11-storage-faq-78cefea52b7c)
- [Modern user storage on Android](https://medium.com/androiddevelopers/modern-user-storage-on-android-e9469e8624f9)

### Android 12

- [First preview of Android 12](https://android-developers.googleblog.com/2021/02/android-12-dp1.html)
