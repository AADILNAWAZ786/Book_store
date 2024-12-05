# Bookstore API 📚

A RESTful API built using Django REST Framework (DRF) for managing a bookstore. The API supports user authentication, book management, and review functionality.

---

## Features 🚀
- **User Authentication**: 
  - Registration and Login with JWT.
  - User profiles with bio and profile picture.
  
- **Book Management**:
  - Add, update, delete, and view books.
  - Filter books by genre or author.
  
- **Review System**:
  - Authenticated users can rate and review books (1-5 stars).
  - View all reviews for a specific book.

- **Pagination & Search**:
  - Paginated book listing.
  - Search books by title or author.

---

## Technologies Used 🛠️
- **Backend**: Django & Django REST Framework
- **Database**: MySQL
- **Authentication**: JWT (JSON Web Token)
- **Deployment**: Gunicorn and Nginx (for production-ready setup)

---

## Installation 🧰

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AADILNAWAZ786/Book_store.git
   cd Book_store
