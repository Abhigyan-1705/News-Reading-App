# 🗞️ Daily Brief - News Reading App

Daily Brief is a modern Android application built with **Kotlin**, **Jetpack Compose**, and the **MVVM architecture**. It delivers real-time news headlines from around the world using the **NewsAPI**, offering a fast, clean, and user-friendly news reading experience. Users can browse news by category, search for articles, and read full stories directly within the app.

## ✨ Features

1. 📰 Real-time news headlines
2. 📂 Browse news by category
3. 🔍 Search articles by keyword
4. 🌐 Read full articles inside the app using WebView
5. 🧭 Type-safe navigation with Navigation Compose
6. 🎨 Modern Material 3 UI built entirely with Jetpack Compose

## 🛠️ Tech Stack

- **Language:** Kotlin
- **UI:** Jetpack Compose
- **Architecture:** MVVM
- **Networking:** NewsAPI Java Library
- **Navigation:** Navigation Compose
- **Image Loading:** Coil 3
- **Serialization:** Kotlinx Serialization
- **Design System:** Material 3


## 📁 Project Structure

```text
MyNewsApp/
├── app/
│   ├── src/main/
│   │   ├── java/com/example/myapplication/
│   │   ├── Constant.kt
│   │   ├── HomePage.kt
│   │   ├── MainActivity.kt
│   │   ├── NewsArticlePage.kt
│   │   ├── NewsViewModel.kt
│   │   └── Route.kt
│   └── build.gradle.kts
├── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

* Android Studio Ladybug (2024.2.1) or newer
* NewsAPI API Key

### Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/Daily-Brief.git
```

2. Open the project in Android Studio.

3. Add your NewsAPI key in `Constant.kt`

```kotlin
const val API_KEY = "YOUR_API_KEY"
```

4. Build and run the application.

---

## 🏗️ Architecture

The application follows the **MVVM (Model-View-ViewModel)** architecture pattern.

```text
UI (Jetpack Compose)
        │
        ▼
    ViewModel
        │
        ▼
      NewsAPI
```


