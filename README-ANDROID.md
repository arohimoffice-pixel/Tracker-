# My Islamic Tracker — Android Studio project

This is an Android WebView app wrapper around the included offline tracker.

## Build an APK
1. Install Android Studio (with Android SDK Platform 35).
2. Open this `MyIslamicTrackerAndroid` folder in Android Studio.
3. Allow Gradle sync to finish.
4. Select **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. Android Studio will show the APK location, normally `app/build/outputs/apk/debug/app-debug.apk`.
6. Copy the APK to your Android phone and install it. You may need to allow installation from that source.

## Included
- Prayer checkboxes for Fajr, Dhuhr, Asr, Maghrib and Isha
- Quran reading log (pages, verses, notes)
- Hadith reading log (count, pages, notes)
- Custom daily task categories, completion and star markers
- Monthly and yearly reports
- Foreground app active-time estimate

## Data
The app stores records locally in WebView local storage on the phone. Clearing app data or uninstalling may erase records. Export/backup is not included yet.

## Usage timer limitation
The timer counts only while the app is open and visible. It does not count background time or measure total Android device screen time.
