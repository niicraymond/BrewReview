# BrewReview (Bootcamp Group Project)

Demo: run locally via Expo

## Overview
Cross-platform mobile app built with Expo/React Native for reviewing beers and breweries. Users can authenticate, browse beers and breweries, post reviews, follow other users, manage favorites, view recent activity, and explore via map or categories.

## Features
- User authentication (Firebase Auth)  
- View home feed, individual beers, breweries, user profiles  
- Post beer reviews  
- Follow/unfollow users  
- Favorite beers and breweries  
- Browse by categories  
- Map view of breweries  
- View followers/following lists  
- Recent reviews feed  
- Settings and profile management  
- Toast notifications and loading states  

## Technologies Used
- Expo / React Native  
- Expo Router (file-based routing)  
- Firebase (Auth + Firestore)  
- NativeWind (Tailwind-style styling for RN)  
- React Native Paper  
- React Navigation (native stack)  
- Toast messages (`react-native-toast-message`)  
- JavaScript / JSX  
- ESLint / TypeScript tooling in dev  

## Prerequisites
- Node.js (recommended latest LTS)  
- Android Studio (for Android emulator) or Xcode (for iOS simulator) if not using Expo Go  
- Expo-compatible device (Expo Go) or simulator/emulator  

## Setup Instructions
```bash
git clone https://github.com/niicraymond/BrewReview/
cd BrewReview
npm install
```

Start the app:
```bash
npm run start
```

Then choose one of:
- Run on Android emulator: `npm run android`  
- Run on iOS simulator: `npm run ios`  
- Open in web: `npm run web`  
- Scan the QR code with Expo Go on your mobile device  

## Scripts
- `npm run start` – launch Expo dev tools  
- `npm run android` – open in Android emulator  
- `npm run ios` – open in iOS simulator  
- `npm run web` – run as web app  
- `npm run lint` – run ESLint  
- `npm run reset-project` – reset starter state (moves current code to example folder)  

## Data / Backend
Uses Firebase Firestore for persistence. Core collections include:
- `users` – user profiles, followers/following  
- `beers` / `breweries` – entities being reviewed  
- `reviews` – user reviews, vote tracking  
- `categories` – classification for browsing  

Utility modules handle fetching entities and vote/follow logic.

## Author / Team
Bootcamp Group Project - Developed By Nicole Raymond, George Harper, Sam Joy, Katherin Bennet and Manuel González 

