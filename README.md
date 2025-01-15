# CapitalQuest

## Overview
The **CapitalQuest Quiz** is a simple yet engaging quiz application powered by a **Node.js** backend and a **Postgres** database. This project demonstrates how to use a database in a Node.js environment for real-time applications, with proper configuration, connection, and query execution.

In this quiz:
- Users are prompted with a country name and must input its capital.
- Responses are validated against data stored in the **Postgres** database.
- The score increases for every correct answer, but the quiz ends as soon as a wrong answer is submitted.

This project highlights key backend concepts, including database integration, middleware usage, and best practices for connection handling.

---

## Key Features

- **Dynamic Quiz Application**: Powered by Postgres data, checks answers in real-time.
- **Normalized Input Handling**: Handles casing and trims unnecessary characters in user input.
- **Database Queries**: Demonstrates SQL operations using the `pg` package.
- **Backend Configuration**: Explains and uses Postgres configuration details effectively.
- **Session Management**: Ensures proper connection closure after operations.

---

## Project Structure

- **Backend**: Node.js, Express, and the `pg` library for database integration.
- **Database**: Postgres with table:
  - `flags`: Country names and their flags.
- **Frontend**: Basic EJS templates, CSS for styling, and static files for assets.

---

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/world-capitals-quiz.git
   cd world-capitals-quiz
2. **Install dependencies**
   ```bash
   npm install
3. **Database Configuration**
   Ensure you have Postgres installed and running locally.
   Create a database named world.
   Populate the database with flags and capitals tables (SQL files provided in the repository).

4. **nodemon solution.js
   ```bash
   nodemon solution.js

**The quiz page should look like this**:

![image](https://github.com/user-attachments/assets/0bbe0bcc-da2c-4289-998e-74f72cfc264c)

**and when you enter the wrong campital, it will look like this**:

![image](https://github.com/user-attachments/assets/5f97d6d2-023d-4abf-a016-16c7a2a02b6e)

