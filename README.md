# Malaysian Foods API

This is a simple Node.js Express API that provides information about Malaysian foods.

## Features

- Get a list of all Malaysian food recipes.
- Search recipes by name.
- Search recipes by origin.
- Search recipes by ingredient.
- Filter recipes by the first alphabet of the recipe name.

## API Endpoints

- `GET /api/recipes`  
  Returns all recipes.

- `GET /api/recipes/name/:name`  
  Returns recipes whose names include the specified string.

- `GET /api/recipes/origin/:origin`  
  Returns recipes from the specified origin.

- `GET /api/recipes/ingredient/:ingredient`  
  Returns recipes that include the specified ingredient.

- `GET /api/recipes/filter/:alphabet`  
  Returns recipes whose names start with the specified alphabet.

## Data Structure

Each recipe object contains the following fields:

- `id`: Unique identifier.
- `name`: Name of the dish.
- `description`: Description of the dish.
- `origin`: Country or region of origin.
- `cookTimeMinutes`: Estimated cooking time in minutes.
- `caloriesPerServing`: Estimated calories per serving.
- `ingredients`: List of ingredients.
- `steps`: List of cooking steps.

## Running Locally

1. Install dependencies:

   ```
   npm install
   ```

2. Start the server:

   ```
   npm start
   ```

3. The API will be available at `http://localhost:3001`.
