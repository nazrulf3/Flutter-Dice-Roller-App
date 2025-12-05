# 🎲 Flutter Dice Roller App

A beautiful and interactive dice rolling application built with Flutter. This app features a stunning gradient background and smooth animations for an engaging user experience.

## ✨ Features

- 🎯 **Interactive Dice Rolling**: Tap the button to roll a virtual dice
- 🎨 **Beautiful Gradient Background**: Eye-catching purple gradient design
- 🖼️ **Visual Dice Images**: High-quality dice images for each roll (1-6)
- 📱 **Cross-Platform**: Runs on Android, iOS, Web, Windows, macOS, and Linux
- 🔄 **Smooth Animations**: Responsive UI with instant feedback
- 🎲 **Random Number Generation**: Uses Dart's built-in Random class for fair rolls

## 📱 Screenshots

*Add screenshots of your app here*

## 🚀 Getting Started

### Prerequisites

- [Flutter SDK](https://docs.flutter.dev/get-started/install) (3.0 or higher)
- [Dart SDK](https://dart.dev/get-dart) (included with Flutter)
- An IDE like [VS Code](https://code.visualstudio.com/) or [Android Studio](https://developer.android.com/studio)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/nazrulf3/Flutter-Dice-Roller-App.git
   cd Flutter-Dice-Roller-App
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

## 🏗️ Project Structure

```
lib/
├── main.dart              # App entry point
├── gradient_container.dart # Gradient background container
├── dice_roller.dart       # Main dice rolling logic
└── styled_text.dart       # Reusable styled text widget

assets/
└── images/
    ├── dice-1.png         # Dice images for each face
    ├── dice-2.png
    ├── dice-3.png
    ├── dice-4.png
    ├── dice-5.png
    └── dice-6.png
```

## 🎯 How It Works

1. **Main App**: The app starts with a `MaterialApp` that displays a gradient container
2. **Gradient Container**: Creates a beautiful purple gradient background using `LinearGradient`
3. **Dice Roller**: A stateful widget that:
   - Displays the current dice image
   - Generates random numbers (1-6) when the button is pressed
   - Updates the UI with the new dice face
4. **Interactive Button**: A styled button that triggers the dice roll animation

## 🛠️ Built With

- **Flutter** - UI framework
- **Dart** - Programming language
- **Material Design** - Design system

## 📚 Learning Resources

This project is perfect for beginners learning Flutter. Key concepts demonstrated:

- StatefulWidget vs StatelessWidget
- State management with `setState()`
- Asset management and images
- Custom widgets and composition
- Material Design components
- Gradient backgrounds
- Random number generation

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the project
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🎓 About

This is a learning project created while following Flutter development tutorials. It demonstrates fundamental Flutter concepts in a fun and interactive way.

---

**Happy Coding!** 🚀

For help getting started with Flutter development, view the [online documentation](https://docs.flutter.dev/), which offers tutorials, samples, guidance on mobile development, and a full API reference.
