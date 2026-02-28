# Sudha's Mahila Lokh 🧚‍♀️

A complete Flutter mobile application for Sudha's Mahila Lokh - AP's biggest ladies retail shop for Jewellery, Cosmetics, Fancy items, and Hair accessories.

## Features

### 🏠 **10 Screens**
1. **Splash Screen** - Simple white button with "sudha" text (40x40)
2. **Home Screen** - Main landing page with shop information
3. **Categories List Screen** - Browse all product categories
4. **9 Category Screens** - Individual screens for each category:
   - Cosmetics
   - Bangles
   - Jewellery
   - One gram gold
   - Chains
   - Ear rings
   - Hair clips
   - Brochures
   - Saree pins
5. **Favorites Screen** - Save favorite products
6. **Settings Screen** - App settings and shop information

### 🎨 **UI Features**
- Beautiful gradient header (Yellow to Orange)
- Clean and simple design
- Easy navigation with bottom navigation bar
- Product grid with 40 items per category (2 columns)
- Image and video upload functionality
- Text description for each product

### 📱 **Functionality**
- **Image Upload**: Add product images to each widget
- **Text Input**: Add product descriptions
- **Video Upload**: Upload promotional videos for each category
- **Navigation**: Easy navigation between screens
- **Bottom Navigation Bar**: Quick access to Home, Categories, Favorites, and Settings

### 📍 **Shop Information**
- **Address**: NTR stadium complex, Shop No.11, Lakshmipuram, AP
- **Timings**: 10 AM to 9 PM
- **Phone**: 0863 2222855, 9441412413
- **WhatsApp**: 9441412413 👍

## Installation & Setup

### Prerequisites
- Flutter SDK (3.0.0 or higher)
- Dart SDK
- Android Studio / VS Code
- Android device or emulator (for testing)

### Steps to Run

1. **Install Flutter dependencies**:
   ```bash
   flutter pub get
   ```

2. **Check Flutter setup**:
   ```bash
   flutter doctor
   ```

3. **Run the app**:
   ```bash
   flutter run
   ```

4. **Build APK for Android**:
   ```bash
   flutter build apk --release
   ```

5. **Build for iOS** (requires Mac):
   ```bash
   flutter build ios --release
   ```

## Project Structure

```
sudhas_mahila_lokh_app/
├── lib/
│   └── main.dart              # Main application code
├── android/                    # Android-specific files
│   └── app/src/main/
│       └── AndroidManifest.xml
├── ios/                        # iOS-specific files
│   └── Runner/
│       └── Info.plist
├── pubspec.yaml               # Dependencies
└── README.md                  # This file
```

## Dependencies

- **flutter**: SDK
- **image_picker**: ^1.0.4 - For image and video selection
- **cupertino_icons**: ^1.0.2 - iOS style icons

## Screens Overview

### 1. Splash Screen
- Single button in center (40x40)
- White background
- Navigates to Home Screen on tap

### 2. Home Screen
- App bar with shop title
- Gradient header (400px height)
- Shop information and contact details
- 9 category buttons
- Bottom navigation bar

### 3. Category Screens
- Video upload section (full width, 400px height)
- 40 product widgets in grid (2 columns, 20 rows)
- Each widget has:
  - Image upload button
  - Text input button
  - 200x200 size with white background
  - Rounded corners and shadow

### 4. Additional Screens
- **Categories List**: All categories in a list view
- **Favorites**: Saved favorite products
- **Settings**: App settings and shop information

## Permissions

### Android
- Internet access
- Camera access
- Read/Write external storage

### iOS
- Photo library access
- Camera access
- Microphone access (for video)

## Customization

You can customize the app by modifying:
- Colors in `main.dart` (search for `Colors.orange`, `Colors.yellow`)
- Text content and styling
- Number of products per category (currently 40)
- Grid layout (currently 2 columns)

## Contact & Support

For any issues or questions about the app:
- **Phone**: 0863 2222855, 9441412413
- **WhatsApp**: 9441412413

## About

**Sudha's Mahila Lokh** - Your trusted ladies shop for over 30 years!
- 1Lack+ Designs
- AP's biggest Jewellery, Cosmetics, and Fancy items store
- One Stop Ladies shopee

---

**Version**: 1.0.0  
**Last Updated**: February 2026  
**Developed for**: Sudha's Mahila Lokh, Lakshmipuram, AP
