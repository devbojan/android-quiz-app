# Android Quiz Application

## 🚀 Author
Bojan Brankovic 

## Project Overview
This project is an Android Quiz Application designed to test user knowledge through interactive multiple-choice questions. It demonstrates core mobile app functionality such as user interaction, state management, and result evaluation.

Quiz applications are commonly used for learning and self-assessment, allowing users to answer questions, receive instant feedback, and track their performance. :contentReference[oaicite:0]{index=0}  

The goal of this project is to simulate a real-world quiz experience with focus on usability, responsiveness, and correct evaluation logic.

## Features
- Multiple-choice questions (4 options)
- Answer selection and validation
- Score calculation
- Instant feedback (correct/incorrect answers)
- Quiz progress tracking
- Restart / replay quiz

## Tech Stack
- Java / Kotlin (Android)
- Android SDK
- Android Studio

## Application Flow
1. User opens the app  
2. Quiz starts with first question  
3. User selects an answer  
4. App validates answer and updates score  
5. Next question is displayed  
6. Final result is shown at the end  
7. User can restart the quiz  

## Scope of Testing
- Question and answer validation  
- Score calculation logic  
- Navigation between questions  
- UI responsiveness  
- Edge cases (no selection, rapid clicks, repeated answers)  

## Tools Used
- Manual Testing  
- Android Emulator / Real Device  
- Logcat (debugging)  

## Testing Types
- Functional Testing  
- UI/UX Testing  
- Exploratory Testing  
- Regression Testing  
- Negative Testing  

## Deliverables
- Test Cases  
- Bug Reports  
- Test Execution Report  

## Key Issues Identified
- User can select multiple answers for the same question  
- Score not updated correctly after certain questions  
- App allows proceeding without selecting an answer  
- Quiz does not reset properly after completion  
- UI delay when switching between questions  

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/devbojan/android-quiz-app.git
