# ⚡ FLASH CHECK - Typing Speed Tracker

<div align="center">

![Flutter](https://img.shields.io/badge/Flutter-Framework-blue?style=for-the-badge\&logo=flutter)
![Dart](https://img.shields.io/badge/Dart-Language-blue?style=for-the-badge\&logo=dart)
![Material Design](https://img.shields.io/badge/UI-Material_Design-success?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Mobile-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)

### A Flutter-Based Typing Speed Tracker Application

</div>

---

## 📖 Overview

**FLASH CHECK** is a simple and interactive typing speed tester developed using **Flutter** and **Dart**.

The application allows users to test their typing skills by typing randomly generated paragraphs within a specified time limit. It calculates the user's **Words Per Minute (WPM)** and **typing accuracy** while also tracking the user's best performance.

The project is developed as an educational application to demonstrate concepts such as:

* Flutter Application Development
* Stateful Widget Management
* Navigation Between Screens
* Timer Implementation
* User Input Handling
* Performance Calculation Logic
* Material Design UI

---

# ✨ Key Features

### 🎚️ Multiple Difficulty Levels

Users can choose from different difficulty levels:

* Easy
* Medium
* Hard

### ⏳ Countdown Timer Based Test

* The timer automatically starts when the typing test begins.
* The test automatically ends when the timer reaches zero.

### ⚡ Automatic WPM Calculation

The application calculates typing speed automatically after test completion.

### 🎯 Accuracy Percentage Calculation

Typing accuracy is calculated based on correctly typed words.

### 🏆 Best WPM Tracking

The application stores and displays the user's best typing speed during the current session.

### 📊 Result Dialog

After completion of the test, results are displayed through an interactive dialog box.

### 📱 Clean and Simple User Interface

Built using Material Design principles to provide a user-friendly experience.

### 🔄 Proper Screen Navigation

Smooth navigation between screens using Flutter Navigator.

---

# 🏗️ System Architecture

```text
Home Screen
      |
      ↓
Select Difficulty
      |
      ↓
Start Typing Test
      |
      ↓
Countdown Timer Starts
      |
      ↓
User Types Paragraph
      |
      ↓
Timer Ends
      |
      ↓
Calculate WPM & Accuracy
      |
      ↓
Display Result Dialog
      |
      ↓
Return Results to Home Screen
```

---

# 🛠️ Technologies Used

| Technology      | Purpose                        |
| --------------- | ------------------------------ |
| Flutter         | Cross-platform App Development |
| Dart            | Programming Language           |
| Material Design | User Interface Design          |
| Navigator       | Screen Navigation              |
| Timer Class     | Countdown Timer Functionality  |

---

# 📂 Project Structure

```text
Flash_Check/
│
├── lib/
│   ├── main.dart
│   ├── home.dart
│   └── type.dart
│
├── pubspec.yaml
│
└── README.md
```

---

# 🧠 Application Workflow

## User Flow

1. Launch the application.
2. Select a difficulty level.
3. Start the typing test.
4. Timer starts automatically.
5. Type the given paragraph.
6. Wait for the timer to finish.
7. View typing speed and accuracy results.
8. Results are returned to the home screen.
9. Best WPM is updated if the new score is higher.

---

# 🧮 Calculation Logic

## WPM Calculation

Words Per Minute (WPM) is calculated based on the number of correctly typed words.

```text
WPM = Number of Correct Words
```

---

## Accuracy Calculation

Typing accuracy is calculated using the following formula:

```text
Accuracy = (Correct Words / Total Typed Words) × 100
```

---

# ⚙️ Installation and Setup

## Step 1: Install Flutter SDK

Download and install Flutter SDK from the official Flutter website.

---

## Step 2: Clone the Repository

```bash
git clone https://github.com/your-username/FLASH-CHECK.git
```

Move into the project directory:

```bash
cd FLASH-CHECK
```

---

## Step 3: Install Dependencies

Execute:

```bash
flutter pub get
```

---

## Step 4: Run the Application

Execute:

```bash
flutter run
```

---

# 🚀 Application Screens

## 🏠 Home Screen

* Displays the application's home page.
* Allows users to choose difficulty levels.
* Displays the best WPM.

---

## ⌨️ Typing Screen

* Shows the typing paragraph.
* Starts the countdown timer.
* Accepts user input.

---

## 📊 Result Dialog

Displays:

* WPM
* Accuracy Percentage
* Final Performance

---


# 🌟 Future Enhancements

* [ ] Save History of Tests
* [ ] Store Best WPM Permanently Using Shared Preferences
* [ ] Add Animations
* [ ] Add Live WPM Counter
* [ ] Add Dark Mode
* [ ] Add Progress Graphs
* [ ] Add Multiple Language Support

---

# 🧪 Testing

| Test Case            | Expected Result            |
| -------------------- | -------------------------- |
| Select Difficulty    | Correct Test Starts        |
| Timer Completion     | Test Ends Automatically    |
| Typing Input         | User Input Accepted        |
| WPM Calculation      | Correct WPM Displayed      |
| Accuracy Calculation | Correct Accuracy Displayed |
| Best WPM Update      | Best Score Updated         |

---

# 🤝 Contribution

Contributions are welcome.

### Steps:

1. Fork the repository.

2. Create a new feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push the changes.

```bash
git push origin feature-name
```

5. Create a Pull Request.

---

# 👨‍💻 Developed For Learning Purpose

This project demonstrates:

* Stateful Widgets
* Timer Usage
* TextEditingController
* Navigator with Data Return
* UI Design Basics
* Result Calculation Logic

---

# 👨‍💻 Author

**Ajith P A**

---

# 📄 License

This project is developed for educational and learning purposes.

---

<div align="center">

## ⭐ If you found this project useful, consider giving it a star!

### ⚡ FLASH CHECK

**Test Fast • Type Faster • Improve Continuously**

*Built with ❤️ using Flutter and Dart*

</div>
