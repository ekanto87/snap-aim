# SnapAim

Native Android aimbot — স্ক্রিন ক্যাপচার করে enemy-র health bar খুঁজে বের করে,
crosshair সেখানে snap করে, তারপর ফায়ার করে।

## বিল্ড
1. Android Studio → File → Open → এই ফোল্ডার
2. Gradle sync শেষ হওয়া পর্যন্ত অপেক্ষা করো
3. Build → Build Bundle(s)/APK(s) → Build APK(s)
4. APK: app/build/outputs/apk/debug/app-debug.apk

## চালানোর ধাপ
1. Overlay permission দাও
2. Accessibility → SnapAim চালু করো
3. START → "Entire screen" সিলেক্ট করো
4. Free Fire → Training Ground
5. Panel → CAL → detection ঠিক করো
6. FIRE marker গেমের ফায়ার বাটনের উপর বসাও
7. AIM বাটন চেপে ধরো

## নোট
- gradle-wrapper.jar নেই — Android Studio নিজেই ঠিক করে নেবে।
- JDK 17 আর Android SDK 34 লাগবে।
