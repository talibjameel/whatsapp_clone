# WhatsApp Clone in Flutter

A full-featured WhatsApp clone built using Flutter. This project aims to replicate core WhatsApp functionalities, providing a real-time chat experience, group chats, media sharing, and much more using a modern cross-platform framework.

## Features

- **Authentication**
  - User login & registration (phone/email/OTP)
  - Secure authentication with Firebase/Auth provider

- **Chats**
  - One-to-one messaging
  - Group chat support
  - Real-time message updates using Firebase Firestore or Socket.io
  - Message status (sent, delivered, seen)

- **Media**
  - Image, video, audio, and document sharing
  - Voice messages
  - Camera integration

- **UI/UX**
  - WhatsApp-inspired design
  - Light & dark modes
  - Chat backgrounds & profile customization

- **Calls**
  - Voice & video calling (using WebRTC or third-party SDKs)
  - Call logs

- **Notifications**
  - Push notifications for new messages and calls

- **Other Features**
  - Status updates (stories)
  - Contact sync
  - Message search
  - User blocking/reporting

## Screenshots

> _Add screenshots of your application here_

## Getting Started

### Prerequisites

- [Flutter](https://flutter.dev/docs/get-started/install) (>=3.0.0 recommended)
- Dart SDK
- Firebase project (for backend services)
- Android Studio/Xcode (for platform-specific builds)

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/whatsapp-clone-flutter.git
   cd whatsapp-clone-flutter
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Configure Firebase**
   - Create a Firebase project.
   - Add Android/iOS apps to Firebase.
   - Download `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) and place them in the respective directories.
   - Enable Authentication, Firestore, and Storage in the Firebase console.

4. **Run the app**
   ```bash
   flutter run
   ```

## Folder Structure

```
lib/
  ├── main.dart
  ├── models/
  ├── screens/
  ├── widgets/
  ├── services/
  ├── utils/
```

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](LICENSE)

## Credits

- Inspired by WhatsApp
- Built with [Flutter](https://flutter.dev)
- Uses [Firebase](https://firebase.google.com/)

---

> This project is for educational purposes only. It is not affiliated with or endorsed by WhatsApp or Meta.
