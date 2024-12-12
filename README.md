# Angular Housing Project

This project is a housing website developed using Angular, providing users with a platform to browse, search, and explore housing listings. The backend is a simple JSON web server that reads and writes data from a `db.json` file.

## Features

- **Browse Listings**: View a comprehensive list of available housing options.
- **Search Functionality**: Filter listings based on user-defined criteria.
- **Responsive Design**: Optimized for various devices to ensure a seamless user experience.

## Technologies Used

### Frontend

- **Angular**: Framework for building a dynamic, component-driven user interface.
- **HTML/CSS**: For structuring and styling the user interface.
- **TypeScript**: Used for type-safe, modern JavaScript development.

### Backend

- **JSON Server**: A lightweight, mock REST API that reads from `db.json` to provide listing data.

### Tooling

- **Node.js & NPM**: For managing dependencies and running development scripts.
- **Angular CLI**: For development commands like `ng serve`, `ng build`, and `ng test`.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/react-picasso/angular-housing-project.git   ```

2. **Navigate to the project directory:**
   ```bash
   cd angular-housing-project   ```

3. **Install the dependencies:**
   ```bash
   npm install   ```

4. **Install Angular CLI globally (if not already installed):**
   ```bash
   npm install -g @angular/cli   ```

5. **Start the development server:**
   ```bash
   ng serve   ```

6. **Start the backend server (JSON server):**
   ```bash
   npx json-server --watch db.json   ```

7. **Open the application:**

   Navigate to `http://localhost:4200/` in your web browser for the Angular app.

   The backend server for the JSON data will be running at `http://localhost:3000/`.

## Usage

Once the application is running:

- **View Listings**: Browse through the available housing options displayed on the homepage.
- **Search**: Use the search bar to filter listings based on your preferences.
- **Details**: Click on a listing to view more detailed information about the property.
