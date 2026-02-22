📌 Task Manager App – Android (MVVM + Room)

A modern Android Task Management application built using MVVM architecture and the Room Persistence Library for efficient local data storage.

This project demonstrates clean architecture principles, lifecycle-aware components, and structured separation of concerns using Android Jetpack tools.

🚀 Features

Create, update, and delete tasks

Store tasks locally using Room Database

Lifecycle-aware UI updates using ViewModel

RecyclerView-based task listing

Material Design UI components

Clean MVVM architecture implementation

🏗️ Architecture

The application follows the MVVM (Model-View-ViewModel) pattern:

🔹 UI Layer

Activities

RecyclerView Adapter

XML Layouts

🔹 ViewModel Layer

Manages UI-related data

Survives configuration changes

Exposes observable data

🔹 Repository Layer

Abstracts data operations

Acts as a single source of truth

🔹 Data Layer (Room)

Entity (Task model)

DAO (Database queries)

Database class

🛠️ Tech Stack

Language: Kotlin

Architecture: MVVM

Database: Room Persistence Library

UI: XML Layouts + RecyclerView

Build System: Gradle

📂 Project Structure
app/
 └── src/main/
      ├── java/com/yourpackage/
      │     ├── data/
      │     ├── repository/
      │     ├── viewmodel/
      │     └── ui/
      ├── res/
      └── AndroidManifest.xml
🎯 Purpose of the Project

This project was developed to:

Practice scalable Android architecture

Implement local persistence using Room

Understand lifecycle-aware components

Strengthen practical Android development skills

🔮 Future Improvements

Add sorting and filtering functionality

Implement task priority system

Add dark/light theme toggle

Introduce dependency injection (Hilt)

Convert LiveData to Kotlin Flow


📌 Author

Harsh Srivastava
