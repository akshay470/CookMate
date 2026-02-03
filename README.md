# CookMate
Smart Android Recipe Application built using Kotlin and Room Database
# 🍳 CookMate — Smart Recipe Application (Android)

CookMate is a modern Android-based Recipe Application designed to help users discover, explore, and cook delicious recipes easily.
 The app provides categorized recipes, popular food suggestions, step-by-step cooking instructions,
  and daily cooking tips — all in a clean and user-friendly interface.

---

## 📌 Project Overview

CookMate is built to solve a simple but common problem — finding cooking ideas quickly with proper instructions.
The application uses a local database to store recipes and displays them using optimized UI components like RecyclerView and ScrollView.

The main goal of this project is to provide:

- Easy recipe browsing
- Category-based filtering
- Fast local database access
- Smooth UI experience
- Helpful cooking tips

---

## ✨ Key Features

### 🏠 Home Screen
- Greeting message (Hello Foodie)
- Search recipe option
- Category section with icons and labels
- Popular Recipes horizontal list
- Cooking Tip of the Day card

### 📂 Categories
- Salad
- Main Dish
- Drinks
- Desserts

Users can click any category to view related recipes.

### 🔥 Popular Recipes Section
- Shows trending and most popular recipes
- Implemented using RecyclerView
- Horizontal scrolling supported

### 📖 Recipe Details Screen
- Recipe Image
- Ingredients List
- Step-by-step cooking instructions
- Cooking time display
- Easy navigation

### 🔍 Search Feature
- Allows searching recipes by name
- Improves user experience

### 💡 Cooking Tip Section
- Displays daily cooking tips
- Enhances engagement and learning
- Adds professional app feel

---

## 🛠 Tech Stack Used

### Programming Language
- Kotlin

### UI Design
- XML Layouts
- ConstraintLayout
- ScrollView
- LinearLayout

### Database
- Room Database (SQLite)
- Preloaded recipe database (Asset Database)

### Architecture Components
- ViewBinding
- RecyclerView Adapter
- Activity-based navigation

---

## 📱 Application Screens

### Home Screen Includes:
- Header greeting
- Search bar
- Category cards
- Popular recipe list
- Cooking tip card at bottom

### Category Screen:
- Displays recipes based on selected category

### Recipe Detail Screen:
- Shows full recipe information
- Ingredients and cooking steps
- Image preview

---

## ⚙ How The Application Works

### Step 1:
App launches HomeActivity.

### Step 2:
Room database loads recipe data from asset database.

### Step 3:
Popular recipes are filtered and displayed using RecyclerView.

### Step 4:
When user clicks on:
- Search → Opens SearchActivity
- Category → Opens CategoryActivity
- Recipe Card → Opens RecipeActivity

### Step 5:
Recipe details are fetched and displayed.


