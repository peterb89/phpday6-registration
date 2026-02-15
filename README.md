# PHP Registration Form – Exercise 1

This project is a simple PHP registration form created for the Real Estate Management course (Exercise 1).  
It includes full server-side validation and protection against HTML injection.

## ✔ Features

- First name validation (letters + spaces, 3–30 characters)
- Last name validation (letters + spaces, 3–30 characters)
- Email validation using `filter_var()`
- Strict password policy:
  - at least 1 letter
  - at least 1 number
  - minimum 6 characters
- Image upload validation (checks if a file was selected)
- HTML injection protection using `cleanInput()`
- Bootstrap 5 styling

## 📁 Files included

- `register.php`
- `function.php`
- ZIP file with the full project

## 🎯 Purpose

This project was created as part of the PHP basics module to practice:
- form handling  
- server-side validation  
- file uploads  
- secure input processing  

