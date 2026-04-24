Life Hack or Urban Myth? 📱
Native Android Flashcard Game

📝 Project Overview
In an era where "productivity hacks" and viral internet rumors are everywhere, this application serves as a tool to help users distinguish between genuine life-improving shortcuts and dangerous or ineffective urban myths.

This project was developed as a native Android application using **Kotlin** to demonstrate proficiency in UI state management, activity navigation, and automated CI/CD workflows.

---

 🚀 Features
- **Welcome Screen:** A clean entry point introducing the app's purpose.
- **Interactive Flashcards:** A series of statements where users decide if a tip is a "Hack" (True) or a "Myth" (False).
- **Instant Feedback:** Real-time explanations for every answer to educate the user.
- **Scoring System:** A dynamic counter that tracks performance.
- **Personalized Results:** A score screen that provides custom feedback (e.g., "Master Hacker!" vs. "Stay Safe Online!").
- **Review Mode:** Allows users to revisit the questions and learn the correct explanations after the quiz.

---

#🛠️ Tech Stack & Architecture
- **Language:** Kotlin
- **IDE:** Android Studio
- **UI:** XML Layouts with Material Design components
- **Version Control:** Git & GitHub
- **CI/CD:** GitHub Actions for automated builds

### Design Considerations
The app follows a modular logic approach:
1.  **Data Management:** Uses a `data class` to store questions, answers, and explanations.
2.  **Navigation:** Uses `Intents` to transition between the Welcome, Quiz, and Score screens while passing score data safely.
3.  **State Logic:** Employs an index-based loop to iterate through the question set without reloading the entire activity.

---

## 🤖 GitHub Actions (CI/CD)
This project utilizes **GitHub Actions** to ensure code quality and build stability.
The workflow (`.github/workflows/build.yml`) automatically:
- Sets up the JDK 17 environment.
- Grants execution permissions to the Gradle wrapper.
- Runs an `assembleDebug` build on every push to the `main` branch.

This ensures that the code is always in a "build-ready" state and prevents integration errors.

---


---

## 🎥 Video Presentation
A full walkthrough of the app features, code structure, and GitHub Actions workflow can be found here:


---

## 📥 How to Run
1. Clone the repository:
   ```bash
   git clone [Your-GitHub-Repo-URL]