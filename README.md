# Library Management System (Java)

A simple **Library Management System** built in **Java** using layered architecture (**DAO → Service → Main**).
This project demonstrates the use of **OOP concepts, custom exceptions, and modular design** to manage books, users, and librarians in a library.

### 🚀 Features

* Add, update, search, and remove books
* Manage users and librarians
* Maintain borrowing records
* Custom exceptions (`BookNotFound`, `UserNotFoundException`)
* Layered architecture:

  * **DAO Layer** → Handles data storage and retrieval
  * **Service Layer** → Business logic (validations, rules)
  * **Entity Layer** → Represents real-world objects (`Book`, `User`, etc.)
  * **Main Layer** → Entry point (`LibraryManagementSystemApp`)

### 🏗️ Project Structure

```
src/
 └── library_management_system
      ├── entity/        # Book, User, Librarian, Record
      ├── exception/     # Custom exceptions
      ├── dao/           # Data Access Layer
      ├── service/       # Business Logic Layer
      ├── main/          # App entry point & tests
      └── util/          # Helpers & configs
```

### 🛠️ Technologies Used

* Java 17+
* Collections Framework
* Exception Handling
* Modular Programming (module-info.java)

How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/library-management-system.git
   cd library-management-system
   ```
2. Compile the project

   ```bash
   javac -d bin src/**/*.java
   ```
3. Run the application

   ```bash
   java -cp bin library_management_system.main.LibraryManagementSystemApp
   ``
