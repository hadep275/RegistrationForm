# RegistrationForm

This README provides an overview of the HTML and CSS code for a registration form. The code is designed for a web page that allows users to register with their personal or business information. Below, you'll find a breakdown of the structure and styling of the form.

[Click here to access the deployed application](https://your-deployed-url.com)

## HTML Structure

### Head Section

- The HTML document includes standard elements like `<html>`, `<head>`, and `<meta>` tags to define the document's character set and viewport settings.
- The page title is set to "Registration Form," and an external CSS file, "styles.css," is linked for styling.

### Body Section

- The `<body>` section contains the registration form itself.
- A prominent heading `<h1>` displays "Registration Form," and a brief introductory message is provided with a `<p>` element.
- The form is enclosed within a `<form>` element. It is configured to submit data to a specified action URL, in this case, "https://register-demo.freecodecamp.org."

### Form Structure

- The form is divided into three `<fieldset>` sections, each containing a group of related input fields.

### First Fieldset

- The first fieldset includes the following fields:
  - First Name (`<input type="text">`)
  - Last Name (`<input type="text">`)
  - Email Address (`<input type="email">`)
  - New Password (`<input type="password">`)
  - All fields in this fieldset are required.

### Second Fieldset

- The second fieldset contains:
  - Radio buttons for selecting an account type (Personal or Business).
  - A checkbox for accepting terms and conditions.
  - A link to the terms and conditions is provided within the label.

### Third Fieldset

- The third fieldset comprises:
  - An option to upload a profile picture using a file input.
  - Input for age (a number input with minimum and maximum values).
  - A dropdown list for selecting a referrer.
  - A textarea for providing a bio.

## CSS Styling

The provided CSS rules in the "styles.css" file are responsible for styling the registration form. The notable styling aspects include:

- Setting the background color to "#1b1b32" and text color to "#f5f6f7" for the entire page.
- Center-aligning the heading and introductory text.
- Styling form elements, including setting background colors, border styles, and text colors.
- Adjusting the width and alignment of various form elements (input fields, radio buttons, etc.).
- Styling the submit button with specific dimensions and colors.
- Setting the link color to "#dfdfe2."

## Instructions

1. Download the HTML and CSS files provided in this repository.
2. Customize the form fields, labels, and styling as needed for your specific registration form.
3. Modify the form's action URL to the appropriate endpoint where you want to submit the registration data.
4. Ensure that the terms and conditions link (`<a>` tag) points to the correct destination.
5. Test the form on your web server or hosting platform.

Enjoy using this registration form template for your website!
