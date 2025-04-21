# GO_DB
Go project where I practiced database integration using native Go libraries. I used lumber for logging and wrote clean modular code that’s easy to maintain
# 🐹 Golang Database Project

A clean and modular Go project demonstrating how to interact with a SQL database using best practices like proper error handling, structured logging, and organized code structure.

---

## 🚀 Project Overview

This project showcases how to build a lightweight Go application that connects to a SQL database, performs core operations like inserting and retrieving records, and logs events using a structured logger. It's designed to be scalable, readable, and interview-ready.

---

## 🛠️ Tech Stack

- **Language:** Go `v1.24.2`
- **Database:** (Specify here, e.g., PostgreSQL / SQLite / MySQL)
- **Packages Used:**
  - [`database/sql`](https://pkg.go.dev/database/sql): Core package to interface with SQL databases.
  - [`github.com/jcelliott/lumber`](https://github.com/jcelliott/lumber): Lightweight and color-coded logger for readable logs.
  - (Add DB driver here, e.g., `github.com/mattn/go-sqlite3` or `github.com/lib/pq`)

---

## 📁 Project Structure

golang-database/ │ ├── main.go # Application entry point ├── go.mod # Go module definition ├── database/ │ └── db.go # DB connection and query logic ├── models/ │ └── user.go # Data models (e.g., User struct) ├── utils/ │ └── logger.go # Logging helper using lumber


---

## 🔧 Features

- ✅ Connects to a SQL database
- ✅ Inserts and retrieves data
- ✅ Structured and color-coded logging
- ✅ Proper error handling
- ✅ Modular and clean architecture

---

## 💡 How to Run

1. **Clone the repo:**
   ```bash
   git clone https://github.com/yourusername/golang-database.git
   cd golang-database
Install dependencies:
  go mod tidy
Run the application:
  go run main.go

📈 Future Improvements

    Add REST APIs using net/http or Gin

    Add .env configuration support

    Add unit testing with Go's testing package

    Dockerize the application


