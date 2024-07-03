# CircleCircleInteraction - Interactive Circle Animation

This project showcases an interactive animation of moving circles using HTML5 Canvas and JavaScript. The animation features multiple circles that move around the screen, bounce off the edges, and display intersection points when they overlap.

## Features

- Dynamic circle generation with random sizes and velocities
- Smooth animation using requestAnimationFrame
- Edge detection and bouncing behavior
- Intersection point calculation and visualization
- Responsive design that adapts to window resizing

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Canvas API

## How It Works

The main components of this project are:

1. `index.html`: Sets up the basic structure and includes necessary scripts and styles.
2. `styles.css`: Provides styling for the full-screen canvas.
3. `sketch.js`: Contains the core logic for circle creation, movement, and intersection detection.

The animation creates a set number of circles with random properties (size, position, velocity). Each frame, it updates the positions of the circles, checks for collisions with the canvas edges, and calculates intersection points between overlapping circles.

## Getting Started

To run this project locally:

1. Clone the repository
2. Open `index.html` in a modern web browser

## Customization

You can easily customize the animation by modifying the following variables in `sketch.js`:

- `circlesNum`: Change the number of circles in the animation
- `Circle()`: Adjust the min/max values for circle radius and velocity

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](link-to-your-issues-page) if you want to contribute.

## License

This project is open source and available under the [MIT License](link-to-license).