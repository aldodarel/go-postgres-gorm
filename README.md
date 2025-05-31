[![Go Version](https://img.shields.io/badge/Go-1.16%2B-blue?style=for-the-badge&logo=go&logoColor=white)](https://golang.org/dl/)
[![Fiber Version](https://img.shields.io/badge/Fiber-v2.30.0-00A9E0?style=for-the-badge&logo=fiber&logoColor=white)](https://gofiber.io/)
[![GORM Version](https://img.shields.io/badge/GORM-v1.23.3-A849BF?style=for-the-badge&logo=gorm&logoColor=white)](https://gorm.io/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-~14-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

# 📖 Go Fiber GORM PostgreSQL: A RESTful Book API Example 🚀

This project serves as a practical example of building a RESTful API using **Golang** 🐹. It implements a book management system with full **CRUD** (Create, Read, Update, Delete) capabilities.

The API is built using the following awesome technologies:
* **Go (Golang):** The core programming language. Check it out [here](https://go.dev/)!
* **Fiber:** A fast and expressive web framework inspired by Express.js ⚡. Learn more at [gofiber.io](https://gofiber.io/).
* **GORM:** A developer-friendly ORM library for Golang, used here to interact with PostgreSQL 🐘. Dive deeper at [gorm.io](https://gorm.io/).
* **PostgreSQL:** A powerful, open-source object-relational database system 💾. Visit [postgresql.org](https://www.postgresql.org/).
* **godotenv:** For loading environment variables from a `.env` file, simplifying configuration management ⚙️.

**✨ Functionalities:**
* **POST `/api/create_books`**: ➕ Add a new book.
* **GET `/api/books`**: 📚 Retrieve all books.
* **GET `/api/get_books/:id`**: 🔎 Retrieve a specific book by its ID.
* **PUT `/api/update_book/:id`**: 🔄 Update an existing book's details.
* **DELETE `/api/delete_book/:id`**: 🗑️ Remove a book by its ID.
