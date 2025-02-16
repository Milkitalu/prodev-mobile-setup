# Mobile Development Setup

This repository documents the setup process for mobile development using Expo Go.

## Tools Installed
- Node.js LTS (v18.x)
- VS Code (v1.85)
- Expo Go (v49.0.0)

## Steps Followed
1. Installed Node.js LTS and VS Code.
2. Downloaded Expo Go from the Google Play Store.
3. Created a new React Native project using `npx create-expo-app`.
4. Started the development server and scanned the QR code with Expo Go.

## Challenges Faced
- **Issue**: QR code not scanning on iOS.  
  **Solution**: Ensured both my laptop and iPhone were on the same Wi-Fi network.
- **Issue**: Expo Go app crashing on launch.  
  **Solution**: Reinstalled the app and updated my device's operating system.

## Screenshots
![QR Code Scanning](screenshots/qr-code-scan.png)  
![App Running on Device](screenshots/app-running.jpg)
Repository Structure
Ensure your repository (prodev-mobile-setup) has the following structure:


# First Mobile App Using Expo Router

This repository documents the process of creating a mobile app using the Expo Router template.




## Steps Followed
 1. Navigated to the project directory:  
   ```bash
   cd prodev-mobile-setup
   ```
2. Initialized a new Expo project using the Expo Router template:  
   ```bash
   npx create-expo-app@latest .
   ```
3. Modified the home screen by editing `app/(tabs)/index.tsx` and changing the default text to `** First App Created**`.
4. Started the development server:  
   ```bash
   npx expo start
   ```
5. Tested the app by scanning the QR code with Expo Go on my Android device.
6. Ran the reset command:  
   ```bash
   npm run reset-project
   ```

## Observations from `reset-project` Command
- The `reset-project` command clears the cache and resets the project to its initial state.
- Any unsaved changes or local configurations are lost after running this command.

## File Structure
The Expo Router template provides the following structure:
```
app/
├── (tabs)/
│   ├── index.tsx        # Home screen
│   └── two.tsx          # Second tab screen
├── _layout.tsx          # Layout configuration
├── constants/
│   └── Colors.tsx       # Color constants
└── app.json             # Expo configuration
```

## Screenshots
![Home Screen](screenshots/home-screen.png)  
![QR Code](screenshots/qr-code.png)
```

---

### **Repository Structure**
Ensure your repository (`prodev-mobile-setup`) has the following structure:
```
prodev-mobile-setup/
└── mobile-app-0x00/
    ├── README.md
    ├── app-example/
    │   ├── app/
    │   │   ├── (tabs)/
    │   │   │   ├── index.tsx
    │   │   │   └── two.tsx
    │   │   ├── _layout.tsx
    │   │   └── constants/
    │   │       └── Colors.tsx
    │   └── app.json
    └── screenshots/ (optional)
```

---

### **Key Files**
1. **`app/(tabs)/index.tsx`**  
   This is the home screen of your app. Modify the text here to customize the welcome message.

2. **`app/constants/Colors.tsx`**  
   This file contains color constants used throughout the app. You can customize the colors here.

3. **`app.json`**  
   This file contains the Expo configuration for your app, such as the app name, version, and orientation.

