# Event Management - Flutter Login App

A modern, responsive, and visually appealing Flutter application dedicated solely to the **Login Page**.

---

## 📱 Features

- **Event Theme Design**: Vibrant gradient logo badge, soft shadows, and clean modern typography.
- **Form Fields & Validation**:
  - **Email Field**: Real-time format validation with `@` and domain checks.
  - **Password Field**: Minimum length validation (6+ characters) with an interactive **show/hide password toggle**.
- **Interactive Controls**:
  - **Remember Me Checkbox**: Toggle credential persistence state.
  - **Forgot Password Modal**: Clean dialog to input an email address to request a reset link.
- **Loading State Feedback**:
  - Circular progress indicator on the button while authenticating.
  - Dynamic Floating SnackBar on successful login.
- **Social Login Row**: One-click Google, Apple, and Facebook integration buttons.
- **Responsive Layout**: Wrapped in `SingleChildScrollView` to prevent keyboard overflow across all screen sizes.

---

## 📁 Project Structure

```
d:\Event mgt\
├── lib/
│   ├── main.dart                 # Application entry point & theme bootstrap
│   ├── screens/
│   │   └── login_screen.dart     # Full interactive Login UI & form state
│   └── theme/
│       └── app_theme.dart        # Color palette, input decorations & typography
├── pubspec.yaml                  # Flutter package definition and assets
└── README.md
```

---

## 🚀 How to Run the App

### Prerequisites
Make sure you have Flutter installed. If not, download and install Flutter from [flutter.dev](https://flutter.dev/docs/get-started/install).

### 1. Fetch Dependencies
In PowerShell or Terminal from `d:\Event mgt`:
```powershell
flutter pub get
```

### 2. Run on Chrome (Web)
```powershell
flutter run -d chrome
```

### 3. Run on Android Emulator or Physical Device
```powershell
flutter run
```
