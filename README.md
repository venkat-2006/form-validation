

# React Form Validation with useState

## Description

This project demonstrates how to create a **controlled form** in React with real-time validation using the `useState` hook. It is a simple, responsive form that collects **name, email, and password**, and validates user input before submission.

The form includes the following features:

* **Controlled Components**: All input fields are controlled using React state.
* **Validation**: Checks for required fields, valid email format, and secure password rules (minimum length, uppercase letter, number, and special character).
* **Error Handling**: Displays user-friendly error messages below each input field.
* **Form Submission**: Only allows submission when all fields are valid and displays a success message.
* **Responsive Layout**: The form is centered on the page and works well on desktop and mobile devices.

## Technologies Used

* React
* Vite
* JavaScript
* CSS

## How it Works

1. **useState Hook**: Manages form data and validation errors.
2. **handleChange Function**: Updates state as users type into the input fields.
3. **validate Function**: Validates all fields and sets appropriate error messages.
4. **handleSubmit Function**: Prevents default form submission, runs validation, and displays form data if valid.

## Project Structure

src/
  ├─ App.jsx
  ├─ Form.jsx
  ├─ index.css
public/
  └─ background.jpg
index.html



