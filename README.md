# Coding School Quiz System - Sign-up Page

This repository contains the HTML, CSS, and JavaScript code for the sign-up page of a Coding School Quiz System. This form allows users to create an account by entering their details, with real-time validation and feedback on password strength.

## Features

- **Responsive Layout**: The page layout is optimized for various screen sizes, with a two-column design on larger screens and a simplified single-column design on mobile.
- **Password Strength Checker**: The password field includes a strength checker, with visual indicators for weak, medium, and strong passwords.
- **Validation Feedback**: Instant validation with error messages for each field, including full name, email, experience level, and password.
- **Interactive Styling**: Real-time input styling changes based on validation status for a user-friendly experience.

## Folder Structure

- **HTML**: The sign-up page structure is written in HTML with embedded CSS and JavaScript.
- **CSS**: Inline CSS defines the layout, animations, and styling.
- **JavaScript**: Embedded JavaScript handles form validation, password strength checks, and controls the sign-up button's enabled/disabled state.

## Instructions

1. **Clone the repository** to your local machine:

   ```bash
   git clone https://github.com/niyontwali/signup-page.git
   ```

2. **Open the file** in your preferred browser to view the form layout and functionality.

   ```bash
   open index.html
   ```

3. **Test the Form**: 
   - Fill in the fields, and observe error messages or indicators as you type.
   - Try different passwords to see the strength indicator's response.
   - Once all fields are valid, the "Create Account" button becomes enabled.

## Form Fields

1. **Full Name**:
   - Required; must contain a minimum of 3 characters and a space (for full name).
   
2. **Email**:
   - Required; must follow standard email format.
   
3. **Programming Experience**:
   - Required; options include Beginner, Intermediate, and Advanced.
   
4. **Password**:
   - Required; includes feedback on strength with recommendations for improvement.

## Form Validation

Validation is implemented to ensure user input meets the required criteria:

- **Full Name**: Checks for minimum length and space inclusion.
- **Email**: Validates against a regex pattern.
- **Programming Experience**: Checks if an option is selected.
- **Password**: Feedback on strength based on criteria like length, uppercase, numeric, and special characters.

## Password Strength Feedback

The password strength indicator updates based on these factors:

- **Weak**: Fails multiple criteria.
- **Medium**: Satisfies 3-4 criteria.
- **Strong**: Meets all criteria.

## License

This project is available under the MIT License.