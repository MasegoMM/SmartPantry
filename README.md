# Smart Pantry Manager 🍽️

## Project Overview
Smart Pantry Manager is a Java-based Android application developed using Android Studio. It helps users manage their pantry ingredients, reduce food waste, and discover recipes they can prepare using ingredients they already have at home.

## Key Features
- **Pantry Management:** Add, view, edit, and delete ingredients, including quantities, units, and optional expiry dates.
- **Recipe Collection:** Browse a database of at least 15–20 recipes with ingredients and preparation instructions.
- **Suggested Recipes:** Displays only recipes for which all required ingredients are available in the pantry in sufficient quantities.
- **Ingredient Matching:** Handles common differences such as singular and plural ingredient names and unit conversions.
- **Recipe Details:** View the required ingredients and preparation method for each recipe.
- **Settings:** Manage preferences such as expiry alerts or measurement units.
- **Data Persistence:** Stores pantry and recipe data in a database so information remains available after restarting the app.
- **Input Validation:** Checks ingredient entries to help maintain accurate pantry records.

## Core Business Logic
The application uses a strict recipe-matching system. A recipe is suggested only when every required ingredient is available in the pantry in the required quantity. Recipes with missing or insufficient ingredients are excluded from the main suggestions list.

## Technologies Used
- **Programming Language:** Java
- **Development Environment:** Android Studio
- **Database:** SQLite
- **User Interface:** XML layouts and Android UI components
- **Data Display:** RecyclerView or ListView with a custom Adapter
- **Navigation:** Android Intents

## Learning Objectives
This project demonstrates Android application development, database management, CRUD operations, input validation, screen navigation, and the implementation of business logic to solve a real-world problem.

## Project Goal
To provide a practical pantry-management solution that helps users make better use of available ingredients, plan meals, and minimise avoidable food waste.

## Project Status
Developed as part of the Mobile App Development 700 practical assignment.
