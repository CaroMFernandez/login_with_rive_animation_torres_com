# 🐻 Animated Login Screen with Rive & Flutter

## 📚 Course Information
- **Subject:** Graficación  
- **Professor:** Rodrigo Fidel Gaxiola Sosa  
- **Group:** 5SA  

---

## 🚀 Project Overview

This project consists of an interactive login screen developed with Flutter and enhanced using Rive animations.  
The main goal is to integrate a vector-based animated character that reacts dynamically to user input (email and password fields).

Instead of using static UI elements, this implementation connects user events with a State Machine, allowing the animated character to respond in real time.

---

## ✨ Main Features

- 📧 Email and Password input fields  
- 👀 Bear follows the email text while typing  
- 🙈 Bear covers its eyes when password field is focused  
- 🔐 Toggle password visibility  
- 🎯 Success and Fail animation triggers  
- 🔄 Real-time animation response using FocusNodes  
- 🧠 Proper lifecycle management using `dispose()` to prevent memory leaks  

---

## 🎨 What is Rive?

[Rive](https://rive.app/) is a real-time interactive animation platform that allows developers and designers to create vector-based animations with logic and state control.

Unlike traditional animations (like GIFs or videos), Rive animations are dynamic and can respond to user interaction through programmable inputs.

---

## 🔁 What is a State Machine?

A **State Machine** is a logic system that defines:

- Different states (Idle, Checking, Hands Up, Success, Fail)
- Transitions between states
- Conditions that trigger those transitions

In this project, the Rive State Machine works as the "brain" of the bear animation.  
Through **SMI (State Machine Inputs)** like booleans and triggers, Flutter sends signals to control the animation behavior.

---

## 🛠 Technologies Used

- 💙 Flutter
- 🎯 Dart
- 🎨 Rive (State Machine)
- 🧩 Git & GitHub
- 🖥 Visual Studio Code
- 📱 Android Emulator

---

## 📂 Basic Project Structure

```
lib/
 ├── main.dart
 ├── screens/
 │     └── login_screen.dart
assets/
 └── animated_login_bear.riv
pubspec.yaml
```

### 📌 Important Files

- **main.dart** → Entry point of the application  
- **login_screen.dart** → UI structure, animation logic, FocusNodes, StateMachineController  
- **pubspec.yaml** → Dependency management and asset registration  
- **assets/** → Contains the `.riv` animation file  

---

## 🧠 Animation Logic Architecture

- `StatefulWidget` used for dynamic UI updates  
- `StateMachineController` connected to "Login Machine"  
- SMI Inputs used:
  - `isChecking`
  - `isHandsUp`
  - `trigSuccess`
  - `trigFail`
- `FocusNode` listeners detect active input field  
- `dispose()` properly releases FocusNodes to prevent memory leaks  

---

## 🎥 Demo

Below is a demonstration of the full interaction:

![Demo GIF](demo.gif)

*(Replace demo.gif with your actual GIF file inside the repository)*

---

## 🙌 Animation Credits

Original Rive Animation:  
**"Remix of Login Machine"** from Rive Community  

🔗 https://rive.app/community/

All animation rights belong to the original creator on the Rive platform.

---

## 📦 Installation

1. Clone the repository
2. Run:

```
flutter pub get
flutter run
```

Make sure Flutter SDK and Android Studio are properly configured.

---

## 💡 Learning Outcomes

- Understanding Flutter project architecture
- Integrating vector animations with State Machines
- Managing FocusNodes and asynchronous listeners
- Applying lifecycle management using `dispose()`
- Using Git for version control
- Structuring a professional README documentation

---

## 👨‍💻 Author

Developed as part of the **Graficación** course – 2026.

---

⭐ If you like this project, feel free to explore and improve it!
