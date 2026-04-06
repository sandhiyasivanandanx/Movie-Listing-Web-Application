# Movie Listing Web Application

## 📌 Overview
 This project is a simple full-stack web application developed as part of a time-bound assignment. It displays a list of movies and allows users to view detailed information for each movie. The application is built using React for the frontend and Node.js with Express for the backend.

## 🚀 Features
 * Display a list of movies with key details (title, tagline, rating)
 * View detailed information for a selected movie
 * Backend APIs to fetch movie data
 * Responsive design for different screen sizes
 * Navigation between list and detail pages

## 🛠 Tech Stack
 * Frontend: React (Create React App)
 * Backend: Node.js, Express
 * Data Source: JSON file (`movies_metadata.json`)

## ⚙️ How It Works
 1. The backend server loads movie data from a JSON file.
 2. APIs are created to:
   * Fetch all movies
   * Fetch a single movie by ID
 3. The frontend calls these APIs to display:
   * A movie list page (initial view)
   * A movie detail page (on selection)
 4. Users can navigate between pages using the UI.

## 🔌 API Endpoints
 * `GET /api/movies` → Returns list of movies
 * `GET /api/movies/:id` → Returns details of a specific movie

## ▶️ How to Run

### 1. Install dependencies
```bash
npm install
```

### 2. Run in development mode
```bash
npm run development
```

### 3. Run in production mode
```bash
npm run production
```

## 📊 Dataset
 The application uses a local JSON dataset (`movies_metadata.json`) containing movie information such as title, tagline, rating, release date, and runtime.

## ⚠️ Notes
 * This project was developed as a **time-limited assignment (2 hours)**.
 * The implementation focuses on core functionality such as API creation and UI rendering.

## 📌 Future Improvements
 * Enhance UI/UX design and responsiveness
 * Add search and filtering functionality
 * Implement pagination for large datasets
 * Improve error handling and validation
 * Optimize performance for API responses
