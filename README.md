# PayrollPro - Payroll Management System

A comprehensive Flutter application for payroll and attendance management, converted from a React/TypeScript project.

## Features

### 🏢 Multi-Role Support
- **Super Admin**: Manage all companies, billing, and system-wide settings
- **Company Admin**: Manage employees, payroll, and attendance for your company
- **Employee**: Clock in/out, view payslips, and track attendance

### 💼 Key Capabilities
- ✅ Biometric attendance tracking with GPS verification
- ✅ Automated payroll generation
- ✅ Employee management
- ✅ Real-time reports and analytics
- ✅ Multi-company/tenant support
- ✅ Comprehensive dashboards with KPI cards
- ✅ Mobile-optimized employee interface

## Project Structure

```
lib/
├── main.dart                 # App entry point
├── screens/                  # All screen/page widgets
│   ├── landing_page.dart
│   ├── login_page.dart
│   ├── super_admin_dashboard.dart
│   ├── company_admin_dashboard.dart
│   └── employee_mobile_app.dart
├── widgets/                  # Reusable widget components
│   ├── custom_widgets.dart   # Badge, Card, Button, Icons
│   ├── kpi_card.dart
│   ├── dashboard_sidebar.dart
│   └── dashboard_header.dart
├── theme/                    # App theming
│   └── app_theme.dart        # Colors, gradients, text styles
├── models/                   # Data models (to be added)
└── utils/                    # Utility functions (to be added)
```

## Getting Started

### Prerequisites
- Flutter SDK (>=3.0.0)
- Dart SDK
- VS Code or Android Studio

### Installation

1. Navigate to the project directory:
```bash
cd "c:\Users\hussein\OneDrive\Desktop\code\flutter apps\payroll_management_app"
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

### Running on Different Platforms

```bash
# Web
flutter run -d chrome

# Android
flutter run -d android

# iOS (macOS only)
flutter run -d ios

# Windows
flutter run -d windows
```

## Demo Mode

The app includes a **Demo Mode** that allows you to view all dashboards and interfaces without logging in:

1. On the landing page, click **"View All Dashboards"** button
2. Navigate between tabs to explore:
   - Super Admin Dashboard
   - Company Admin Dashboard
   - Employee Mobile App
   - Landing Page

## Conversion from React/TypeScript

This Flutter app is a conversion of the original React/TypeScript PayrollPro application. Key conversions include:

| React Component | Flutter Equivalent |
|----------------|-------------------|
| TSX/JSX | Flutter Widgets |
| Tailwind CSS | ThemeData + Custom Styles |
| React State (useState) | StatefulWidget + setState |
| React Props | Constructor parameters |
| Radix UI Components | Custom Flutter widgets |
| Lucide React Icons | Material Icons |
| Recharts | fl_chart (planned) |

## Dependencies

- **google_fonts**: ^6.1.0 - Custom font support
- **provider**: ^6.1.1 - State management
- **fl_chart**: ^0.68.0 - Charts and graphs
- **flutter_svg**: ^2.0.10 - SVG support
- **intl**: ^0.19.0 - Internationalization

## Customization

### Colors & Theme
Edit `lib/theme/app_theme.dart` to customize:
- Primary colors
- Gradients
- Text styles
- Card styles
- Button styles

### Add New Screens
1. Create a new file in `lib/screens/`
2. Import necessary widgets from `lib/widgets/`
3. Add navigation in `lib/main.dart`

## Next Steps

- [ ] Add backend API integration
- [ ] Implement authentication
- [ ] Add database persistence
- [ ] Implement charts with fl_chart
- [ ] Add form validation
- [ ] Implement file upload/download
- [ ] Add unit tests
- [ ] Add integration tests

## License

This project is for demonstration purposes.

## Screenshots

The app features:
- Modern, clean UI with gradient accents
- Responsive design for mobile and desktop
- Comprehensive admin dashboards
- Mobile-first employee experience
- Professional landing page with pricing

---

**Converted from React to Flutter** • Built with ❤️ using Flutter
