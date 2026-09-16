# Drawing App

An Android drawing application built with Kotlin and Jetpack Compose. The app provides a canvas for creating and editing drawings, local and cloud storage, sharing, and image analysis features.

## Features

* Freehand drawing with configurable brush size and color
* Shape drawing tools
* Save and manage drawings in a gallery
* Local persistence using Room
* User authentication and cloud storage with Firebase
* Community gallery for shared drawings
* Image analysis tools
* Android sharing support
* Configurable application settings
* Unit tests for drawing, persistence, settings, and UI-related behavior

## Technologies

* Kotlin
* Android / Jetpack Compose
* MVVM architecture
* Room
* Firebase
* Gradle

## Running the Project

1. Clone the repository.
2. Open the `DrawingApp` directory in Android Studio.
3. Allow Gradle to download and configure the required dependencies.
4. Run the application on an Android emulator or physical Android device.

## Project Structure

The application separates UI screens, ViewModels, data repositories, persistence, navigation, and reusable UI components. Drawing data can be stored locally while authenticated users can access cloud and community functionality.

## About

This project was developed as a team project for CS 4530 at the University of Utah.
