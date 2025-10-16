# Image and CSV Display Project

## Description

This is a simple static web application that displays an image and tabular data from a CSV file. The application loads the image and CSV data from data URIs provided through the `window.attachments` object.

## Features

- Displays an image.
- Displays CSV data in a table.
- Responsive design for mobile and desktop viewing.
- Uses vanilla JavaScript, no external frameworks required.
- Clean and modern design.

## How to Use

1.  **Deployment**: Deploy the `index.html` file to a static web hosting service like GitHub Pages, Netlify, or Vercel.
2.  **Accessing the Image and CSV**: The image displayed is loaded from `window.attachments['file-0']` if it's an image, and the CSV data is loaded from `window.attachments['file-0']` if it's a CSV. Ensure that the `window.attachments` object is populated with the image data URI or CSV data when running the application.

## Technologies Used

-   HTML5
-   CSS3 (Embedded)
-   JavaScript (Vanilla)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.