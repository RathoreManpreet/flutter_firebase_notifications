# flutter_firebase_notifications

Flutter Firebase Notifications Installation

## Getting Started

1. Setup the firebase console settings

2. Then Setup the firebase settings in flutter
   `android/build.gradle file`

   - `classpath 'com.google.gms:google-services:4.3.3'`

3. Then Setup the firebase settings in flutter
   `android/app/build.gradle file`
    - defaultConfig add this code `multiDexEnabled true`
   - `apply plugin: 'com.google.gms.google-services'`
   - `implementation 'com.google.firebase:firebase-analytics:17.5.0'`
   - `implementation 'com.google.firebase:firebase-messaging:20.2.4'`


4. Install package `firebase_messaging` for flutter

