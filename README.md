# Tech Blog

[![Heroku App](https://img.shields.io/badge/heroku-deployed-6567a5?logo=heroku)](https://your-heroku-app-url.herokuapp.com/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## Description

The Tech Blog is a platform where developers can publish their blog posts and interact with other developers by commenting on their posts. It is built using Express.js, Handlebars, MySQL2, Sequelize, dotenv, bcrypt, and express-session.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Questions](#questions)

## Installation

To install and run the Tech Blog locally, follow these steps:

1. Clone the repository:

```bash
git clone *****
cd tech-blog
```
### Install dependencies
 ```bash
npm install
```
###  Set up the database:

* Create a .env file in the root directory and add your MySQL credentials:
```bash
DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
```

### Run the database schema and seed files:

```bash
npm run db:setup
```

## Usage

To start the Tech Blog application, run the following command:

```bash
npm start
```

Visit http://localhost:3001 in your web browser to access the application.

## Deployment

The Tech Blog is deployed on Heroku. You can access it at https://tech-blog-name-2323-583741032784.herokuapp.com/

## Technologies Used
* Node.js
* Express.js
* Handlebars
* MySQL2
* Sequelize
* dotenv
* bcrypt
* express-session
* Javascript
* HTML
* CSS

## ScreenShots

![](./Screenshot%202024-03-04%20at%202.15.43%20PM%20(2).png)
![](./Screenshot%202024-03-04%20at%202.16.21%20PM%20(2).png)
![](./Screenshot%202024-03-04%20at%202.16.52%20PM%20(2).png)