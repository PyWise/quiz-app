# ❓ Quiz App

A simple and fun quiz app built with Flutter. Users can roll through multiple-choice questions and test their knowledge!

## 📱 Features

- Interactive quiz with multiple questions
- Clean UI with custom buttons
- Tracks user answers and shows results at the end
- Built entirely with Dart and Flutter

## 🧠 Screens Overview

- **Start Screen**: Launches the quiz
- **Questions Screen**: Presents one question at a time with answer options
- **Result Screen**: Shows selected answers and the correct ones
- **Answer Button**: Custom widget for clean, reusable UI
- **Quiz Logic**: Managed in a central `Quiz` widget

## 🛠️ How to Run

1. Make sure Flutter is installed:

   ```bash
   flutter doctor
   ```

2. Clone this repository:

   ```bash
   git clone https://github.com/PyWise/quiz-app.git
   cd quiz-app
   ```

3. Get the packages:

   ```bash
   flutter pub get
   ```

4. Run the app:
   ```bash
   flutter run
   ```

## 📂 Project Structure

```
lib/
├── main.dart                # Entry point
├── quiz.dart                # Manages screen transitions
├── questions.dart           # Question data
├── answer_button.dart       # UI for answer choices
├── start_screen.dart        # Start screen UI
├── questions_screen.dart    # Displays questions
└── results_screen.dart      # Shows quiz results
```

## 💡 Technologies Used

- Flutter
- Dart
