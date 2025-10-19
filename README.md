# CAPTCHA Solver Application

This project provides a simple, single-page web application designed to demonstrate a basic CAPTCHA solving interface. It features a responsive layout built with Tailwind CSS and dynamically loads CAPTCHA images.

## Features

*   **Responsive Design**: Adapts to various screen sizes using Tailwind CSS.
*   **Dynamic Image Loading**: Loads CAPTCHA images either from a URL specified in the query parameter (`?url=...`) or defaults to a local `sample.png` if no URL is provided.
*   **Client-Side Verification (Simulated)**: Includes basic JavaScript to simulate CAPTCHA verification against a hardcoded solution for the `sample.png` image (which is "ADORS" based on the provided image).

## Getting Started

To run this application, simply open the `index.html` file in your web browser. Ensure that `sample.png` is in the same directory as `index.html`.

### Usage

1.  Open `index.html` in your browser. The `sample.png` image will be displayed.
2.  Alternatively, you can provide a CAPTCHA image URL using the `url` query parameter:
    `index.html?url=https://example.com/path/to/your/image.png`
3.  Enter the text you see in the CAPTCHA image into the input field.
4.  Click "Submit" to see the verification result.

## Technologies Used

*   **HTML5**: Structure of the web page.
*   **Tailwind CSS**: Utility-first CSS framework for styling and responsiveness.
*   **JavaScript**: For dynamic image loading and client-side CAPTCHA verification logic.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.