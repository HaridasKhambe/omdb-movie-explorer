# 🎬 OMDB Movie Explorer – Movie Search & Discovery Platform

## 📘 Overview
**OMDB Movie Explorer** is a full-stack web application that enables users to search and explore movies and series using the OMDB API. The application features a clean, responsive interface with real-time search, detailed movie information, and intelligent caching for optimal performance.

> **🚀 Built with Modern Technologies!**  
> This application demonstrates best practices in REST API development, caching strategies, and responsive frontend design.

---

### 🎯 Key Features
- **Movie Search**: Find movies and series by title.
- **Detailed View**: Get comprehensive details for any movie, including plot, actors, ratings, and more.
- **Responsive UI**: A clean and modern user interface that works on any device.
- **Performance Optimized**: Built-in caching for faster subsequent API responses.

---

### ⚙️ Technology Stack

### 🖥️ Backend
| Technology | Purpose |
|------------|---------|
| **Java 21** | Programming language |
| **Spring Boot 3.2.0** | REST API framework |
| **Spring Web** | RESTful web services |
| **Spring Cache** | Caching abstraction layer |
| **Caffeine Cache** | High-performance in-memory caching |
| **Lombok** | Reduce boilerplate code |
| **Maven** | Build & dependency management |

### 💻 Frontend
| Technology | Purpose |
|------------|---------|
| **React 18+ (Vite)** | Fast modern frontend framework |
| **React Router v6** | Client-side routing |
| **Axios** | HTTP client for API calls |
| **Tailwind CSS v4** | Utility-first styling |
| **Lucide React** | Modern icon library |
| **React Hot Toast** | Toast notification system |

---

## 🏗️ Project Architecture

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

📧 **Email:** [haridaskhambe2003@gmail.com](mailto:haridaskhambe2003@gmail.com)  
💼 **LinkedIn:** [Haridas Khambe](https://www.linkedin.com/in/haridas-khambe-aa650926b)  
🌐 **Portfolio:** [View Portfolio](https://haridaskhambe.github.io/react-personal-portfolio/)

⭐ If you find this project helpful or inspiring, consider giving it a star on GitHub!