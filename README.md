### BACA NI DULU BRO ###

## Step 1: Firebase Setup

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new project (or use existing)
3. Add Android app:
   - Use your app's package name (found in `android/app/build.gradle`)
   - Download `google-services.json`
   - Place it in: `android/app folder`
4. Set authentication for emai (boleh tengok YouTube)

## Step 2: Firebase Setup at VSCode
1. Copy `build/main.dart`
2. Copy `android/app/build.gradle file`
3. Copy `pubspec.yaml`

## Step 3: Run the project
1. flutter get pub
2. flutter run

## Troubleshooting

If you get errors:
1. Check `google-services.json` is in correct location
2. Run `flutter clean` then try again
3. Make sure Firebase Authentication is enabled in Firebase Console

## Semoga Tak NT
