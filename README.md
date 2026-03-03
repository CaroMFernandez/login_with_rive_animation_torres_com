# 🐻 Animated Login Screen with Rive & Flutter

## 📚 Course Information
- **Subject:** Graficación  
- **Professor:** Rodrigo Fidel Gaxiola Sosa  
- **Group:** 5SA  

---

## 🚀 Project Overview

This project is an interactive login screen built with **Flutter** and enhanced using **Rive animation**.  
It features a responsive animated character that reacts to user interactions such as typing email, focusing password, and showing success/failure feedback.

---

## ✨ Main Features

- 📧 Elegant email and password input fields  
- 👀 Bear follows email text while typing  
- 🙈 Bear covers eyes when password is focused  
- 🔐 Toggle password visibility  
- 🎯 Success and fail animations triggered via state  
- 🔄 Smooth interaction using Rive State Machine  
- 🧠 Proper resource cleanup using `dispose()`

---

## 🎨 What is Rive?

**Rive** is a real-time animation tool that lets designers and developers create vector animations that can respond to logic and input.  
Instead of using static GIFs or videos, Rive animations run dynamically and react to user actions in real time.

Learn more: https://rive.app/

---

## 🔁 What is a State Machine?

A **State Machine** is a system that defines:

- Different animation states (Idle, Checking, Hands Up, Success, Fail)
- Transitions between states
- Rules and triggers for those transitions

In this project, the Rive State Machine controls the bear animation through inputs such as:

- `isChecking`  
- `isHandsUp`  
- `trigSuccess`  
- `trigFail`

These inputs allow Flutter to communicate with the animation logic in Rive.

---

## 🛠 Technologies

- 💙 Flutter  
- 🎯 Dart  
- 🖥 Visual Studio Code  
- 🧠 Rive Animation  
- 📁 Git & GitHub  

---

## 📂 Project Structure

```
lib/
 ├── main.dart
 ├── screens/
 │     └── login_screen.dart
assets/
 └── animated_login_bear.riv
pubspec.yaml
```

### 📌 Key Files

- **main.dart** – App entry point  
- **login_screen.dart** – UI + animation handling  
- **pubspec.yaml** – Flutter package & assets  
- **assets/** – Rive animation file

---

## 🎥 Demo

Below is a preview of how the login interaction works:

![Demo GIF](demo.gif)

*(Replace `demo.gif` with your actual animated file in the repository)*

---

## 🙌 Animation Credits

Animation used from Rive Marketplace:

💫 **Remix of Login Machine**  
🔗 https://rive.app/marketplace/3645-7621-remix-of-login-machine/

All animation credit goes to the original creator on Rive Marketplace.

---

## 📦 Installation

1. Clone the repository  
2. Run:

```
flutter pub get
flutter run
```

Make sure Flutter SDK is installed and configured.

---

## 💡 Learning Outcomes

This project demonstrates:

- Building Flutter interfaces  
- Integrating Rive with State Machine logic  
- Managing user interaction  
- Proper widget lifecycle handling  
- Professional README documentation

---

## 👨‍💻 Author

Created as part of the **Graficación** course – 2026.

---

⭐ Thank you for reviewing this project! Feel free to explore and improve it!
