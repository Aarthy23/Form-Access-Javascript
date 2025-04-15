# 📋 JavaScript Mini Project – Form Access (signup and login)

This project focuses on building a **User Registration and Login Form** with custom **form validation** using **JavaScript**. It strengthened my skills in using the **DOM (Document Object Model)** to read, manipulate, and validate user input dynamically before form submission.

---

## 🛠️ Technologies Used

- ✅ **HTML5** – Structure of the form  
- ✅ **CSS3** – Styling and layout  
- ✅ **JavaScript** – Validation logic and DOM interaction  
- ✅ **jQuery** – Page transitions between signup/login  

---

## ✨ Features

- User-friendly **Signup & Login interface**
- Real-time validation for:
  - ✅ **Name** (Required)
  - ✅ **Phone Number** (Exactly 10 digits)
  - ✅ **Email** (Must contain letters, numbers, and `@`)
  - ✅ **Password** (Exactly 8 characters, with letter, number, and special character)
  - ✅ **Confirm Password** (Must match password)
- Alert messages for missing or invalid fields  
- `focus()` used to guide the user to invalid inputs  
- Prevents form submission if any validation fails  
- Dynamic page switching using **jQuery slide effects**

---

## 🧪 JavaScript Validation Highlights

- **Regex Patterns Used:**
  - Email: `/^(?=.*[a-zA-Z])(?=.*\d)(?=.*[@])[a-zA-Z\d@.]+$/`
  - Phone: `/^[0-9]{10}$/`
  - Password: `/^(?=.*[a-zA-Z])(?=.*\d)(?=.*[^a-zA-Z0-9]).{8}$/`
- **DOM Functions:**
  - `getElementById()` for accessing inputs
  - `focus()` for invalid fields
  - `return false` to prevent submission on error

---

## 📚 Key Concepts Learned

- ✅ DOM Manipulation  
- ✅ Writing validation logic using JavaScript  
- ✅ Using RegEx for field pattern matching  
- ✅ Preventing invalid form submission  
- ✅ Implementing jQuery for smoother UI/UX  

---

## 🛠️ Fixes/Improvements

- Fixed assignment error (`=`) used instead of comparison (`==`) in conditional checks  
- Improved regex for email and password validation  
- Ensured all error alerts are descriptive and helpful  
- Applied `.focus()` to each input for enhanced user experience  

---

## 🚀 Goal of the Project

This project replicates real-world scenarios where **form data validation is essential before submission**. It boosted my confidence in front-end development and handling **user interactions** dynamically using **JavaScript**.



