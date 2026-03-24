# MovieExplorer

- Project Overview
- Tech Stack
- API Documentation
- Notes


## 📝 Project Overview
MovieExplorer is a full-stack web application for exploring movies. Users can search for movies by genre, release year, keywords, or actors, manage a list of favorite movies, and view popular search queries.

The backend is built with Flask and is responsible for routing and API endpoint implementation. Database interactions are handled through custom service functions using raw MySQL queries, enabling direct and fine-grained control over data operations.

The frontend is developed with React and provides a simple, responsive user interface designed for clarity and ease of use.

The application also includes basic user authentication and functionality for managing personal favorite movies.

## 🛠 Tech Stack

**_Current:_**

- 🐍 Python – backend logic and database functions  
- ⚡ Flask – API development and request handling  
- 🐬 MySQL – relational database accessed via custom SQL queries
- ⚛️ React – frontend user interface
- 🌐 HTML & CSS – basic styling and layout

## 📄 API Documentation
**_Endpoints examples:_**

Search Movies: GET /api/films

Add to Favorites: POST /api/favorites_list/add?user_id=<user_id>&film_id=<film_id>

Remove from Favorites: DELETE /api/favorites/delete?user_id=<user_id>&film_id=<film_id>

Popular Searches: GET /api/top_queries

## 📄 Notes
This project is my first full-stack application developed in Python. Flask was used to build the backend, including routing and server-side logic. Database operations are implemented without an ORM, using a custom service layer, which helped me develop a deeper understanding of working directly with SQL and data management.

The project includes a logging system as well as a basic email notification mechanism for error tracking and handling.

The frontend is intentionally minimalistic and focused on learning the fundamentals of client-server interaction. Special attention was given to manual API testing, both using tools such as Postman and directly through the browser.

## 🚀 Future Improvements
1. Backend:
    - Refactor backend architecture using Flask or FastAPI
    - Improve code structure and scalability
    - Expand application functionality

2. Frontend:
    - responsive layout
    - component-based architecture
    - improved code organization
