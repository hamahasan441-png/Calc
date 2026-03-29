# تۆمارکردنی خەرجی — Expense Tracker

> **کوردی:** ئەپێکی ئەندرۆیدە بۆ تۆمارکردنی خەرجی ڕۆژانە بە زمانی کوردی.  
> **English:** An Android app for tracking daily expenses, built with a Kurdish-language RTL interface.

## Features / تایبەتمەندیەکان

- Add and delete expense entries with confirmation modals
- Filter by today, current month, or specific date
- Persistent storage via `localStorage`
- Kurdish numerals and RTL layout
- Dark theme with gold accent colors
- Toast notifications

## Project Structure

```
app/
  src/main/
    assets/index.html          # Full HTML/CSS/JS expense tracker app
    java/com/calc/expensetracker/MainActivity.java
    AndroidManifest.xml
    res/values/
      strings.xml
      colors.xml
      themes.xml
build.gradle
app/build.gradle
settings.gradle
gradle.properties
gradle/wrapper/gradle-wrapper.properties
```

## Build Instructions

### Requirements
- Android Studio Hedgehog (2023.1.1) or later
- JDK 17+

### Build debug APK

```bash
./gradlew assembleDebug
```

### APK output location

```
app/build/outputs/apk/debug/app-debug.apk
```

### Install on connected device

```bash
adb install app/build/outputs/apk/debug/app-debug.apk
```
