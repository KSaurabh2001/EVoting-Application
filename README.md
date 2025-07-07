# 🗳️ E-Voting System – Backend API with Spring Boot

A secure backend-only voting system built using **Java**, **Spring Boot**, and **MySQL**, designed to simulate electronic voting workflows with vote integrity and user validation. This API supports user registration, candidate management, and one-vote-per-user submission logic.

---

## 🚀 Features

- 🧑‍💼 Voter registration and login
- 🗳️ One-time vote submission per user
- 🧾 Candidate registration and listing
- 📊 View voting results (live tally)
- 🔐 Input validation & security handling
- 🧠 Domain-focused backend architecture

---

## 🧰 Tech Stack

| Layer        | Tech Stack                            |
|--------------|----------------------------------------|
| Language     | Java                                   |
| Framework    | Spring Boot, Spring MVC, Spring Data JPA |
| Database     | MySQL                                  |
| Tools        | Maven, Postman, Git, GitHub            |

---

## 🗂️ Project Structure

evoting/
├── src/
│ ├── main/
│ │ ├── java/com/evoting/... (controllers, services, models)
│ │ └── resources/application.properties
└── pom.xml


---

## 📑 API Endpoints Overview

| Method | Endpoint               | Description                  |
|--------|------------------------|------------------------------|
| POST   | `/api/voters`          | Register a new voter         |
| POST   | `/api/candidates`      | Add a new candidate          |
| GET    | `/api/candidates`      | List all candidates          |
| POST   | `/api/vote`            | Submit a vote (once/user)    |
| GET    | `/api/results`         | Get current vote counts      |

---

## 🧠 Learning Highlights

- Designed and implemented RESTful APIs from scratch
- Practiced layered architecture: `Controller → Service → Repository`
- Ensured one-user-one-vote constraint using backend validation
- Strengthened skills in Spring Boot, JPA, and relational data handling

---

## 🧪 How to Run Locally

1. **Clone the repository**

```bash
git clone https://github.com/KSaurabh2001/E-Voting-System.git
cd E-Voting-System
