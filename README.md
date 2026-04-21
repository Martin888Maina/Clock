# Analog Clock

A responsive analog clock built with vanilla HTML, CSS, and JavaScript. This project demonstrates clean code practices, modern web development techniques, and attention to visual design.

## Overview

This analog clock displays real-time hours, minutes, and seconds with smooth animations. The clock updates every second and features both analog and digital time displays for enhanced usability. The design is fully responsive and works seamlessly across desktop, tablet, and mobile devices.

## Features

- Real-time clock updates every second
- Smooth hand animations with accurate time representation
- Digital time display for accessibility
- Fully responsive design that adapts to all screen sizes
- Modern gradient background with elegant styling
- Hover effects and micro-animations for enhanced user experience
- Clean, semantic HTML structure
- Well-commented, maintainable code

## Technologies Used

- HTML5 for semantic structure
- CSS3 for styling, animations, and responsive design
- Vanilla JavaScript for clock logic and DOM manipulation

## How It Works

The clock uses JavaScript's `Date` object to retrieve the current time. Each clock hand (hour, minute, and second) is rotated using CSS transforms:

- Hour hand: Rotates 30 degrees per hour plus 0.5 degrees per minute
- Minute hand: Rotates 6 degrees per minute
- Second hand: Rotates 6 degrees per second

The `setInterval` function updates the clock every 1000 milliseconds (1 second), ensuring accurate time representation.

## Installation and Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/Martin888Maina/Clock.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Clock
   ```

3. Open `index.html` in your web browser:
   - Double-click the file, or
   - Right-click and select "Open with" your preferred browser, or
   - Use a local development server

No build process or dependencies required. Simply open the HTML file and the clock will start running.

## Project Structure

```
Clock/
├── index.html          # Main HTML file with structure and JavaScript
├── styles.css          # All styling, animations, and responsive design
├── clockface.png       # Clock face background image
├── README.md           # Project documentation
└── LICENSE             # MIT License
```

## Browser Compatibility

This project uses standard web technologies and works in all modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge

## Responsive Design

The clock is fully responsive with breakpoints at:
- Desktop: 768px and above (400px clock)
- Tablet: 481px to 768px (320px clock)
- Mobile: 480px and below (280px clock)

## Code Quality

- Clean, readable code with consistent formatting
- Descriptive variable and function names
- Thoughtful comments that explain the logic without being excessive
- Semantic HTML5 elements for better accessibility
- CSS organized by sections with clear separation of concerns
- No external dependencies or frameworks

## Future Enhancements

Potential improvements for future versions:
- Timezone selection and world clock functionality
- Customizable themes and color schemes
- Alarm and timer features
- Dark/light mode toggle
- Sound effects for hourly chimes

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

Martin Maina
- GitHub: [@Martin888Maina](https://github.com/Martin888Maina)

## Acknowledgments

This project was created as a demonstration of fundamental web development skills and serves as a portfolio piece showcasing clean code practices and modern design principles.
