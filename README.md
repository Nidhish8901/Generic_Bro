# Generic Medicine Finder

A Flutter application to help users find generic medicines and locate nearby pharmacies.

## Features

- Search for generic alternatives to branded medicines
- Locate nearby pharmacies with real-time directions
- User-friendly interface with modern design
- Direct Google Maps integration for navigation
- Backend powered by FastAPI and Supabase

## Getting Started

### Prerequisites

- Flutter SDK
- Android Studio / VS Code
- Python 3.9+
- Git

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd generic-bro
```

2. Install frontend dependencies:
```bash
cd genericbro-frontend
flutter pub get
```

3. Install backend dependencies:
```bash
cd ../genericbro-backend
pip install -r requirements.txt
```

### Running the Application

1. Start the backend server:
```bash
cd genericbro-backend
uvicorn main:app --reload
```

2. Run the Flutter app:
```bash
cd genericbro-frontend
flutter run
```

## Building for Production

To build the release APK:
```bash
cd genericbro-frontend
flutter build apk --release
```

The APK will be available at `build/app/outputs/flutter-apk/app-release.apk`

## Tech Stack

- Frontend: Flutter
- Backend: FastAPI
- Database: Supabase
- Maps Integration: Google Maps API
- Deployment: Render

## License

This project is licensed under the MIT License - see the LICENSE file for details. # Generic_Bro
