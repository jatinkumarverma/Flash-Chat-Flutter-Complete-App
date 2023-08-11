
# Flash Chat Flutter App

Flash Chat is a real-time messaging app built with Flutter that allows users to send and receive messages instantly. The app utilizes Firebase for authentication and Firestore for real-time database management, making it a powerful and engaging communication platform.

## Features

- User Registration and Authentication
- Real-time Messaging
- Message Timestamps
- User Profiles
- Offline Messaging Support

## Getting Started

To get started with the Flash Chat app, follow these steps:

1. Clone this repository
2. Navigate to the project directory: `cd flash-chat-flutter`
3. Install the necessary dependencies: `flutter pub get`
4. Create a new Firebase project and configure the app by following the instructions [here](https://firebase.flutter.dev/docs/overview).
5. Add the Firebase configuration files to the `android/app` and `ios/Runner` directories.
6. Run the app on your preferred device or emulator: `flutter run`

## Configuration

Before running the app, you need to configure your Firebase project:

1. Create a new Firebase project on the [Firebase Console](https://console.firebase.google.com/).
2. Enable Firebase Authentication and Firestore for the project.
3. Replace the Firebase configuration in the `lib/constants.dart` file with your own configuration.

```dart
// lib/constants.dart

const kFirebaseApiKey = 'YOUR_API_KEY';
const kFirebaseProjectId = 'YOUR_PROJECT_ID';
const kFirebaseSenderId = 'YOUR_SENDER_ID';
const kFirebaseAppId = 'YOUR_APP_ID';
```

## Dependencies

This app uses the following packages:

- `firebase_core` and `firebase_auth` for Firebase authentication
- `cloud_firestore` for Firestore database management
- `modal_progress_hud` for showing loading indicators
- `fluttertoast` for displaying toast notifications

You can find more details about these packages in the `pubspec.yaml` file.

## Contributing

Contributions are welcome! If you have any bug fixes, improvements, or new features to add, please open a pull request.
