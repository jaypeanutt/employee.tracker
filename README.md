# employee.tracker
  <div align="center">
  <h1 align="center">SQL EMPLOYEE TRACKER</h1>
  <h3>Codebase for the SQL EMPLOYEE TRACKER platform</h3>
  <h3>◦ Developed with the software and tools below.</h3>
  <p align="center"><img src="https://img.shields.io/badge/-Node.js-004E89?logo=Node.js&style=social" alt='Node.js\' />
<img src="https://via.placeholder.com/1/0000/00000000" alt="spacer" /><img src="https://img.shields.io/badge/-MySQL-004E89?logo=MySQL&style=social" alt='MySQL\' />
<img src="https://via.placeholder.com/1/0000/00000000" alt="spacer" /><img src="https://img.shields.io/badge/-Inquirer.js-004E89?logo=Inquirer.js&style=social" alt='Inquirer.js\' />
<img src="https://via.placeholder.com/1/0000/00000000" alt="spacer" /><img src="https://img.shields.io/badge/-Express.js-004E89?logo=Express.js&style=social" alt='Express.js\' />
<img src="https://via.placeholder.com/1/0000/00000000" alt="spacer" /><img src="https://img.shields.io/badge/-dotenv-004E89?logo=dotenv&style=social" alt='dotenv\' />
<img src="https://via.placeholder.com/1/0000/00000000" alt="spacer" /><img src="https://img.shields.io/badge/-figlet-004E89?logo=figlet&style=social" alt='figlet"' />
<img src="https://via.placeholder.com/1/0000/00000000" alt="spacer" />
  </p>
  </div>
  
  ---
  ## 📚 Table of Contents
  - [📚 Table of Contents](#-table-of-contents)
  - [🔍 Description](#-description)
  - [🌟 Features](#-features)
  - [📁 Repository Structure](#-repository-structure)
  - [💻 Demo Video](#-demo-video)
  - [💻 Code Summary](#-code-summary)
  - [🚀 Getting Started](#-getting-started)
  
  ---
  
  
  ## 🔍 Description

 This is a Node.js project with a MySQL database, consisting of a RESTful API for managing departments, employees, and roles in a company. The project includes a `db` directory with schema and seed files, as well as a `lib` directory with utility functions for connecting to the database and performing queries. The `models` directory contains JavaScript classes for each of the three entities, and the `index.js` file is the entry point for the application.

---

## 🌟 Features

 Node.js, MySQL, RESTful API, departments, employees, roles, company, schema, seed, utility functions, connection, queries, models, JavaScript classes

---
## Demo Video

- [demo video](https://drive.google.com/file/d/1NZREynC0o_B3kOqGFF2_M615aeA3yYMs/view?usp=sharing)

---
## 🚀 Getting Started

 To get started with this project, follow these steps:<br>
1. Install the necessary dependencies by running `npm install` in your terminal.
2. Create a `.env` file in the root directory of the project and add your MySQL username and password to it, like this:
```
DB_USER=your_username
DB_PASSWORD=your_password
```
3. Start the application by running `node index.js` in your terminal.
4. Use the command-line interface to interact with the application and manage the employee database.

Note: Before you start, make sure you have a MySQL server running on your local machine and that you have created the necessary database and tables using the schema and seed files in the `db` directory.