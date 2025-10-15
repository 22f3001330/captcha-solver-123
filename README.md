# Captcha Solver Frontend Application

This project provides a simple, responsive single-page application (SPA) frontend for a captcha solver. It displays a captcha image and allows users to input their solution. The application uses Tailwind CSS for styling and vanilla JavaScript for dynamic behavior.

## Features

-   **Responsive Design**: Built with Tailwind CSS to look good on various screen sizes.
-   **Dynamic Image Loading**: Displays a default captcha image (`sample.png`) or loads an image from a URL specified in the query parameters.
-   **User Input**: Provides an input field for users to type their captcha solution.
-   **Simulated Validation**: For the default `sample.png` captcha, it offers a client-side check for the known solution ("ADCR3"). For dynamically loaded images, it simulates a submission confirmation.

## Usage

To run this application, simply open the `index.html` file in your web browser.

### Default Captcha

When you open `index.html` directly, it will display the `sample.png` image:

`index.html`

### Loading a Custom Captcha Image

You can specify a custom image URL using the `?url=` query parameter in your browser's address bar. For example:

`index.html?url=https://example.com/path/to/your/captcha.png`

Make sure to URL-encode the image URL if it contains special characters.

### Solving the Captcha

1.  Observe the captcha image displayed.
2.  Type the characters you see in the image into the input field.
3.  Click the "Submit" button.

For `sample.png`, the correct answer is `ADCR3`.

## Project Structure

-   `index.html`: The main HTML file containing the application structure, styling (via Tailwind CDN), and JavaScript logic.
-   `sample.png`: The default captcha image displayed when no URL is provided.
-   `README.md`: This file.
-   `LICENSE`: The MIT License for this project.

## Technologies Used

-   **HTML5**: For the page structure.
-   **Tailwind CSS**: For utility-first styling (via CDN).
-   **JavaScript (Vanilla)**: For dynamic functionality and form handling.
