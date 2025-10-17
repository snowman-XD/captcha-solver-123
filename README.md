# Captcha Solver Application

This is a simple, single-file responsive web application designed to demonstrate a basic CAPTCHA solving mechanism using a predefined image or a dynamically loaded image URL.

## Features

*   **Dynamic Image Loading:** Loads CAPTCHA images from a `url` query parameter or defaults to `sample.png`.
*   **User Input:** Provides an input field for users to enter the CAPTCHA text.
*   **Verification:** Checks the entered text against a hardcoded correct value for the `sample.png` CAPTCHA. (The expected text for `sample.png` is "ADUR3".)
*   **Responsive Design:** Built with Tailwind CSS for a modern, mobile-first approach.

## How to Run

1.  Save the `index.html`, `README.md`, and `LICENSE` files into a single directory.
2.  Ensure `sample.png` (provided separately) is in the same directory.
3.  Open `index.html` in your web browser.

## Usage

*   **Default:** Open `index.html` to see the `sample.png` CAPTCHA. Enter "ADUR3" to verify.
*   **Custom Image:** To load a different CAPTCHA image, append a `url` query parameter to the URL. For example: `index.html?url=https://example.com/your-captcha.png`. *Note: This application only loads and displays external images; it does not contain advanced OCR or machine learning to "solve" arbitrary dynamic CAPTCHAs. The verification logic is only active for the default `sample.png`.* 

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS:** For styling and responsive design.
*   **JavaScript (ES6+):** For dynamic content loading and basic CAPTCHA verification logic.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
