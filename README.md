# 🎬 OMDB Movie Explorer

A full-stack web application built to search, discover, and explore movies using the OMDb API.

---

### 🎯 Key Features
- **Movie Search**: Find movies and series by title.
- **Detailed View**: Get comprehensive details for any movie, including plot, actors, ratings, and more.
- **Responsive UI**: A clean and modern user interface that works on any device.
- **Performance Optimized**: Built-in caching for faster subsequent API responses.

---

### ⚙️ Technology Stack

**🖥️ Backend**

| Technology | Purpose |
| :--- | :--- |
| **Spring Boot 3.x** | REST API Framework |
| **Spring MVC** | Web Architecture |
| **Spring Cache** | Caching Abstraction |
| **Caffeine**| High-Performance Cache |
| **Java 21** | Core Language |
| **Maven** | Build & Dependency Management|

**💻 Frontend**

| Technology | Purpose |
| :--- | :--- |
| **React 19 (Vite)** | Modern Frontend Library |
| **React Router v7** | Routing & Navigation |
| **Axios** | API Communication |
| **Tailwind CSS** | Responsive Styling |
| **Lucide-React** | Icon Pack |

---

### 🏗️ Project Architecture

The project follows a classic client-server model:

-   **`ome-frontend`**: A **React** single-page application (SPA) that provides a dynamic and responsive user interface. It handles user interactions and communicates with the backend via RESTful API calls.
-   **`ome-backend`**: A **Java Spring Boot** application that serves the REST API. It handles business logic, communicates with the external OMDb API, and manages the server-side cache.

---

### 🧮 API Endpoints

| Function | Method | Endpoint |
| :--- | :--- | :--- |
| Search Movies | `GET` | `/api/movies/search?title={title}` |
| Get Movie Details| `GET` | `/api/movies/{imdbId}` |

---

### 🖼️ Screenshots

| Page / Feature | Output |
| :--- | :--- |
| Home Page & Search | *(Image of the main search page)* |
| Search Results | *(Image displaying a grid of movie cards)* |
| Movie Detail Page | *(Image showing the detailed view of a single movie)* |
| Responsive Design | *(Image showing the app on a mobile device)* |

---

### 🎯 Key Implementation Highlights
- **RESTful API**: A well-structured backend API built with Spring Boot.
- **DTOs**: Use of Data Transfer Objects (`MovieSearchResponse`, `MovieDetailResponse`) for clean API contracts.
- **Global Exception Handling**: Centralized error management for robust API responses.
- **Component-Based UI**: A modular frontend built with reusable React components.
- **Environment-Based API Configuration**: Securely manages API keys and settings.

---

### 💡 Bonus Features Implemented
- **In-Memory Caching**: Implemented using Spring Cache and Caffeine to reduce redundant calls to the OMDb API, improving response time and reducing API usage.

---

### 👨‍💻 Developed By
Haridas Khambe

📧 haridaskhambe2003@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/haridas-khambe-aa650926b)
🌐 Portfolio

⭐ If you find this project helpful or inspiring, consider giving it a star on GitHub!