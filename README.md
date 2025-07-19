# Creative Web Developer Portfolio

This is a modern, single-page portfolio website designed for creative web developers. It's built with HTML, Tailwind CSS, and a little bit of JavaScript to create a visually appealing and interactive experience. The design is clean, professional, and fully responsive, ensuring it looks great on all devices.

## Live Demo

[Link to your live portfolio website here]

## Features

-   **Modern & Clean Design:** A sleek, dark-themed UI with a unique aurora background effect.
-   **Fully Responsive:** Adapts seamlessly to desktops, tablets, and mobile devices.
-   **Interactive Elements:** Smooth scrolling, hover effects, and fade-in animations on scroll to engage visitors.
-   **Glassmorphism Navigation:** A semi-transparent "glass" navigation bar that stays fixed at the top.
-   **Structured Sections:** Includes sections for Home, About Me, Projects, Skills, and Contact.
-   **Easy to Customize:** Built with standard web technologies and Tailwind CSS for straightforward customization.
-   **Iconography:** Uses `lucide-react` for clean and modern icons.

## Technologies Used

-   **HTML5:** For the core structure and content.
-   **CSS3 / Tailwind CSS:** For all styling, layout, and responsiveness.
--   **JavaScript:** For dynamic functionalities like the mobile menu, smooth scrolling, and scroll-triggered animations.
-   **Lucide Icons:** For lightweight and beautiful SVG icons.
-   **Google Fonts:** For the 'Inter' font family.

## Project Structure

The project is organized into three main files for clarity and maintainability:


/
|-- index.html      # The main HTML file for content and structure
|-- style.css       # Custom CSS rules and component styles
|-- script.js       # JavaScript for interactivity and animations
|-- README.md       # You are here!


## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You just need a modern web browser (like Chrome, Firefox, or Edge) and a code editor (like VS Code).

### Installation

1.  **Clone the repository (or download the files):**
    ```sh
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd your-repo-name
    ```
3.  **Open `index.html` in your browser:**
    You can simply double-click the `index.html` file, or if you're using an editor like VS Code, you can use an extension like "Live Server" to view the site with hot-reloading.

## Customization Guide

This portfolio is designed to be easily personalized.

1.  **Update Content (`index.html`):**
    * **Text:** Open `index.html` and replace all placeholder text (like "John Doe", project descriptions, about me content, etc.) with your own information.
    * **Images:** Replace the placeholder image URLs from `https://placehold.co/...` with your own professional photos and project screenshots.
    * **Links:** Update the links for your GitHub, project details, and the contact email address.

2.  **Change Colors & Theme (`style.css` and `index.html`):**
    * The primary theme color is `indigo`. You can change this by searching for `bg-indigo-600`, `text-indigo-400`, etc., in `index.html` and replacing them with other Tailwind CSS color utilities (e.g., `bg-blue-600`, `text-green-400`).
    * The background `aurora` effect can be tweaked in `style.css` by changing the RGBA color values within the `radial-gradient`.

3.  **Modify Scripts (`script.js`):**
    * The JavaScript file controls the mobile menu and the fade-in-on-scroll animation. You can adjust the `IntersectionObserver` options (like `threshold` or `rootMargin`) to change when the animations trigger.

## License

This project is open-source and available under the [MIT License](LICENSE). Feel free to use it as a template for your own portfolio.
