# Android Room Database Example (Java)

An Android reference application demonstrating local SQLite data persistence using the **Room Persistence Library** in Java.

## Overview
This project provides a clean reference implementation of Room ORM in an Android Java environment. It demonstrates how to set up an object-relational mapping layer to handle database access safely, abstracting raw SQLite operations behind structured Java interfaces and objects.

## Key Features
* **Room ORM Integration:** Safe abstraction over SQLite for local storage persistence.
* **DAO Pattern Implementation:** Structured data access operations defined via `UserDao`.
* **Database Entity Definition:** Data model mapped using Room annotations in `User`.
* **Database Instance Setup:** Centralized database lifecycle management using `MyRoomDatabase`.

## Architecture & Project Structure
```
com.example.roomdatabaseexample/
├── MainActivity.java
└── myDb/
    ├── MyRoomDatabase.java
    ├── User.java
    └── UserDao.java
```

## Tech Stack
* **Language:** Java 8
* **Persistence:** `androidx.room:room-runtime:2.3.0`
* **Annotation Processor:** `androidx.room:room-compiler:2.3.0`
* **Min SDK:** 16 (Android 4.1)
* **Target SDK:** 30

## Quick Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/m-lomba/room-database-example.git
   ```
2. Open the project in **Android Studio**.
3. Build and run on an emulator or physical device running API 16 or higher.
