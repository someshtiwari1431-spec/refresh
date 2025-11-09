# Infinite Capital Management - Loan Website

A modern, responsive website for Infinite Capital Management, providing loan services with a focus on user experience and trust-building design.

## Features

- **Responsive Design**: Works on all devices from mobile to desktop
- **Interactive Loan Calculator**: Real-time EMI calculation
- **Modern UI/UX**: Clean design with smooth animations
- **Fast Performance**: Optimized assets and code for quick loading
- **SEO Optimized**: Structured for better search engine visibility

## Technologies Used

- HTML5
- CSS3 (with CSS Variables for theming)
- Vanilla JavaScript (ES6+)
- Google Fonts (Poppins & Inter)
- Font Awesome Icons

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.)

### Installation

1. Clone the repository:
   ```bash
   git clone [repository-url]
   ```

2. Open the project folder:
   ```bash
   cd loan-website
   ```

3. Open `index.html` in your browser:
   - Double-click the file, or
   - Use a local server (e.g., Live Server in VS Code)

## Project Structure

```
loan-website/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # Main stylesheet
├── js/
│   └── script.js       # Main JavaScript file
└── README.md           # Project documentation
```

## Customization

### Colors

Primary colors can be customized by updating the CSS variables in `css/style.css`:

```css
:root {
    --primary-color: #0F52BA;
    --primary-dark: #003366;
    --secondary-color: #FF8C00;
    --accent-color: #FFD700;
    --text-dark: #333333;
    --text-light: #666666;
    --light-bg: #F5F7FA;
    --white: #FFFFFF;
}
```

### Fonts

Fonts are loaded from Google Fonts. To change them, update the link in `index.html` and the corresponding font-family in `style.css`.

## Features in Detail

### Loan Calculator

The interactive EMI calculator allows users to:
- Adjust loan amount using a slider
- Modify interest rates
- Change loan tenure
- See real-time EMI updates

### Responsive Navigation

- Mobile-friendly hamburger menu
- Smooth scrolling to sections
- Sticky header on scroll

### Performance Optimizations

- Minified assets
- Lazy loading for images
- Optimized animations

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS/Android)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Google Fonts](https://fonts.google.com/)
- [Font Awesome](https://fontawesome.com/)
- [Unsplash](https://unsplash.com/) for placeholder images