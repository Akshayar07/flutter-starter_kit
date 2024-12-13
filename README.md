# flutter-starter_kit


# Lib Folder Structure

lib/
├── main.dart                 # Entry point of the application
├── app/
│   ├── app.dart              # Contains the main MyApp class
│   ├── routes.dart           # Manages named routes
│   ├── themes.dart           # Centralized theme management
│   ├── localization.dart     # Localization configuration (if applicable)
├── core/
│   ├── constants/
│   │   ├── app_strings.dart  # Contains all static strings
│   │   ├── app_colors.dart   # Color definitions
│   │   ├── app_assets.dart   # Asset paths (e.g., images/icons)
│   ├── utils/
│   │   ├── validators.dart   # Input validation logic
│   │   ├── extensions.dart   # Dart extensions for better readability
│   ├── services/
│       ├── api_service.dart  # API interaction logic
│       ├── storage_service.dart # Local storage (e.g., SharedPreferences)
│       ├── auth_service.dart # Authentication logic
├── data/
│   ├── models/               # Data models (e.g., User, Product)
│   ├── repositories/         # Handles business logic and connects services
│       ├── user_repository.dart 
│       ├── product_repository.dart
├── presentation/
│   ├── screens/              # UI screens
│   │   ├── home/
│   │   │   ├── home_screen.dart
│   │   │   ├── widgets/      # Widgets specific to the home screen
│   │   ├── login/
│   │       ├── login_screen.dart
│   ├── widgets/              # Reusable UI components
│       ├── custom_button.dart
│       ├── custom_card.dart
├── localization/             # Translation files
│   ├── en.json
│   ├── es.json
├── test/                     # Test files
