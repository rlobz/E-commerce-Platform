# E-commerce-Platform

This project involves building the backend for an e-commerce platform. It's designed to provide an API for performing CRUD operations on a MySQL database using Sequelize. This backend system can manage categories, products, and tags for an e-commerce retail platform, demonstrating the key functionalities of an internet retail company's backend system.

![Gif demo of E-commerce-Platform](./assets/E-commerce-Platform.gif)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technology](#technology)
- [Demo Video](#demo-video)
- [Contributing](#contributing)
- [Credits](#credits)

## Installation

To install this application, follow these steps:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/rlobz/E-commerce-Platform.git
```
2. Navigate to the project directory:

```bash
cd e-commerce-platform
```
3. Install the required npm packages:

```bash
npm install
```
4. Set up your MySQL database and configure the `.env` file with your MySQL username, password, and database name.

5. Run `npm run seed` to seed data to your database.

6. Start the server using `npm start`.

# Usage

This backend system is designed to interact with a front-end e-commerce platform. It provides API routes for:

- Viewing, adding, updating, and deleting categories.
- Viewing, adding, updating, and deleting products.
- Viewing, adding, updating, and deleting tags.

## Features

- CRUD operations for managing categories, products, and tags.
- Association and relationship management between different data models.
- Secure storage of sensitive information with environment variables.

## Technology

- Node.js
- Express.js
- MySQL and Sequelize ORM
- Dotenv for environment variable management

## Demo Video

A walkthrough video demonstrating the functionality of the application can be found [here](https://drive.google.com/file/d/1r2T746OMnLOIgdTaHWuJxbmhTlZX-5fQ/view).

## Contributing

Contributions to this project are welcome. Please ensure that your code adheres to the existing style and conventions.

## Credits

**Rafal Lobzowski**
- Github: [@rlobz](https://github.com/rlobz)