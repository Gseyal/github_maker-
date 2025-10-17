This is a simple HTML form with a modern UI built using Tailwind CSS. It allows users to input various data fields, including email, secret, task details, and descriptions. The form also dynamically displays the entered data as a JSON object in a separate panel.

## Features:

*   **Responsive Design**: Adapts to different screen sizes.
*   **Modern UI**: Clean and minimal design with Tailwind CSS.
*   **Dynamic JSON Output**: Real-time display of form data in JSON format.
*   **Form Submission**: Submits data to a specified endpoint (`https://seyal-p1.hf.space/ready`).

## How to Use:

1.  **Open `index.html`** in your web browser.
2.  **Fill in the form fields** on the left panel.
3.  **Observe the JSON output** updating in real-time on the right panel.
4.  **Click 'Submit'** to send the form data to the configured endpoint.

## Development:

No build steps are required. Simply open `index.html`.

The form uses a CDN link for Tailwind CSS, so no local installation is needed.

## Customization:

*   **Styling**: Modify the Tailwind CSS classes within `index.html` to change the appearance.
*   **Endpoint**: Update the `url` variable in the JavaScript section to point to your desired submission endpoint.
*   **Form Fields**: Add or remove input fields by editing the HTML form structure.

## Files:

*   `index.html`: The main HTML file containing the form and JavaScript logic.
*   `README.md`: This file.
*   `LICENSE`: The license file for this project.
