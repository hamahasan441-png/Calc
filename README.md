# تۆمارکردنی خەرجی - Expense Tracker

بەرنامەیەکی ئەندرۆیدی تۆمارکردنی خەرجیی ڕۆژانە بە زمانی کوردی.

A Kurdish-language Android expense tracker app built with WebView.

## Features / تایبەتمەندییەکان

- ✅ تۆمارکردنی خەرجییەکان بە ناو، بڕ، جۆر، و بەروار
- ✅ فلتەرکردن بە ئەمڕۆ، ئەم مانگە، یان هەموو
- ✅ سڕینەوەی خەرجی بە پشتڕاستکردنەوە
- ✅ پاشەکەوتکردن لە localStorage
- ✅ ژمارەی کوردی
- ✅ دیزاینی تاریک (Dark Theme)

## Project Structure / پێکهاتەی پڕۆژە

```
Calc/
├── app/
│   ├── build.gradle
│   ├── proguard-rules.pro
│   └── src/main/
│       ├── AndroidManifest.xml
│       ├── assets/
│       │   └── index.html          # HTML expense tracker app
│       ├── java/com/calc/expensetracker/
│       │   └── MainActivity.java   # WebView activity
│       └── res/values/
│           ├── colors.xml
│           ├── strings.xml
│           └── themes.xml
├── build.gradle                    # Project-level build file
├── settings.gradle
├── gradle.properties
└── gradle/wrapper/
    └── gradle-wrapper.properties
```

## Build Instructions / ڕێنمایی دروستکردن

### Prerequisites
- Android Studio (latest version recommended)
- JDK 8 or higher

### Build with Android Studio
1. Open the project in Android Studio
2. Wait for Gradle sync to complete
3. Click **Run** ▶ or **Build > Build APK**

### Build from Command Line
```bash
./gradlew assembleDebug
```

The APK will be at: `app/build/outputs/apk/debug/app-debug.apk`

## Tech Stack

- **Android** (Java) - Native Android app
- **WebView** - Renders the HTML expense tracker
- **HTML/CSS/JavaScript** - Full expense tracker UI with Kurdish localization
- **localStorage** - Client-side data persistence
