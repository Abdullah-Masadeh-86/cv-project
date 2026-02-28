# CV Application

A professional CV management application built with Flutter that allows users to create, manage, and download their CVs.

## Features

- 🔐 **User Authentication**: Login and Sign-up functionality
- 📝 **CV Creation**: Create comprehensive CVs with personal and professional information
- 📊 **Real-time Statistics**: Track CVs created and downloads
- 💾 **Data Persistence**: CVs are saved locally using SharedPreferences
- 📱 **Responsive Design**: Material Design UI optimized for all screen sizes
- ⬇️ **Download Functionality**: Download CVs in various formats

## Screens

1. **Login Screen**: User authentication with email/password
2. **Sign-up Screen**: New user registration
3. **Dashboard**: Overview with statistics and quick actions
4. **Create CV**: Form to add new CVs with all required fields
5. **View CVs**: List and detailed view of created CVs

## CV Fields

- Personal Information: First Name, Last Name, Job Title, Phone, Email, Address
- Professional Information: Skills, Education

## Technical Details

- **Framework**: Flutter
- **Language**: Dart
- **State Management**: StatefulWidget
- **Local Storage**: SharedPreferences
- **UI Framework**: Material Design 3

## Installation

1. Clone this repository
2. Run `flutter pub get` to install dependencies
3. Run `flutter run` to start the application

## Build

### For Web
```bash
flutter run -d chrome
```

### For Android APK
```bash
flutter build apk --release
```

### For Android App Bundle (Google Play)
```bash
flutter build appbundle
```

## Author

**Abdullah Masadeh** - [GitHub](https://github.com/Abdullah-Masadeh-86)

## License

This project is licensed under the MIT License.
