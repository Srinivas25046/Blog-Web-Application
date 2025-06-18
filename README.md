📝 Blog Web Application

This is a simple Blog Web Application built using Node.js, Express.js, and EJS. It allows users to create, view, edit, and delete blog posts. The posts are stored in memory (no database), and the site is styled to work well on both desktop and mobile devices.


🚀 FEATURES
    -> Create blog posts
    -> View all blog posts on the home page
    -> Edit existing posts
    -> Delete posts
    -> Fully responsive and user-friendly design
    -> Built with Node.js + Express.js + EJS
    -> No database used (data is lost on server restart)


🛠️ TECH STACK
    -> Node.js
    -> Express.js
    -> EJS
    -> HTML5 + CSS


📂 Project Structure
blog-app/
├── views/             # EJS templates
│   ├── index.ejs      # Home page
│   ├── new.ejs        # New post form
│   └── edit.ejs       # Edit post form
├── public/            # Static files
│   └── style.css      # CSS styles
├── app.js             # Main server file
├── package.json       # Node config file
└── README.md          # Project documentation


💻 HOW TO RUN
1. Download the Project 
    If you don't use Git:
    1. Download the ZIP file
    2. Extract it to a folder on your computer

    (OR)

    Clone the Repository

2. Install Node.js(if not installed previously)
    Download from https://nodejs.org
    Install it like any normal app
    To check if Node.js is installed, run:
    node -v
    npm -v

3. Install Project Dependencies
    In the terminal, go to project folder and run:
    
    npm install

    This installs all required packages (express, ejs, body-parser)

4. Start the App

    npm start

    (OR)

    navigate to the directory using the terminal

    node app.js

5. Open in the Browser
    Visit:

    http://localhost:3000


HOW TO USE THE APP

    -> Click "+ New Post" to create a blog post
    -> Posts show on the home page
    -> Use ✏️ Edit or 🗑️ Delete to manage posts