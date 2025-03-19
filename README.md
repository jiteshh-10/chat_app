# Flutter Chat App

![Flutter Chat App](https://via.placeholder.com/800x400?text=Flutter+Chat+App)

A modern, real-time chat application built with Flutter that allows users to connect and communicate with friends seamlessly.

## ✨ Features

- **User Authentication**: Secure login and registration system
- **Real-time Messaging**: Instant message delivery and read receipts
- **User Profiles**: Customize your profile with pictures and username
- **Friend Management**: Add, remove, and manage your contacts
- **Responsive Design**: Works smoothly across different screen sizes
- **Push Notifications**: Never miss a message with real-time alerts

## 📱 Screenshots

<div style="display: flex; justify-content: space-between;">
  <img src="https://via.placeholder.com/200x400?text=Login+Screen" width="200" />
  <img src="https://via.placeholder.com/200x400?text=Chat+List" width="200" />
  <img src="https://via.placeholder.com/200x400?text=Chat+Screen" width="200" />
  <img src="https://via.placeholder.com/200x400?text=Profile" width="200" />
</div>

## 🛠️ Technologies Used

- **Flutter**: Cross-platform UI toolkit
- **Firebase**: 
  - Authentication for user management
  - Firestore for database
  - Storage for profile pictures
  - Cloud Messaging for notifications
- **Provider**: State management
- **GetX**: Navigation and dependency injection

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/jiteshh-10/chat_app.git
   cd chat_app
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Firebase Setup**
   - Create a new Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Add an Android/iOS app to your Firebase project
   - Download the configuration file (google-services.json/GoogleService-Info.plist)
   - Place the configuration file in the appropriate directory:
     - Android: `android/app/`
     - iOS: `ios/Runner/`

4. **Run the app**
   ```bash
   flutter run
   ```

## 🧩 Project Structure

```
lib/
├── components/      # Reusable UI components
├── models/          # Data models
├── screens/         # App screens
├── services/        # Firebase and other services
├── utils/           # Utility functions and constants
└── main.dart        # Entry point
```

## 🤝 How to Contribute

1. Fork the repository
2. Create a new branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some amazing feature'`)
5. Push to the branch (`git push origin feature/amazing-feature`)
6. Open a Pull Request

## 📋 Requirements

- Flutter (>=2.10.0)
- Dart (>=2.16.0)
- Android Studio / Xcode for emulators
- Firebase account

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

Jitesh - [@jiteshh_10](https://github.com/jiteshh-10)

Project Link: [https://github.com/jiteshh-10/chat_app](https://github.com/jiteshh-10/chat_app)
