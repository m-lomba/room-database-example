# Android Room Database Example

An Android reference application demonstrating local SQLite data persistence using the Room Persistence Library in Java.

## Overview
This project provides a reference implementation of Room ORM in an Android Java environment. It demonstrates how to set up an object-relational mapping layer to handle database access safely, abstracting raw SQLite operations behind structured Java interfaces and objects.

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
* **Min SDK:** 16 (Android 4.1)
* **Target SDK:** 30

## Quick Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/m-lomba/room-database-example.git
   ```
2. Open the project in Android Studio.
3. Build and run on an emulator or physical device running API 16 or higher.
