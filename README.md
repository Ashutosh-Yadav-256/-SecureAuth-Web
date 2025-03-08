
# SecureAuth Web

**SecureAuth Web** is a secure web application that provides user registration and login functionality with enhanced password validation and hashing.

## Features

- User Registration with validation:
  - Password must be at least 8 characters long.
  - Password must contain at least one letter and one number.
  - Password confirmation required.
  - Email format validation.
- Secure User Login:
  - Passwords are hashed using SHA-256 before being sent to the server.
  - Client-side error handling.
- Responsive UI using Bootstrap 5.
- Loading indicators for better user experience.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript, Bootstrap 5
- **Security Features:** Password hashing (SHA-256), input validation
- **Backend (to be implemented):** Node.js, Express, MongoDB (suggested)
