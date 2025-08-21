Online Banking Application

A simple Spring Boot REST API that simulates online banking with file-based persistence. 
It supports account creation, listing, balance checks, and fund transfers. 
An optional HTML dashboard can be used to interact with the API visually.

Features

1) Create new accounts with initial balance

2) Retrieve account details by ID

3) List all accounts

4) Transfer funds between accounts

5) Data persistence via a local text file (accounts.txt)

6) Optional HTML dashboard for a simple UI

   Tech Stack

>Java 17+

>Spring Boot (Web starter)

>File-based persistence (no database required)

| Method | Endpoint         | Description                     |
| ------ | ---------------- | ------------------------------- |
| POST   | `/accounts`      | Create a new account            |
| GET    | `/accounts`      | List all accounts               |
| GET    | `/accounts/{id}` | Get account by ID               |
| POST   | `/transfer`      | Transfer funds between accounts |
