# <div align="center">📝 HTML Forms</div>

<div align="center">

![HTML](https://img.shields.io/badge/HTML5-Forms-orange?style=for-the-badge&logo=html5)
![Level](https://img.shields.io/badge/Level-Beginner-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Practice-Completed-blue?style=for-the-badge)

</div>

---

# 📖 About

This folder contains practice programs related to HTML forms.

Forms are one of the most important parts of web development because they allow users to enter and submit data on websites.

---

# 🎯 Objectives

✅ Learn how to create HTML forms  
✅ Understand different input types  
✅ Collect user information  
✅ Practice form structure and layout  
✅ Build interactive webpages  

---

# 📂 Files Included

```text
05_forms/
│
├── index.html
└── README.md
```

---

# 📚 Concepts Used

| Tag / Attribute | Purpose |
|---|---|
| `<form>` | Create HTML form |
| `<input>` | User input field |
| `type="text"` | Text input |
| `type="email"` | Email input |
| `type="password"` | Password input |
| `type="radio"` | Single choice selection |
| `type="checkbox"` | Multiple selections |
| `<textarea>` | Multi-line input |
| `<select>` | Dropdown menu |
| `<option>` | Dropdown options |
| `placeholder` | Input hint text |

---

# 💻 HTML Code

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Forms</title>
</head>
<body>

    <h1>Student Registration Form</h1>

    <form>

        <label>Full Name:</label>
        <input type="text" placeholder="Enter your name">

        <br><br>

        <label>Email:</label>
        <input type="email" placeholder="Enter your email">

        <br><br>

        <label>Password:</label>
        <input type="password" placeholder="Enter password">

        <br><br>

        <label>Gender:</label>

        <input type="radio" name="gender"> Male
        <input type="radio" name="gender"> Female

        <br><br>

        <label>Skills:</label>

        <input type="checkbox"> HTML
        <input type="checkbox"> CSS
        <input type="checkbox"> JavaScript

        <br><br>

        <label>Date of Birth:</label>
        <input type="date">

        <br><br>

        <label>Choose Your City:</label>

        <select>
            <option>Kolkata</option>
            <option>Delhi</option>
            <option>Mumbai</option>
        </select>

        <br><br>

        <label>Message:</label>

        <br>

        <textarea rows="5" cols="30"></textarea>

        <br><br>

        <input type="submit" value="Register">

    </form>

</body>
</html>
```

---

# 🖥 Output

The webpage displays:

- Student registration form
- Text and email input fields
- Password field
- Radio buttons
- Checkboxes
- Dropdown menu
- Textarea
- Submit button

---

# 💡 What I Learned

✔ Creating HTML forms  
✔ Using different input types  
✔ Collecting user information  
✔ Building interactive webpages  
✔ Structuring form layouts properly  

---

# ⚡ Git Commands Used

```bash
git add .
git commit -m "Built student registration form using HTML"
git push origin main
```

---

# 🚀 Future Improvements

- Add CSS styling
- Make form responsive
- Add form validation
- Connect form with backend
- Create professional UI design

---

<div align="center">

# ⭐ HTML Forms Completed ⭐

</div>