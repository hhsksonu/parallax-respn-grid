# Parallax Effect with Responsive Grid

This project implements a parallax scrolling effect along with a responsive grid layout. The webpage includes a background with a parallax effect, a responsive grid of cards, and a scroll-to-top button that scrolls back to the parallax section when clicked.

## Features

- **Parallax Scrolling Effect:** The first section (`section1`) has a parallax background effect with layered images for a 3D effect as you scroll.
- **Responsive Grid Layout:** The second section (`section2`) contains a grid of cards that adapt to different screen sizes. It uses CSS Grid to ensure cards are properly aligned and spaced.
- **Smooth Scroll Button:** A circular button is positioned at the bottom-right corner of the `section2`, which, when clicked, smoothly scrolls back to the first section.
- **Hover Effects:** Cards have hover effects that make them scale slightly and add shadow for interactivity.
- **Cross-Device Compatibility:** The layout and button adjust for various screen sizes, making it mobile-friendly.

## Installation

To get started with this project locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/hhsksonu/parallax-respn-grid.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd parallax-effect-responsive-grid
    ```

3. **Open the `index.html` file in your browser** to view the project.

## Files Structure

- `index.html`: The main HTML file containing the structure of the webpage.
- `styles.css`: The CSS file that styles the sections, grid, and scroll button.
- `base.png`, `outer-layer-blur.png`: Image files used for the parallax effect in the first section.

## How It Works

### Parallax Section (`section1`):
- The background images are positioned in a way that creates a parallax effect. The images move at different speeds as you scroll, giving the illusion of depth.
- Text is overlaid on top of the background with a shadow for better visibility.

### Responsive Grid Section (`section2`):
- A CSS Grid layout is used to display a series of cards. The grid automatically adjusts the number of columns based on the screen size.
- Each card has a hover effect that scales it slightly and adds a shadow for a dynamic user experience.

### Scroll-to-Top Button:
- The button is a circular element with an upward arrow. It’s positioned fixed at the bottom-right of `section2` and scrolls the page smoothly back to the first section when clicked.

## Technologies Used

- **HTML5** for the structure of the page.
- **CSS3** for styling and animations, including parallax effects and responsive design.
- **JavaScript** for the smooth scrolling functionality of the scroll-to-top button.

## Contributing

Feel free to fork this project and submit pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
