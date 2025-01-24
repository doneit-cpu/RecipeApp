# Recipe Finder App

A simple web-based recipe finder that allows users to search for meals and view detailed recipes using the **MealDB API**.

## Features

- Search for recipes by meal name.
- View meal details, including ingredients and instructions.
- Responsive UI with dynamically generated content.
- Error handling for failed API requests or empty search inputs.

## How It Works

1. **Search Functionality:**  
   - Users can enter a meal name and click the search button.
   - Results are fetched from the MealDB API and displayed dynamically.

2. **Recipe Display:**  
   - Each result shows the meal image, name, origin, and category.
   - Clicking the "View Recipe" button opens a popup with detailed instructions and ingredient lists.

3. **Popup Handling:**  
   - Clicking the close button hides the recipe details.

## Technologies Used

- HTML, CSS, JavaScript
- Fetch API for data retrieval
- MealDB API for recipe data

## Key Functions

- `fetchRecipes(query)`: Fetches meal data based on user input and displays it.
- `fetchIngredients(meal)`: Extracts and formats the list of ingredients.
- `openRecipePopup(meal)`: Displays detailed meal information in a popup.
- Event listeners for handling search input and closing the recipe popup.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/recipe-finder.git
   cd recipe-finder
