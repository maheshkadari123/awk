# Login Page Project

## Description
This project is a simple login page that validates user input and provides feedback based on the validation results. It uses HTML, CSS, and JavaScript to create a user-friendly interface with form validation and API login functionality.

## Features
- Input validation for username/email and password.
- Show/hide password functionality.
- Remember Me feature.
- Loading spinner during login request.
## Installation
To run this project, you don't need any special installation. Just ensure you have a web browser installed on your computer.

## Usage
1. Clone or download this repository to your local machine.
2. Open the `index.html` file in your web browser.
3. Fill in the username/email and password fields.
4. Click the "Submit" button to log in.

## Project Files
- **index.html**: The HTML file that contains the structure of the login page.
- **styles.css**: The CSS file that styles the login page.
- **script.js**: The JavaScript file that handles form validation, password visibility toggle, and API login request.
- **README.md**: This file, containing instructions on how to run the project.

## Validation Rules
- **Username/Email**: 
  - Required field.
  - Must be in a valid email format.
- **Password**: 
  - Required field.
  - Must be at least 6 characters long.

## API Login
The login function sends a POST request to the JSONPlaceholder API for demonstration purposes. In a real-world application, you should replace the URL with your actual API endpoint.

## Customization
You can customize the project by:
- Updating the styles in the `styles.css` file.
- Modifying the validation logic in the `script.js` file.
- Replacing the API URL in the `login` function with your own endpoint.

## Notes
- This project uses Font Awesome for the icons. Ensure you have an internet connection to load the icons from the CDN.
- The Remember Me feature uses `localStorage` to save the username.

## Credits
- **Font Awesome**: For the icons used in the project.
- **JSONPlaceholder**: For providing a free fake API for testing and prototyping.

## Contact
For any questions or feedback, please contact [Your Name] at [Your Email].
