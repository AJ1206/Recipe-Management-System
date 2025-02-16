# Recipe Management System

## Overview
The Recipe Management System is a web-based application designed to help users manage their recipes. Users can add, edit, delete, and search for recipes. The system allows for categorization of recipes, ingredient management, and provides an easy-to-use interface for managing personal or shared recipes.

## Features
- **User Authentication:** Secure login and registration system.
- **Recipe Management:** Add, edit, delete, and view recipes.
- **Categorization:** Organize recipes by categories (e.g., Breakfast, Lunch, Dinner).
- **Search Functionality:** Easily search for recipes by name, ingredients, or category.
- **Ingredient Management:** Keep track of ingredients needed for each recipe.
- **User Profiles:** Manage personal information and view user-specific recipes.
- **Responsive Design:** Works on both desktop and mobile devices.

## Technologies Used
- **Frontend:**
  - HTML5
  - CSS3
  - JavaScript
  - React.js

- **Backend:**
  - Node.js
  - Express.js

- **Database:**
  - MongoDB

- **Authentication:**
  - JWT (JSON Web Tokens)

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/AJ1206/Recipe-Management-System.git
   cd Recipe-Management-System
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the root directory and add the following variables:
   ```
   PORT=3000
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```

4. **Run the application:**
   ```bash
   npm start
   ```

5. **Open your browser:**
   Navigate to `http://localhost:3000` to view the application.

## Usage
1. **Register a new account or log in with existing credentials.**
2. **Navigate to the "Add Recipe" page to create a new recipe.**
3. **View and manage your recipes from the dashboard.**
4. **Use the search bar to find specific recipes by name, ingredients, or category.**
5. **Edit or delete recipes as needed from the recipe details page.**

## Contributing
Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch with your feature or bug fix.
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push the branch to your forked repository.
4. Open a pull request with a detailed description of your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

## Contact
For any questions or suggestions, feel free to open an issue or contact the project maintainer:
- GitHub: [AJ1206](https://github.com/AJ1206)
