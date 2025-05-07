# Prometheus: Add README for solana_flutter_frontend

## Project Overview

A secure and innovative mobile application for parking booking that leverages blockchain technology to ensure safe and transparent transactions. This Flutter-based mobile app provides users with a seamless parking reservation experience powered by Solana cryptocurrency.

### Key Features
- Cryptocurrency-based transaction system using Solana blockchain
- Secure and transparent parking reservations
- User authentication and profile management
- Real-time transaction tracking
- Cross-platform mobile application (iOS and Android)

### Benefits
- Enhanced transaction security through blockchain technology
- Reduced dependency on traditional payment methods
- Decentralized and transparent booking process
- Convenient mobile-first user experience
- Eliminates intermediary fees associated with traditional parking booking systems

## Getting Started, Installation, and Setup

### Prerequisites

- Flutter SDK (version >=2.11.0 <3.0.0)
- Dart SDK 
- Android Studio or VS Code with Flutter extensions
- Android/iOS development environment (for mobile deployment)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/solana_flutter_frontend.git
   cd solana_flutter_frontend
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

### Development Setup

#### Running the App

1. Connect a device or start an emulator
2. Run the app in development mode:
   ```bash
   flutter run
   ```

#### Platform-Specific Instructions

##### Android
- Ensure Android SDK is installed
- Open the project in Android Studio
- Sync Gradle files
- Run on Android emulator or physical device

##### iOS
- Open the project in Xcode
- Update signing certificates
- Run on iOS simulator or physical device

### Build for Production

#### Android
```bash
flutter build apk
```
The release APK will be located in `build/app/outputs/flutter-apk/app-release.apk`

#### iOS
```bash
flutter build ios
```
Follow Xcode instructions to archive and deploy the app

### Key Dependencies
- Provider for state management
- HTTP for network requests
- Google Maps for location services
- Geolocator for geographical functionality

### Recommended Development Environment
- Flutter SDK 
- Android Studio or VS Code
- Android/iOS development tools