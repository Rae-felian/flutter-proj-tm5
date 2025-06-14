# Ranimelist

Personal anime list app built with Flutter.

## Features

- Browse trending anime
- View top rated anime  
- Check most popular anime
- Save favorites locally
- View anime details

## Getting Started

1. Clone this repository
2. Run `flutter pub get`
3. Run `flutter run`

## Tech Stack

- Flutter
- Dart
- Jikan API (MyAnimeList)
- SharedPreferences

## Project Structure

```
lib/
├── main.dart
├── models/
│   └── anime_model.dart
├── services/
│   └── api_service.dart
├── pages/
│   ├── main_screen.dart
│   ├── home_page.dart
│   ├── search_page.dart
│   └── favorite_page.dart
└── widgets/
    ├── custom_bottom_nav.dart
    ├── anime_grid_card.dart
    ├── category_section.dart
    └── anime_detail_modal.dart
```

## API

Uses [Jikan API](https://jikan.moe/) for anime data.

## Author

**Rae Felian**  
NIM: 221110020  
Email: 221110020@student.mercubuana-yogya.ac.id
