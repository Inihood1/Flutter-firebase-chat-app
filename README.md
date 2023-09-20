# Flutter Chat App with Firebase


A Flutter chat application that uses Firebase for real-time messaging. This app allows users to register, log in, and chat with each other in real-time. It is built using Flutter for the frontend and Firebase for the backend.

## Features

- User registration and authentication using Firebase Authentication.
- Real-time chat with other users.
- A clean and intuitive user interface.
- Users can send text messages.
- Online presence status for other users.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Inihood1/Flutter-firebase-chat-app.git
   ```

2. Change to the project directory:

   ```bash
   cd flutter-firebase-chat
   ```

3. Install the required dependencies:

   ```bash
   flutter pub get
   ```

4. Set up Firebase for your project:
   - Create a new project in the [Firebase Console](https://console.firebase.google.com/).
   - Add a new Android app and follow the setup instructions to download the `google-services.json` file.
   - Add a new iOS app and follow the setup instructions to download the `GoogleService-Info.plist` file.
   - Enable Firebase Authentication, Firestore, and Firebase Cloud Messaging in the Firebase Console.

5. Replace the Firebase configuration files:
   - Replace `android/app/google-services.json` with the one you downloaded from Firebase.
   - Replace `ios/Runner/GoogleService-Info.plist` with the one you downloaded from Firebase.

6. Run the app:

   ```bash
   flutter run
   ```

## Usage

1. Register a new account using the app.
2. Log in with your registered credentials.
3. Start chatting with other users who have registered in the app.

## Contributing

Contributions are welcome! If you have any feature requests or bug reports, please [create an issue](https://github.com/yourusername/flutter-firebase-chat/issues) on GitHub. If you'd like to contribute code, please fork the repository and make a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the Flutter and Firebase communities for their awesome documentation and resources.
- [Firebase](https://firebase.google.com/)
- [Flutter](https://flutter.dev/)

---

Happy chatting! If you have any questions or need assistance, feel free to open an issue or contact us.
