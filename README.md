# React Native MCQ Exam App

## Overview

This React Native application is designed for conducting Multiple Choice Questions (MCQ) exams. The app dynamically loads questions from a JSON data source, implements a countdown timer, allows users to select and submit answers, and provides a results screen with score calculation and the option to review answers.

## Features

- **MCQ Exam Screen:**
  - Display questions and answer options dynamically from a JSON data source.
  - Countdown timer for the exam.
  - User-friendly UI with card view for each question.
  - Ability to select and submit answers.
  - Automatic navigation to the next question upon submission.

- **Results Submission:**
  - Calculate and display the user's score at the end of the exam.
  - Provide feedback on correct and incorrect answers.
  - Option to review all questions and answers.

## How to Run the Project

### Prerequisites

- Node.js and npm installed.
- Expo CLI installed globally (`npm install -g expo-cli`).

### Steps

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/PriyanshSanghavi/MCQExamApp.git
   cd MCQExamApp
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Run the App:**

   ```bash
   npm start
   ```

   - This will start the development server and open the Expo DevTools in your default browser.
   - You can run the app on an emulator/simulator or scan the QR code with the Expo Go app on your mobile device.

4. **Explore the App:**

   - Answer the MCQs, submit the exam, and view your results.
   - Review answers at the end of the exam.

## Customize

- Modify the `questions.json` file to add your own set of questions.
- Adjust styling and UI components in the `App.js` file to meet your design preferences.

## Technologies Used

- React Native
- React Navigation
- React Native Paper

