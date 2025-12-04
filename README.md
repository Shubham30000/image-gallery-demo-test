# Responsive Image Gallery

## Live Demo
Check out the live demo here: [DEPLOYMENT_URL_PLACEHOLDER](DEPLOYMENT_URL_PLACEHOLDER)

## Overview
This project presents a responsive image gallery built with pure HTML, Tailwind CSS from CDN, and vanilla JavaScript. It demonstrates a modern and clean way to display a collection of images, featuring a grid layout that adapts to various screen sizes and a modal viewer for full-size image viewing.

## Features
*   **Responsive Design:** Adapts seamlessly to desktop, tablet, and mobile devices using Tailwind CSS utility classes.
*   **Image Grid Layout:** Utilizes Tailwind's grid system for an organized and aesthetically pleasing display of images.
*   **Hover Effects:** Interactive hover animations on gallery items for an engaging user experience.
*   **Modal Image Viewer:** Click any image to open a full-size version in a responsive modal, complete with a close button and overlay dismissal.
*   **Vanilla JavaScript:** Lightweight and efficient JavaScript handles the modal functionality without external libraries.
*   **Local Image Support:** Images are referenced as local files (e.g., `sample.png`).

## Technologies Used
*   **HTML5:** The core structure of the web page.
*   **Tailwind CSS (CDN):** A utility-first CSS framework for rapid UI development and responsive design.
*   **Vanilla JavaScript:** For interactive elements, specifically the image modal logic.

## Setup
To run this project locally, follow these simple steps:

1.  **Clone the repository (or download the files):**
    ```bash
    git clone <repository-url>
    cd <project-folder>
    ```
    (Note: If only receiving files, simply create a folder and place `index.html`, `README.md`, and `LICENSE` inside it, along with `sample.png`.)

2.  **Ensure image files are present:** Make sure `sample.png` is in the same directory as `index.html`.

## Usage
Simply open `index.html` in your web browser. The gallery will load, and you can interact with the images:

*   **Browse:** Scroll through the responsive grid of images.
*   **View Full Size:** Click on any image to open it in a modal dialog.
*   **Close Modal:** Close the modal by clicking the 'X' button, clicking outside the image on the overlay, or pressing the `Escape` key.

## Project Structure
```
.
├── index.html        # Main HTML file with gallery and modal
├── sample.png        # Image attachment used in the gallery
├── README.md         # Project documentation
└── LICENSE           # MIT License file
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
