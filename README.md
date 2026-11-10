# Who Wants to Be a Millionaire? 💡

An Android quiz-game project organized around a sequence of question screens, with separate win and loss activities.

## Features represented in the source

- Splash and main activities
- Individual question activities for questions 1 through 10
- Separate game-won and game-lost screens
- Android XML layouts, drawable assets, and custom font resources
- Edge-to-edge window layout support in the main activity

## Tech Stack

- Java
- Android SDK (compile / target SDK 34; minimum SDK 24)
- AndroidX AppCompat and Activity
- Material Components
- ConstraintLayout
- Konfetti Android library
- Android XML layouts and resources

## Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/SRIKALYANBHAVANTHI/WhoWantstoBeaMillionaire.git
   ```
2. Open the project in Android Studio.
3. Allow Gradle sync to complete.
4. Run the **app** configuration on an Android emulator or device.

Build a debug APK:

```bash
./gradlew assembleDebug
```

Windows:

```bat
gradlew.bat assembleDebug
```

## Project Structure

Java activities are under `app/src/main/java/com/example/whowantstobeamillionaire`; screen layouts and visual assets are under `app/src/main/res`.

## Notes

The repository structure includes ten question activities and win/loss screens. Test question progression, answer validation, and end-game navigation before presenting the project as release-ready.

---

Created by [Srikalyan Bhavanthi](https://github.com/SRIKALYANBHAVANTHI).
