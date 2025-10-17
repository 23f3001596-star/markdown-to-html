# Markdown to HTML Renderer

This project provides a simple, single-page HTML application designed to convert Markdown content from an `input.md` file into a styled HTML page. It leverages Tailwind CSS for responsive design and `marked.js` for efficient Markdown parsing.

## Features

*   **Markdown to HTML Conversion:** Automatically reads `input.md` and renders its content as HTML.
*   **Responsive Design:** Built with Tailwind CSS, ensuring a consistent and user-friendly experience across various devices.
*   **Easy to Use:** A self-contained application that requires no complex setup.

## Getting Started

To view the application:

1.  Ensure you have `index.html` and `input.md` in the same directory.
2.  Open `index.html` in your web browser.

The page will automatically fetch `input.md`, convert its content to HTML, and display it within the browser.

## Technologies Used

*   **HTML5:** The core structure of the web page.
*   **Tailwind CSS:** A utility-first CSS framework for styling and responsive design. (Used via CDN)
*   **Marked.js:** A fast and lightweight Markdown parser and compiler. (Used via CDN)

## File Structure

```
.
├── index.html
├── input.md
└── README.md
└── LICENSE
```

## Customization

*   **`input.md`:** Modify this file to change the Markdown content displayed on the page.
*   **`index.html`:** Adjust Tailwind CSS classes or add custom CSS within the `<style>` tags to alter the appearance. Update the JavaScript if you wish to fetch Markdown from a different source or implement additional functionality.
