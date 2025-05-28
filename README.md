# Responsive Login Page

A responsive login page created with HTML, CSS (using Tailwind CSS), and React. This is a standalone frontend implementation that can be easily integrated into any project.

## Features

- Responsive design that works on all device sizes
- Email and password input fields with validation
- Login button with form submission handling
- "Create new account" link that redirects to a signup page
- "Forgot password?" link that redirects to a password reset page
- Form validation for required fields and valid email format
- React state management for form data
- Modern, clean UI with Tailwind CSS

## How to Use

1. Simply open the `index.html` file in a web browser to view the login page.
2. The page includes placeholder links to the signup and password reset pages.
3. The form has client-side validation that checks for:
   - Required email and password fields
   - Valid email format

## Implementation Details

- Uses React (loaded via CDN) for component-based architecture and state management
- Uses Tailwind CSS (loaded via CDN) for styling
- Uses Babel (loaded via CDN) for JSX transpilation
- No server-side implementation is included - this is a frontend-only solution

## Notes

- In a production environment, you would typically:
  - Use a bundler like webpack or Vite
  - Implement proper authentication with a backend service
  - Add more robust form validation
  - Use a state management solution for larger applications 