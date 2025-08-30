# Flutter News App

## Overview
This is a Flutter-based news application that fetches and displays news articles from a public API. Users can browse headlines, read detailed articles, and stay updated with the latest news.

## Secreenshots

<img width="426" height="952" alt="Screenshot_1756580186" src="https://github.com/user-attachments/assets/f06a80a9-1f9d-4598-93fc-c621a035e88a" />
<img width="426" height="952" alt="Screenshot_1756580194" src="https://github.com/user-attachments/assets/ce3fea3a-1227-46a8-aead-d90048692d77" />

## Features
- Display a list of top news headlines.
- View detailed information for each news article.
- Responsive UI.

## Getting Started

### Prerequisites
- Flutter SDK installed.
- A code editor like VS Code or Android Studio.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/flutter-news-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd flutter-news-app
   ```
3. Get dependencies:
   ```bash
   flutter pub get
   ```

### Running the App
1. Connect a device or start an emulator.
2. Run the app:
   ```bash
   flutter run
   ```

## Project Structure
```
lib/
├── data/
│   ├── api_service.dart         # Handles API calls
│   ├── modals/
│   │   └── news_model.dart      # Data model for news articles
│   └── repositories/
│       └── news_repo.dart       # Repository for news data
├── screens/
│   ├── news_detail_screen.dart  # Displays detailed news article
│   └── news_screen.dart         # Displays list of news headlines
├── styles/
│   ├── app_theme.dart           # Defines application theme
│   └── icons.dart               # Custom icons
├── utils/
│   └── constants.dart           # Application constants
└── main.dart                    # Main entry point of the application
```

## Dependencies
- `http`: For making network requests.
- `provider`: For state management.
- `cached_network_image`: For caching network images.
- `intl`: For date formatting.

(See `pubspec.yaml` for full list of dependencies)
