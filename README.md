# 📝 BlogEase Dashboard

A simple, beginner-friendly blog post dashboard built with HTML, CSS, and JavaScript. Users can register, login, upload a profile picture, create posts with images, and like their own posts. All data is saved locally using `localStorage`.

---

## 📸 Features

- 👤 Register & Login system (stored in `localStorage`)
- 📷 Profile Picture Upload & Save
- 📝 Create blog posts (Title, Description, Image)
- ❤️ Like posts (toggle between `Like` and `Liked`)
- 🧠 Posts and likes persist on refresh (for the logged-in user only)
- 🔐 Logout functionality

---

## 📁 Folder Structure

/blogease-dashboard
├── index.html # Optional entry point
├── /pages
│ ├── register.html # User registration page
│ ├── login.html # User login page
│ ├── dashboard.html # Main blog dashboard
├── /css
│ ├── style.css # Global styles (optional)
│ ├── dashboard.css # Dashboard-specific styles
├── /js
│ ├── main.js # Handles login/register logic
│ ├── dashboard.js # Dashboard script (posts, likes, profile pic)
├── README.md



---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/EzekielBliss/blogease-dashboard.git
cd blogease-dashboard

No server needed. Just open the HTML files directly:

pages/register.html — To register

pages/login.html — To login

pages/dashboard.html — Main dashboard after login


  ## 💡 How It Works
Registration/Login:

Stores user info in localStorage

Validates login against saved credentials

Dashboard:

User’s name and profile picture are displayed

Posts created are stored per user (username_Posts)

Posts can be liked once; liked state is stored in localStorage

## 🧪 Technologies Used
HTML5

CSS3

JavaScript (Vanilla)

LocalStorage

## 🔐 Limitations
Not connected to a backend or real authentication

Only the current user can see their posts

Not secure for production use

## 📌 Future Improvements
Add user authentication using Firebase or Supabase

Store posts in a database

Enable global post sharing between users

Comment system


## 🧑‍💻 Author
Ezekiel Taiwo Olatunji
Frontend Dev | Web3 Enthusiast
GitHub: @EzekielBliss


## Let me know if you’d like to include a live demo link or auto-create the MIT license file too.
