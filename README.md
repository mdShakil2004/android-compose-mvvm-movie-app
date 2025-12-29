## Android-compose-mvvm-movie-app


A modern Android app built using **Kotlin, Jetpack Compose, MVVM, Coroutines, Flow, Hilt, and Room**.  
MovieHub fetches movie data from a remote API, manages state efficiently, and demonstrates clean, scalable architecture with offline support.

---

## Features

- Display **movies list** from a remote API with smooth Jetpack Compose UI  
- **Favorites / Watchlist**: Save and manage favorite movies locally  
- **Search movies**: Quickly find movies by title  
- **Loading & Error handling**: Responsive UI with progress indicators and error messages  
- **Offline caching**: Access favorite and previously viewed movies even without internet  
- **Clean MVVM + Repository pattern**: Scalable and maintainable architecture  
- **Dependency Injection with Hilt**: Decoupled and testable code  

---

## Tech Stack

- **Language**: Kotlin  
- **UI**: Jetpack Compose  
- **Architecture**: MVVM + Repository Pattern  
- **Async operations**: Coroutines + Flow  
- **Dependency Injection**: Hilt  
- **Local Database**: Room  
- **Networking**: Retrofit  

---

## What I Learned
- MVVM with Repository & ViewModel
- Async API calls with Coroutines & Flow
- Compose UI + state management
- Dependency Injection (Hilt)


<img width="400" height="835" alt="image" src="https://github.com/user-attachments/assets/25610554-dd14-49d9-ba6f-11e1ebf9775d" />

<img width="1024" height="1536" alt="flow diagram" src="https://github.com/user-attachments/assets/a925ce66-8b61-44e8-bd54-0df9b68aef50" />

## Project Structure Highlights

- `data/` → Repository, API services, and Room database entities/DAOs  
- `ui/` → Compose screens, navigation, and UI components  
- `viewmodel/` → Handles UI state, collects Flow from repository  
- `di/` → Hilt modules for dependency injection  

---

## Learning Highlights

While building MovieHub, I learned to:

- Implement **MVVM architecture** for clean separation of concerns  
- Handle **API calls asynchronously** using **Coroutines & Flow**  
- Manage **UI state** in Jetpack Compose effectively  
- Add **offline support** using Room  
- Implement **dependency injection** with Hilt  
- Write **clean, maintainable Kotlin code**  

---

## How to Run

1. Clone the repo:

```bash
git clone https://github.com/mdShakil2004/android-compose-mvvm-movie-app.git
