# React Native Navigation App

This project is a simple React Native application demonstrating navigation using `@react-navigation/native` and `@react-navigation/native-stack`. The app includes three screens: Home, About Us, and Contact Us.

## 📦 Dependencies
- **React Native**
- **@react-navigation/native**
- **@react-navigation/native-stack**
- **react-native-safe-area-context**
- **react-native-paper**

## 🚀 Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <project-folder>
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Install required pods (iOS only):
   ```bash
   cd ios && pod install && cd ..
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Run the app:
   - For Android:
     ```bash
     npm run android
     ```
   - For iOS:
     ```bash
     npm run ios
     ```

## 🛠️ Project Structure
```
.
├── components/
│   ├── Home.js
│   ├── AboutUs.js
│   ├── ContactUs.js
├── assets/
│   ├── images/
│   │   ├── uovlogo.png
├── App.js
├── package.json
└── README.md
```

## 📱 Features
- **Home Screen:** Introduction text and navigation buttons.
- **About Us Screen:** Information about the University with navigation options.
- **Contact Us Screen:** Contact form with fields for Name, Email, Phone, and Message.

## 🧭 Navigation
- **Home → Contact Us**
- **Home → About Us**
- **Contact Us → About Us**
- **About Us → Home**

## 🎨 Styling
The app uses **react-native-paper** for UI components and theming, with a consistent design across screens.

## 📧 Output
![Screenshot_20250106-103832_Expo Go](https://github.com/user-attachments/assets/ee606195-2c0c-4977-8c03-83d692f6816c)
![Screenshot_20250106-103838_Expo Go](https://github.com/user-attachments/assets/c3ea0b4c-ba48-41a3-bdac-38f6f106fec9)
![Screenshot_20250106-104345_Expo Go](https://github.com/user-attachments/assets/4364a07e-5e98-4eef-aba5-ebf8832c3dd9)
