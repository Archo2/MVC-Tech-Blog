# MVC Tech Blog

A CMS-style blog, similar to WordPress, where developers can publish posts and comment on each other's posts. Built with the Model-View-Controller pattern.

> The original Heroku deployment is no longer available because Heroku ended its free tier. Follow **Getting Started** to run it locally.

## Features

- Sign up, log in and log out, with passwords hashed using bcrypt
- Sessions stored in the database, so you stay logged in
- Home page lists all posts; click one to read it and its comments
- Logged-in users can comment on any post
- Dashboard to create, edit and delete your own posts

## Built With

Node.js · Express.js · Handlebars.js · Sequelize · MySQL · bcrypt · express-session · dotenv

## Getting Started

**Prerequisites:** Node.js and MySQL

```bash
git clone https://github.com/Archils/MVC-Tech-Blog.git
cd MVC-Tech-Blog
npm install
```

1. Create a `.env` file in the project root:
   ```
   DB_NAME=tech_blog
   DB_USER=your_mysql_user
   DB_PASSWORD=your_mysql_password
   ```
2. Create the database and start the server:
   ```bash
   mysql -u root -p < db/schema.sql
   npm start
   ```
3. Open http://localhost:3001.

## Screenshots

![Screenshot](mvc-demo-01.gif)

## Author

**Archils Oburu**
- GitHub: [@Archils](https://github.com/Archils)
- Email: oburuarchils@gmail.com
