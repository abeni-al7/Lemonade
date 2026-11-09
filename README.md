# Lemonade

A tap-through game for making lemonade: pick a lemon from the tree, squeeze it, drink the lemonade, then start again.

Built while following Google's [Android Basics with Compose](https://developer.android.com/courses/android-basics-compose/course) course (the "Lemonade" practice project).

## Features

- Four steps, each with its own image and instruction text
- The squeeze step needs a random number of taps (2 to 4) before moving on
- Tapping the empty glass restarts the cycle

## Built with

- Kotlin, Jetpack Compose, Material 3
- Step state with `remember { mutableStateOf(...) }` and `when` expressions
- `Scaffold` with a `CenterAlignedTopAppBar`
- Min SDK 24, target/compile SDK 35

## Run it

1. Open the project folder in Android Studio and let Gradle sync.
2. Run the `app` configuration on an emulator or device (Android 7.0 / API 24 or newer).

Or, with a device or emulator connected:

```sh
./gradlew installDebug
```
