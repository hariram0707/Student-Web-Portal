# 🎓 Student Web Portal (Login & Registration)

A responsive student login and registration web page built with **HTML, CSS and a little JavaScript**. The page title and main heading is **"Welcome to Student Web Portal"**.

---

## 📌 Project Description

This project is a front-end student portal with a modern glass-style design. A student can switch between **Login** and **Registration** forms on the same page. When the Login or Register button is clicked, the page does not reload or open another page. Instead, a message box appears saying **"Your response has been recorded"**.

---

## ✨ Features

- Unique glassmorphism (frosted glass) design with an animated gradient background
- Floating blurred background shapes
- Welcome panel with portal highlights (courses, timetable, results, notices)
- Login / Register tab switch with a sliding animated indicator
- **Login form:** Student ID/Email, Password, Remember me, Forgot password link
- **Registration form:** Full Name, Roll Number, Department, Email, Password, Confirm Password, Terms checkbox
- Required-field validation (the browser checks empty fields)
- Animated success message box: **"Your response has been recorded"** with a tick icon and an OK button
- Buttons with hover shine effect and click animation
- Fully responsive for desktop, tablet and mobile

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Page structure and forms |
| CSS3 | Styling, animations, responsive layout |
| JavaScript | Shows and hides the success message box |

---

## 📁 Project Structure

```
student-portal/
│
├── index.html     # Page structure, forms and script
├── style.css      # All design, animations and layout
└── README.md      # Project documentation
```

---

## ▶️ How to Run

**Using VS Code (Live Server):**
1. Open the `student-portal` folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html` and select **Open with Live Server**.

**Without any extension:**
- Double-click `index.html` to open it in your browser.

---

## 🔄 How It Works

1. The page opens on the **Login** tab by default.
2. Clicking **Register** (or "Create an account") switches to the registration form. This is done with hidden radio buttons and CSS, with no JavaScript needed.
3. The student fills in the required fields and clicks **Login** or **Register**.
4. JavaScript stops the normal form submission, so the page stays on the same screen.
5. A success box appears with the message **"Your response has been recorded"**.
6. Clicking **OK** closes the message box.

---

## ⚠️ Limitations

- This is a front-end only project. Entered data is **not saved** anywhere.
- No real authentication is performed.
- To store data and verify users, a backend (such as Node.js, PHP or Python) and a database would be needed.

---

## 🚀 Future Improvements

- Connect to a backend and database (MySQL / MongoDB)
- Add password strength check and password match validation
- Add a student dashboard page after login
- Add a show/hide password option
- Add email verification and a forgot-password flow

---

## 👤 Author

**Hariram C**
