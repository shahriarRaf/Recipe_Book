# Recipe Book

Recipe Book is an iOS SwiftUI app for browsing, creating, and saving recipes.

## Features

- Firebase Authentication (sign up, log in, session check)
- Home feed with recipe cards
- Search and favorites tabs
- Create and submit new recipes
- Profile tab for account-related views

## Tech Stack

- SwiftUI
- Firebase Auth
- Firebase Firestore

## Project Structure

- `Recipe App/Recipe App/RecipeSaver/` – app entry point and main views
- `Recipe App/Recipe App/Models/` – recipe models
- `Recipe App/Recipe App/RecipeSaver/Views/` – UI screens and components

## Getting Started

1. Open `Recipe App/Recipe App.xcodeproj` in Xcode.
2. Ensure a valid Firebase configuration file (`GoogleService-Info.plist`) is present.
3. Build and run the app on a simulator or iOS device.

## Notes

- The app configures Firebase at launch in `Recipe_AppApp.swift`.
- New recipes are stored in the `Recipes` Firestore collection.
