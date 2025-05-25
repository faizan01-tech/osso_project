# OSSO Project - Flutter Authentication UI

A modern Flutter authentication UI project with beautiful design and smooth animations.

## Features

- Beautiful and modern UI design
- Smooth animations and transitions
- Sign In and Sign Up screens
- Social media authentication options
- Responsive layout
- Custom theme support

## Project Structure

```
lib/
├── main.dart                    # App entry point and root widget
├── screens/
│   ├── welcome_screen.dart      # Initial welcome screen with sign in/up options
│   ├── signin_screen.dart       # User sign in screen
│   ├── signup_screen.dart       # New user registration screen
│   └── forget_passsword_screen.dart  # Password recovery screen
├── widgets/
│   ├── custom_scaffold.dart     # Custom scaffold with background image
│   └── welcome_button.dart      # Reusable button for welcome screen
└── theme/
    └── theme.dart              # App theme configuration and colors
```

## Code Overview

### Screens

1. **WelcomeScreen** (`screens/welcome_screen.dart`)
   - Initial landing screen
   - Logo display
   - Sign in and Sign up options
   - Smooth navigation transitions

2. **SignInScreen** (`screens/signin_screen.dart`)
   - Email and password inputs
   - Form validation
   - Remember me option
   - Forgot password link
   - Social media login options

3. **SignUpScreen** (`screens/signup_screen.dart`)
   - Full name, email, and password inputs
   - Form validation
   - Terms agreement checkbox
   - Social media signup options

4. **ForgetPasswordScreen** (`screens/forget_passsword_screen.dart`)
   - Password recovery functionality
   - Email input for reset link

### Widgets

1. **CustomScaffold** (`widgets/custom_scaffold.dart`)
   - Custom app background
   - Consistent styling across screens
   - Transparent app bar

2. **WelcomeButton** (`widgets/welcome_button.dart`)
   - Customizable button widget
   - Animated transitions
   - Flexible styling options

### Theme

**Theme Configuration** (`theme/theme.dart`)
- Material 3 color scheme
- Light and dark theme support
- Custom button styles
- Consistent color palette

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/faizan01-tech/osso_project.git
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

## Screenshots

Coming soon...

## Contributing

Feel free to contribute to this project by creating issues or submitting pull requests.

## License

This project is open source and available under the MIT License.
