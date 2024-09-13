# Task 10 - Registration Form 

This task , named `Task 10`, consists of a simple registration form built with HTML, CSS, and JavaScript. It includes a basic setup for a registration page and a submission page. The project is designed to demonstrate the use of HTML forms, CSS styling, and JavaScript validation.

## Project Structure

- `index.html` - The main registration form page.
- `submit.html` - A confirmation page displayed after form submission.
- `style.css` - The CSS file containing styles for the registration form.
- `script.js` - The JavaScript file containing logic for form validation.

## How to Run

1. **Open the Project**

   Open the `index.html` file in a code editor, such as VSCodium.

2. **Start LiveServer**

   - Right-click inside the `index.html` file and select "Open with Live Server" from the context menu.
   - Your default web browser will open and display the registration form.

## Functionality

- **Registration Form (`index.html`)**

   - Contains fields for First Name, Last Name, Email ID, Phone Number, Password, and Confirm Password.
   - On form submission, it redirects to `submit.html` using the GET method.
   - Includes basic styling from `style.css` and JavaScript validation from `script.js`.

- **Submission Page (`submit.html`)**

   - Displays a message indicating successful registration and prompts the user to check their email.

## Styling

- **CSS (`style.css`)**

   - Provides basic styling for the registration form to improve its appearance.
   - Styles include form layout, input fields, and buttons.

## JavaScript Validation

- **JavaScript (`script.js`)**

   - Validates that the password and confirm password fields match before allowing form submission.
   - Displays an alert if the passwords do not match and prevents form submission.

## Moving CSS and JavaScript

1. **CSS**

   - The CSS code was initially included in `index.html` but was moved to `style.css` for better organization.
   - Ensure `index.html` links to `style.css` using the following line in the `<head>` section:
     ```html
     <link rel="stylesheet" href="style.css">
     ```

2. **JavaScript**

   - The JavaScript code was initially included in `index.html` but was moved to `script.js`.
   - Ensure `index.html` links to `script.js` using the following line just before the closing `</body>` tag:
     ```html
     <script src="script.js"></script>
     ```
