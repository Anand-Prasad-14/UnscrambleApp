# 🌟 Excited to Share My Latest Android App Project: The Unscramble App! 🚀


I am thrilled to present my latest project: The Unscramble App, a single-player word scrambler game designed to provide an engaging and fun experience while putting your vocabulary to the test! This app is built using the best practices in Android app development, focusing on a clean architecture that ensures smooth gameplay and efficient data management.

## 📱 App Overview:
The Unscramble App challenges players to guess a word from a set of scrambled letters. Players earn points for each correct guess, and they can try as many times as they want or skip the word if they're stuck. The game consists of 10 scrambled words per round, providing endless fun and learning opportunities.

## <img src="https://github.com/user-attachments/assets/e8e07e72-1ea9-4c84-9faf-c23fd59c8053" alt="Home Screen" width="300"/> <img src="https://github.com/user-attachments/assets/2b272f03-f35e-44b7-9ea4-61ced0fe246b" alt="Finish Screen" width="300"/>

## 🏗 Recommended App Architecture:
The development of the Unscramble App adheres to a clean architectural pattern that divides the app into distinct layers:

 - UI Layer: This layer displays the game data on the screen and handles user interaction. It is designed to be independent of data management, allowing for a seamless user experience.

 - Data Layer: This layer is responsible for storing, retrieving, and exposing app data, ensuring efficient and reliable data handling.

 - Optional Domain Layer: Although beyond the scope of this project, a domain layer can be added to simplify interactions between the UI and data layers, promoting reusability and maintainability.

## 🔄 Unidirectional Data Flow (UDF):
To enhance app performance and maintainability, the Unscramble App implements a Unidirectional Data Flow (UDF) pattern. Here's how it works:

 - Event: User actions, such as clicking a button or skipping a word, generate events passed upward to the ViewModel.

 - Update State: The ViewModel handles these events, updating the state accordingly.

 - Display State: The updated state flows downward, and the UI reflects these changes.

This UDF approach decouples the UI components from the state management, resulting in a more organized and efficient app architecture.

## 🔧 Technical Details:
Languages & Tools: Kotlin, Android Studio, Jetpack Compose, MVVM Architecture.

🚀 Next Steps:

I am continuously working on refining the app's features and exploring potential additions, such as multiplayer modes, time-based challenges, and more!

