# Shopping Live - Flutter Live Shopping App

Shopping Live is a modern e-commerce application built with Flutter that enables real-time live shopping experiences. The app integrates video streaming capabilities with HMS SDK, Firebase authentication, and a comprehensive shopping platform.

## Features

- **Live Shopping Streams**: Real-time video streaming using HMS SDK
- **User Authentication**: 
  - Firebase Authentication integration
  - Google Sign-in support
  - Email/Password authentication
- **User Profiles**: 
  - Customizable user profiles
  - Follower system
  - Business profiles for sellers
- **Shopping Features**:
  - Order management system
  - Product browsing
  - Notification system
- **Responsive UI**: 
  - Material Design implementation
  - Cross-platform compatibility
  - Custom navigation with curved navigation bar

## Tech Stack

- **Frontend**: Flutter (SDK >=2.18.6 <3.0.0)
- **Backend**: Firebase
  - Cloud Firestore
  - Firebase Authentication
  - Firebase Storage
- **Video Streaming**: HMS SDK Flutter
- **State Management**: Provider

## Getting Started

### Prerequisites

- Flutter SDK (>=2.18.6)
- Dart SDK
- Android Studio / VS Code
- Firebase project setup
- HMS Account and SDK configuration

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   flutter pub get
   ```
3. Configure Firebase:
   - Add your `google-services.json` for Android
   - Add your `GoogleService-Info.plist` for iOS
4. Configure HMS SDK:
   - Add your HMS credentials in the project
5. Run the app:
   ```bash
   flutter run
   ```

## Dependencies

- **Firebase Packages**:
  - `firebase_core: ^2.4.1`
  - `firebase_auth: ^4.2.5`
  - `cloud_firestore: ^4.3.1`
  - `firebase_storage: ^11.0.10`

- **UI Components**:
  - `curved_navigation_bar: ^1.0.3`
  - `flutter_screenutil: ^5.6.0`
  - `font_awesome_flutter: ^10.3.0`
  - `lottie: ^2.2.0`

- **Authentication**:
  - `google_sign_in: ^5.4.3`

- **Video Streaming**:
  - `hmssdk_flutter: ^1.2.0`

- **Utilities**:
  - `provider: ^6.0.5`
  - `http: ^0.13.5`
  - `permission_handler: ^10.2.0`
  - `file_picker: ^5.2.5`

## Project Structure

The app follows a modular architecture with the following key directories:

- `lib/screens`: UI screens and widgets
- `lib/providers`: State management
- `lib/resources`: Authentication and API services

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
