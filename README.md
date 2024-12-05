# Forgot and Reset Password Pages

This repository contains the **Forgot Password** and **Reset Password** pages, developed as part of a collaborative team project. These pages are designed for the frontend functionality of a website, adhering to modern UI/UX principles. My contribution focused on implementing these pages using **HTML**, **CSS**, and **JavaScript**.

---

## Features

### Forgot Password Page
- Input field for users to enter their email address.
- Validation of email addresses to ensure they follow the correct pattern (e.g., `example@example.com`).
  - **Alerts**:
    - "Please enter a valid email" if the email field is left empty.
    - "Invalid email address" if the email doesn't match the expected format.
- Displays a modal popup notification: "A reset password link has been sent to your email address." when a valid email is submitted.

### Reset Password Page
- Input fields for:
  - **New Password**
  - **Confirm Password**
- Password validation criteria:
  - At least 6 characters.
  - At least one uppercase letter.
  - At least one lowercase letter.
  - At least one special character.
- Matching confirmation for the two password fields.
- **Alerts**:
  - "Password does not meet the criteria" if the password does not satisfy the validation rules.
  - "Passwords do not match" if the two password fields do not match.
- Displays a modal popup notification: "Your password has been successfully reset!" upon successful submission.
- Redirects to the login page after password reset.

---

## Technology Stack
- **HTML**: Structure of the pages.
- **CSS**: Styling, including responsive design and polished UI components.
- **JavaScript**: Implementing client-side validation, modal popups, and interactivity.

---

## Contribution
This project was a team effort. My contributions included:
- Designing and implementing the Forgot Password and Reset Password pages.
- Ensuring functionality through JavaScript for validation and interactivity.
- Styling the pages with enhanced visual elements to provide a seamless user experience.
