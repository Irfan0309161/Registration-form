# Registration-form
# 🎓 GPCET Student Registration Form

A simple and responsive **Student Registration Form** built using **HTML, CSS, and JavaScript**. This project demonstrates how to create a user-friendly form, collect user input, and display the submitted data on the webpage without reloading the page.

---

## 📌 Features

- Clean and responsive UI
- Attractive gradient background
- Student Registration Form
- Input validation using HTML5
- Gender selection using radio buttons
- Date of Birth picker
- Password field
- Displays submitted data dynamically using JavaScript
- Prevents page refresh using `event.preventDefault()`

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (DOM Manipulation)

---

## 📂 Project Structure

```
GPCET-Student-Form/
│
├── index.html
└── README.md
```

---

## 📷 Preview

The registration form contains:

- First Name
- Last Name
- Roll Number
- Gender
- Date of Birth
- Password
- Submit Button

After clicking **Submit**, the entered information is displayed below the form using JavaScript.

---

## 🚀 How It Works

1. Open the project in any web browser.
2. Fill in all required fields.
3. Click the **Submit** button.
4. JavaScript captures the form data using the **FormData API**.
5. The page does not reload.
6. Submitted information is displayed dynamically.

---

## 💻 JavaScript Concepts Used

- DOM Manipulation
- Event Listeners
- FormData API
- Template Literals
- `preventDefault()`
- Dynamic HTML using `innerHTML`

---

## 📋 Form Fields

| Field | Type |
|--------|------|
| First Name | Text |
| Last Name | Text |
| Roll Number | Text |
| Gender | Radio Button |
| Date of Birth | Date |
| Password | Password |

---

## 🎯 Learning Objectives

This project helps beginners understand:

- Creating HTML forms
- Styling forms using CSS
- Responsive layouts
- Handling form submissions with JavaScript
- Reading user input
- Displaying dynamic content
- Basic client-side validation

---

## ⚠️ Known Issues

The current code has a few minor issues:

1. The **Last Name** input contains an incorrect `name` attribute.
2. The page is missing an element with `id="output"` where the submitted data should be displayed.
3. `required` should be added to the radio buttons individually instead of the `<div>`.
4. Password is displayed in plain text after submission (not recommended in real applications).
5. Multiple `autofocus` attributes are used, but only one should exist.

---

## 🔧 Suggested Improvements

- Add Email field
- Add Phone Number field
- Confirm Password field
- Show/Hide Password feature
- Form Reset button
- Store data using Local Storage
- Connect with PHP/MySQL backend
- Better validation using JavaScript
- Success notification after submission
- Mobile responsive improvements

---

## 📈 Future Enhancements

- Student Login System
- Admin Dashboard
- Database Integration
- Student Profile Management
- Attendance Module
- Result Management
- File Upload Feature

---

## 👨‍💻 Author

**Irfan Shaik**

---

## 📄 License

This project is open-source and available for educational and learning purposes.

---

### ⭐ If you found this project helpful, don't forget to star the repository!
