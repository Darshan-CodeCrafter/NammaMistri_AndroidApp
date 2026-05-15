# Namma Mistri — Android (Kotlin)

## Run in Android Studio
1. **File → New → Project from Existing Sources** → select this folder (or **Open** and pick the root).
2. Let Gradle sync (downloads AGP 8.5, Kotlin 1.9.24, Material 1.12).
3. Press **Run ▶** on an emulator or device (minSdk 24 / Android 7+).

## Features
- **ಲೆಕ್ಕ (Calculator):** length × height × wall thickness (4.5"/9"/13.5") → bricks, cement bags, sand CFT, and total cost using your saved rates.
- **ತಂಡ (Team / Labor Diary):** add workers with daily wage, mark P/H/A attendance, log advances, auto **Balance Due**.
- **ಫೋಟೋ (Site Photos):** pick gallery photos with captions + date.
- **ದರ (Rates):** edit local material prices; persists for the calculator.

All data is stored locally via SharedPreferences + Gson (no internet needed).

## Project layout
```
app/
 ├─ build.gradle.kts
 └─ src/main/
     ├─ AndroidManifest.xml
     ├─ java/com/nammamistri/app/
     │   ├─ MainActivity.kt
     │   ├─ CalculatorFragment.kt
     │   ├─ LaborFragment.kt
     │   ├─ PhotosFragment.kt
     │   ├─ RatesFragment.kt
     │   └─ Storage.kt
     └─ res/
         ├─ layout/  (activity + 4 fragments + 2 item rows)
         ├─ drawable/  (card / input / button backgrounds)
         └─ values/  (colors, strings — Kannada, themes)
```
## snapshots
<img width="360" height="800" alt="image" src="https://github.com/user-attachments/assets/82d4ac8b-02d1-4156-9fb7-03c8e37e9073" />
<img width="360" height="800" alt="Screenshot_20260515_202953" src="https://github.com/user-attachments/assets/132a8c6e-3f5e-46ab-8473-56fa100d7d41" />
<img width="360" height="800" alt="Screenshot_20260515_203212" src="https://github.com/user-attachments/assets/7c372bae-c4c6-423b-b344-5180094dbab6" />
<img width="360" height="800" alt="Screenshot_20260515_203225" src="https://github.com/user-attachments/assets/1806a781-df8b-4ddc-a765-8c52901b514b" />



