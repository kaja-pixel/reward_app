# Reward System App

A complete Flutter reward system with Firebase backend, featuring a user app with lucky wheel, surprise cards, points system, and an admin panel for management.

## Features

### User App
- Lucky wheel with smooth animations
- Surprise cards with scratch animations
- Points system
- Daily free spins (3 per day)
- Reward history
- Confetti animations on winning
- Anonymous authentication

### Admin Panel
- Email/password authentication
- CRUD operations for rewards
- Coupon management
- User management
- Winners history with filters
- Analytics dashboard
- CSV export

## Setup

1. Create a Firebase project at https://console.firebase.google.com/
2. Enable Firestore, Authentication (Anonymous and Email/Password)
3. Add Flutter apps (Android, iOS, Web)
4. Download config files and replace placeholders in firebase_options.dart
5. Deploy Firestore rules from firestore.rules
6. Run the apps

## Deployment

### User App
- Build for Android/iOS: `flutter build apk` or `flutter build ios`

### Admin Panel
- Build for web: `flutter build web`
- Deploy to Firebase Hosting: `firebase deploy`

## Firebase Structure

- `rewards`: Reward definitions
- `users`: User data
- `user_rewards`: User-specific rewards
- `spin_history`: Spin logs
- `coupons`: Coupon data
- `settings`: Configurable parameters