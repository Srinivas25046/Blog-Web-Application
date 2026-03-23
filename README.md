# 📝 Blog Web Application

A simple and clean **Blog Web Application** built using **Node.js,
Express.js, and EJS**.\
This app allows users to create, view, edit, and delete blog posts with
a responsive UI.

> ⚠️ Note: Data is stored in memory, so all posts are lost when the
> server restarts.

------------------------------------------------------------------------

## 🚀 Features

-   ✍️ Create blog posts\
-   📖 View all posts on the home page\
-   🛠️ Edit existing posts\
-   🗑️ Delete posts\
-   📱 Fully responsive design (mobile + desktop)\
-   ⚡ Lightweight (no database required)

------------------------------------------------------------------------

## 🛠️ Tech Stack

-   **Backend:** Node.js, Express.js\
-   **Templating Engine:** EJS\
-   **Frontend:** HTML5, CSS3

------------------------------------------------------------------------

## 📂 Project Structure

``` bash
blog-app/
│
├── views/              # EJS templates
│   ├── index.ejs       # Home page
│   ├── new.ejs         # New post form
│   └── edit.ejs        # Edit post form
│
├── public/             # Static files
│   └── style.css       # Stylesheet
│
├── app.js              # Main server file
├── package.json        # Project configuration
└── README.md           # Documentation
```

------------------------------------------------------------------------

## 💻 Getting Started

Follow these steps to run the project locally:

### 1️⃣ Download the Project

**Option 1: Download ZIP** - Download the repository as a ZIP file\
- Extract it to your desired location

**Option 2: Clone Repository**

``` bash
git clone <your-repo-link>
cd blog-app
```

------------------------------------------------------------------------

### 2️⃣ Install Node.js

Download and install from: https://nodejs.org

Verify installation:

``` bash
node -v
npm -v
```

------------------------------------------------------------------------

### 3️⃣ Install Dependencies

Navigate to the project folder and run:

``` bash
npm install
```

This installs required packages like: - express\
- ejs\
- body-parser

------------------------------------------------------------------------

### 4️⃣ Start the Application

``` bash
npm start
```

OR

``` bash
node app.js
```

------------------------------------------------------------------------

### 5️⃣ Open in Browser

Visit:

http://localhost:3000

------------------------------------------------------------------------

## 🧑‍💻 How to Use

-   ➕ Click **"New Post"** to create a blog\
-   🏠 All posts appear on the home page\
-   ✏️ Use **Edit** to update posts\
-   🗑️ Use **Delete** to remove posts

------------------------------------------------------------------------

## ⚠️ Limitations

-   ❌ No database (data is not persistent)\
-   🔄 All posts are lost when the server restarts

------------------------------------------------------------------------

## 📌 Future Improvements

-   ✅ Add database (MongoDB / PostgreSQL)\
-   🔐 User authentication\
-   🖼️ Image upload support\
-   🌐 Deploy online (Render / Vercel)

------------------------------------------------------------------------

## ⭐ Contributing

Feel free to fork this repo and improve it! Contributions are always
welcome 😊

------------------------------------------------------------------------

## 📄 License

This project is open-source and available under the **MIT License**.
