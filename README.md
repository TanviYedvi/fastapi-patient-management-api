# 🏥 Patient Management API

A simple **Patient Management API** built using **FastAPI** as a practice project while learning FastAPI concepts such as CRUD operations, Pydantic models, data validation, path parameters, query parameters, computed fields, exception handling, and JSON file handling.

## 🚀 Features

* Create a new patient
* View all patients
* View a patient by ID
* Update patient details
* Delete a patient
* Sort patients by height, weight, or BMI
* Input validation using Pydantic
* Automatic BMI calculation
* Health verdict based on BMI
* Error handling using `HTTPException`
* JSON file-based data storage

## 🛠️ Technologies Used

* Python
* FastAPI
* Pydantic
* Uvicorn
* JSON

## 📌 API Endpoints

| Method | Endpoint                | Description            |
| ------ | ----------------------- | ---------------------- |
| GET    | `/`                     | API home page          |
| GET    | `/about`                | About the API          |
| GET    | `/view`                 | View all patients      |
| GET    | `/patient/{patient_id}` | View a patient by ID   |
| GET    | `/sort`                 | Sort patients          |
| POST   | `/create`               | Create a new patient   |
| PUT    | `/edit/{patient_id}`    | Update patient details |
| DELETE | `/delete/{patient_id}`  | Delete a patient       |

## ⚙️ Installation & Running

Install the required dependencies:

```bash
pip install fastapi uvicorn
```

Run the application:

```bash
uvicorn main:app --reload
```

The API will be available at:

```text
http://127.0.0.1:8000
```

## 📖 API Documentation

FastAPI provides interactive API documentation.

Open:

```text
http://127.0.0.1:8000/docs
```

You can test all the API endpoints directly from the Swagger UI.

## 👩‍💻 Author

**Tanvi Yedvi**

B.Tech Artificial Intelligence & Data Science Student.
