# Modern Submission Form UI

This project provides a single-file, responsive HTML application for submitting data, built with a modern user interface using Tailwind CSS. It features input fields for various data points including email, secret, task details, and attachments.

## Features

*   **Responsive Design:** Adapts to different screen sizes, from mobile to desktop.
*   **Modern UI:** Clean and intuitive design using Tailwind CSS for styling.
*   **Key Data Inputs:** Includes fields for `email`, `secret`, `task`, `round`, `nonce`, `brief`, `checks`, and `evaluation_url`.
*   **Attachment Reference:** Demonstrates how to reference accompanying files, such as `input.md`.

## Setup and Usage

To use this application:

1.  Save the `index.html` file into a directory.
2.  Ensure any referenced attachments (e.g., `input.md`) are placed in the **same directory** as `index.html`.
3.  Open `index.html` in any modern web browser.

The form is designed for client-side display and interaction. To process submissions, you would typically integrate this form with a backend service (e.g., using JavaScript to send data via an API call) which is beyond the scope of this front-end example.

## Technologies Used

*   **HTML5:** For the core structure of the web page.
*   **Tailwind CSS:** A utility-first CSS framework for rapid UI development. (CDN version used for simplicity).
