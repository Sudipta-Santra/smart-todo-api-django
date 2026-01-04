# Smart ToDo API

A secure and scalable RESTful backend API built using **Django REST Framework** and **PostgreSQL**.  
The application allows users to manage personal tasks with **JWT-based authentication**.

---

## 🚀 Features
- User Registration & Login
- JWT Authentication
- Create, Read, Update, Delete (CRUD) Tasks
- User-specific task access
- PostgreSQL database integration
- RESTful API architecture
- Postman collection for API testing

---

## 🛠 Tech Stack
- **Backend:** Django, Django REST Framework
- **Authentication:** JWT (JSON Web Token)
- **Database:** PostgreSQL
- **API Testing:** Postman

---

## 📂 Project Structure
    smart-todo-api-django/
      │
      ├── manage.py
      ├── requirements.txt
      ├── accounts/
      ├── tasks/
      ├── Smart_ToDo_API.postman_collection.json
      └── README.md

      
---

## 🔐 Authentication
This project uses **JWT (JSON Web Token)** for secure, stateless authentication.


Authorization: Bearer <JWT_ACCESS_TOKEN>


---

## 🔁 API Endpoints

### Authentication
| Method | Endpoint |
|------|---------|
| POST | /api/auth/register/ |
| POST | /api/auth/login/ |
| POST | /api/auth/refresh/ |

### Tasks (Authenticated)
| Method | Endpoint |
|------|---------|
| POST | /api/tasks/ |
| GET | /api/tasks/ |
| PUT | /api/tasks/{id}/ |
| DELETE | /api/tasks/{id}/ |

---

## Security

- Password hashing using Django authentication
- JWT-based secure access
- User-level data isolation
- Foreign key constraints for data integrity

# Conclusion

The Smart ToDo API successfully demonstrates the design and implementation of a secure, scalable, and well-structured RESTful backend system using Django REST Framework and PostgreSQL. The project applies industry-standard practices such as JWT-based authentication, user-level data isolation, and RESTful CRUD operations, ensuring both security and maintainability.

By leveraging Django’s built-in authentication system and ORM, the application achieves reliable user management and seamless database integration. The inclusion of a Postman collection enables easy API testing and reproducibility, making the project suitable for real-world usage, academic assessment, and technical interviews.

Overall, this project reflects a strong understanding of backend architecture, API development, authentication, and database design, and serves as a solid foundation for building more advanced backend systems or production-ready applications.
