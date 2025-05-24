# Front-end Bootcamp Landing Page

A modern, responsive landing page for a web development bootcamp built with Bootstrap 5. This project showcases a professional educational website with interactive features, responsive design, and user-friendly interface.

## Features

- **Responsive Design**: Fully responsive layout that works on all device sizes
- **Modern UI/UX**: Clean, professional design using Bootstrap 5 components
- **Interactive Navigation**: Smooth scrolling navigation with collapsible mobile menu
- **Hero Section**: Engaging landing area with call-to-action button
- **Newsletter Signup**: Email subscription form with validation
- **Service Cards**: Three learning format options (Virtual, Hybrid, In Person)
- **FAQ Section**: Expandable accordion for frequently asked questions
- **Instructor Profiles**: Team showcase with social media links
- **Interactive Map**: Leaflet.js integration showing location
- **Enrollment Modal**: Registration form with validation
- **Contact Information**: Complete contact details with accessibility features

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with Bootstrap integration
- **Bootstrap 5.0.2**: Responsive framework and components
- **Bootstrap Icons 1.7.2**: Icon library for enhanced UI
- **Leaflet 1.9.4**: Interactive maps functionality
- **JavaScript**: Map initialization

## CDN Dependencies

The project uses the following external CDN resources:

- Bootstrap CSS & JS Bundle
- Bootstrap Icons
- Leaflet CSS & JS
- OpenStreetMap tiles for mapping

## Project Structure

```
markup-page/
├── index.html          # Main HTML file
├── style.css           # Custom CSS styles
├── img/                # Image assets
│   ├── showcase.svg    # Hero section illustration
│   ├── fundamentals.svg # Learning section illustration
│   └── react.svg       # React section illustration
└── README.md           # Project documentation
```

## Getting Started

### Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd markup-page
   ```

2. **Open the project:**

   - Option 1: Open `index.html` directly in your browser
   - Option 2: Use a local server for development:

     ```bash
     # Using Python
     python -m http.server 8000

     # Using Node.js (if you have live-server installed)
     npx live-server

     # Using PHP
     php -S localhost:8000
     ```

3. **Access the website:**
   - Direct file: Open `index.html` in your browser
   - Local server: Navigate to `http://localhost:8000`

## Development

### Adding New Sections

1. Create new HTML section in `index.html`
2. Add corresponding navigation link
3. Style with custom CSS if needed
4. Test responsiveness across devices

### Form Handling

The enrollment form includes:

- Client-side validation
- Accessibility attributes
- Bootstrap validation classes
- Pattern matching for inputs

To add backend functionality, integrate with your preferred server-side technology.

## SEO & Accessibility

- Semantic HTML structure
- ARIA labels and roles
- Alt text for images
- Proper heading hierarchy
- Form accessibility
- Screen reader friendly
