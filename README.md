# BunnyNutri

BunnyNutri is a functional Android offline-first MVP for visual food logging and orientative nutrition tracking.

## What it does

- Uses an on-device LiteRT/Google AIY Food Classifier V1 model to suggest a food label from a photo.
- Lets the user confirm or correct the food, portion, preparation, oil and sauces before saving a meal.
- Calculates orientative calories, protein, carbohydrates, fat and fiber from a small local USDA FoodData Central catalogue.
- Stores the meal diary locally with Room/SQLite.
- Supports optional local meal photos, CameraX, Android Photo Picker and JSON export without exposing private photo paths.
- Designed to work offline without a backend or cloud account.

## Current status

This is version 0.5.1 of a pre-revenue MVP. It has no active users, no live store listing and no signed commercial APK. Public traffic, downloads and revenue are currently zero.

The project is offered as a starter product for a buyer who wants to continue development, validation, branding or commercialization. This public repository is a product preview only; the complete source code, build artifacts and commercial delivery package are kept private and are not distributed from this repository.

## Technology

Kotlin, Jetpack Compose, Material 3, CameraX, Room/SQLite, LiteRT/TFLite runtime, Android SDK target 37 and Gradle Wrapper.

## Limitations

Nutrition values are estimates for general tracking and are not medical advice. The app does not claim exact calories, gram-level measurement, ingredient identification or allergen detection.

## License and third-party notices

The private delivery package contains the project documentation, license notices and checksums for included third-party components. Buyers should review the notices and validate licensing before commercial distribution.
