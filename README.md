# Course-Dash-Board-App
Course Dashboard App
A modern Flutter application designed to help students manage their courses with an intuitive and user-friendly interface.

Features
Splash Screen: Beautiful introduction with app branding

Onboarding Experience: Interactive introduction to app features

Home Dashboard: View enrolled courses and quick overview

Course Management: Browse, filter, and enroll in courses

User Profile: Personal information and app settings

Bottom Navigation: Easy navigation between main app sections

Course Enrollment: Simple one-tap course enrollment system

Category Filtering: Filter courses by Science, Arts, or Technology

Exit Confirmation: Secure logout with confirmation dialog

Animated UI Elements: Engaging animations throughout the app

Screens
Splash Screen - App branding and loading indicator

Onboarding Screens - Three-page introduction to app features

Home Tab - Displays enrolled courses and quick stats

Courses Tab - Browse and enroll in available courses

Profile Tab - User information and app settings

Installation
Ensure you have Flutter installed on your system

Clone or download this project

Navigate to the project directory

Run flutter pub get to install dependencies

Run flutter run to launch the app on your connected device/emulator

Dependencies
This app uses only Flutter's built-in packages and requires no external dependencies.

How to Use
Getting Started: Launch the app and go through the onboarding process

Browse Courses: Navigate to the Courses tab to see available courses

Enroll in Courses: Tap the "+" icon next to any course to enroll

View Enrollments: Check your enrolled courses in the Home tab

Filter Courses: Use the dropdown to filter courses by category

Add New Courses: Use the floating action button in Courses tab to add custom courses

Logout: Use the logout button in Profile tab to exit the app

Course Categories
Science: Biology, Chemistry, Physics, and related courses

Arts: Literature, History, Art, and related courses

Technology: Programming, Development, and IT-related courses

App Structure
text
lib/
├── main.dart                 # Main application entry point
├── splash_screen.dart        # Splash screen implementation
├── onboarding_screen.dart    # Onboarding screens
└── main_dashboard.dart       # Main app with all dashboard features
Customization
You can easily customize:

App colors by modifying the primarySwatch in ThemeData

Course data by updating the courses list

Categories by modifying the categories list

UI elements throughout the application

Supported Platforms
Android

iOS

Web

Desktop (Windows, macOS, Linux)

Future Enhancements
Potential features for future versions:

User authentication system

Backend integration for course data

Progress tracking for enrolled courses

Notifications for course updates

Social features for student interaction

Dark mode support

Contributing
Feel free to fork this project and submit pull requests for any improvements.
