# Captcha Solver Application

This is a simple client-side web application designed to demonstrate the concept of a captcha solver. It displays an image (acting as a captcha) and allows the user to input the text they perceive. While this example hardcodes the solution for demonstration purposes, it showcases the basic frontend interaction for such a system.

## Features

*   **Dynamic Image Loading:** Loads a captcha image from a URL query parameter or defaults to a local image.
*   **User Input:** Provides an input field for the user to type the captcha text.
*   **Basic Validation:** Compares user input against a hardcoded solution (for `sample.png`).
*   **Responsive Design:** Utilizes Tailwind CSS for a modern and responsive user interface.

## Usage

1.  **Open `index.html`:** Simply open the `index.html` file in your web browser.

2.  **Default Captcha:** By default, the application will display `sample.png`. You can type "ADCR3" (case-insensitive) into the input field to solve it.

3.  **Custom Captcha Image:** To display a different captcha image, append a `url` query parameter to the URL in your browser.

    **Example:**
    If your `index.html` is at `http://localhost:8000/index.html`, you can use:
    `http://localhost:8000/index.html?url=https://example.com/your-captcha-image.png`

4.  **Solving:** Enter the text you see in the displayed image into the input box and click "Submit". The application will provide feedback on whether the solution is correct or incorrect.

## Technologies Used

*   **HTML5:** For the page structure.
*   **Tailwind CSS:** For styling and responsive design.
*   **JavaScript (ES6+):** For dynamic image loading and form handling.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
