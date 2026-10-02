# Smart-Pantry-Manager
A Java-based Android application utilizing Room SQLite, Navigation, and UI component structures for local pantry item tracking and automated recipe matching.




PROJECT OVERVIEW

Smart Pantry Manager is a Java based Android application designed for local pantry inventory tracking and automated recipe matching. Built using Room SQLite for local data persistence, it features a single activity layout with bottom tab navigation to manage pantry items and discover meal suggestions based on available ingredients.

KEY FEATURES

2.1 Local Data Persistence
Powered by Room ORM with structured SQLite database tables for items and recipes.

2.2 Inventory Management
Add, view, edit, and delete pantry items along with quantity, units, and expiry dates.

2.3 Automated Recipe Matching
Custom string normalization matching engine compares available pantry items against a database of pre-seeded recipes.

2.4 Bottom Navigation Interface
Quick toggling between Pantry, Suggestions, and Settings screens.

PROJECT STRUCTURE AND CLASS DIRECTORY

Source Location: app/src/main/java/com/example/smartpantrymanager/

3.1 AppDatabase.java
Central database class managing Room initialization and automatic table seeding.

3.2 MainActivity.java
Main entry point handling bottom navigation and screen switching.

3.3 PantryDao.java
Data Access Object defining query methods for pantry item CRUD operations.

3.4 PantryItem.java
Entity class defining the database structure for pantry inventory items.

3.5 Recipe.java
Entity class defining the database structure for recipe entries.

3.6 RecipeDao.java
Data Access Object defining query methods for recipe data.

3.7 StringUtil.java
Utility class providing string normalization and ingredient matching logic.

SYSTEM REQUIREMENTS AND INSTALLATION STEPS

4.1 Clone or download the repository files to your local machine.
4.2 Launch Android Studio and open the project directory.
4.3 Wait for Gradle to finish sync and download necessary dependencies.
4.4 Launch an Android Virtual Device (API level 34 or higher recommended).
4.5 Click Run 'app' or press Shift + F10 to compile and execute the project.

TECHNOLOGIES AND TOOLS USED

5.1 Programming Language: Java
5.2 Development Environment: Android Studio
5.3 Local Database Framework: Room Database (SQLite)
5.4 User Interface Components: Material Components, BottomNavigationView, RecyclerView
5.5 System Architecture: Single Activity with Navigation Fragments

5.1 Programming Language: Java
5.2 Development Environment: Android Studio
5.3 Local Database Framework: Room Database (SQLite)
5.4 User Interface Components: Material Components, BottomNavigationView, RecyclerView
5.5 System Architecture: Single Activity with Navigation Fragments
