# 📝 Quora Clone – Post Sharing App

A simple full-stack web application inspired by **Quora**, where users can create, view, edit, and delete text-based posts. Built using **Node.js**, **Express.js**, and **EJS**, styled with modern CSS for a clean user experience.

---

## 🚀 Features

- ✍️ Create new posts with username and content  
- 📄 View all posts in a styled, readable layout  
- 🛠️ Edit post content inline  
- ❌ Delete posts with a single click  
- 🌐 RESTful routing with method override  
- 🎨 Beautiful dark-themed UI design

---

## ⚙️ Tech Stack

- **Backend**: Node.js, Express.js  
- **Frontend**: HTML5, CSS3, EJS templating  
- **Styling**: Custom CSS with dark theme  
- **Routing**: RESTful routes + method-override

---

## 📁 Folder Structure
. ├── public/ │ └── style.css ├── views/ │ ├── index.ejs │ ├── show.ejs │ ├── edit.ejs │ ├── new.ejs ├── app.js ├── package.json ├── README.md └── .gitignore



---

## 🛠️ Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/quora-post-app.git
   cd quora-post-app


✅ Routes Overview
Method | Route | Description
GET | /posts | View all posts
GET | /posts/new | Form to create a post
POST | /posts | Submit a new post
GET | /posts/:id | View a single post
GET | /posts/:id/edit | Form to edit a post
PATCH | /posts/:id | Update the post
DELETE | /posts/:id | Delete the post

post
🙌 Author
Made with ❤️ by NIKHIL GARKOTI


Install dependancies
npm install express
npm install ejs
npm install uuid
npm install method-override

To Run :
node app.js

Server runs on http://localhost:1000

This project is licensed under the MIT License.




