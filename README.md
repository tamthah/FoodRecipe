# Food Recipe App

## Overview
The **Food Recipe App** is a simple web application that allows users to search for recipes based on ingredients using the [TheMealDB API](https://www.themealdb.com/api.php). It provides meal details, including instructions and a video tutorial.

## Features
- Search for recipes by ingredient.
- Display a list of meals with images and names.
- View detailed meal instructions and a YouTube tutorial.
- Responsive and user-friendly UI.

## Technologies Used
- **HTML** - Structuring the web page.
- **CSS** - Styling and layout.
- **JavaScript (Fetch API)** - Fetching live data from TheMealDB API.

## Setup & Usage
### 1. Clone the Repository
```sh
git clone https://github.com/yourusername/food-recipe-app.git
cd food-recipe-app
```

### 2. Open the `index.html` File
Simply open `index.html` in a browser, and the app will fetch recipe data.

### 3. Ensure Internet Access
Since the app relies on fetching data from an external API, make sure you have an active internet connection.

## API Information
- **Endpoint Used:**
  ```sh
  https://www.themealdb.com/api/json/v1/1/filter.php?i=ingredient
  ```
- **Meal Details Endpoint:**
  ```sh
  https://www.themealdb.com/api/json/v1/1/lookup.php?i=mealId
  ```
- **Data Provided:**
  - List of meals based on ingredient.
  - Detailed meal instructions and YouTube tutorial.

## Screenshot
![Food Recipe App](images/demo.png) *(Add an actual screenshot here)*

## Future Improvements
- Add more filtering options (cuisine, meal type, etc.).
- Improve UI with additional animations.
- Implement saved recipes feature.

## License
This project is licensed under the **MIT License**.

## Author
Developed by **Thi Nguyen**.