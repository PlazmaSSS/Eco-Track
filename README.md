# Eco-Track

A native Android application designed to track and manage environmental data, focusing on high performance, clear architecture, and robust offline capabilities.

## 🛠 Tech Stack & Architecture

- **Language:** Kotlin
- **Architecture:** MVVM (Model-View-ViewModel) pattern for clean separation of concerns and maintainable code layout.
- **Database:** Room Persistence Library (SQLite wrapper) for efficient local data storage and offline-first functionality.
- **Components:** Components integration through proper DAO (Data Access Object) interfaces and structured ViewModels.

## 🚀 Key Features

- **MVVM Data Flow:** Seamless reactive updates from the local database to the user interface.
- **Room Integration:** Custom DAO interfaces handling secure and lightweight local data entries.
- **Clean UI:** Responsive layouts tailored for an intuitive user tracking experience.

## 📂 Project Structure

The project code is organized into clean layers:
- `data/`: Room database configurations, entities, and DAO interfaces.
- `ui/`: ViewModels and UI layouts ensuring independent state handling.
