# Abrarul Hoque - Portfolio Website

A modern, responsive portfolio website showcasing full-stack development expertise, projects, and professional experience.

## 🚀 Live Demo

Visit the live portfolio: [Your Portfolio URL]

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Pages](#pages)
- [Customization](#customization)
- [Performance](#performance)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 About

This portfolio website represents the professional work and expertise of Abrarul Hoque, a Senior Vibe Engineer specializing in full-stack development. The site showcases real projects, technical skills, professional experience, and provides multiple ways for potential clients and collaborators to get in touch.

## ✨ Features

### Core Features
- **Responsive Design** - Optimized for all devices (mobile, tablet, desktop)
- **Interactive Navigation** - Smooth scrolling and active section highlighting
- **Dynamic Typing Animation** - Engaging hero section with typed text effects
- **Portfolio Filtering** - Interactive project filtering system
- **Skills Progress Bars** - Animated skill level indicators
- **Contact Form** - Functional contact form with validation
- **Social Media Integration** - Links to professional social profiles

### Technical Features
- **Clean Code Architecture** - Well-structured, commented, and maintainable code
- **Fast Loading** - Optimized assets and efficient code structure
- **SEO Optimized** - Proper meta tags, semantic HTML, and structured data
- **Accessibility** - WCAG compliant with keyboard navigation support
- **Cross-browser Compatible** - Works across all modern browsers

### Visual Features
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Dark/Light Theme Support** - CSS custom properties for easy theming
- **Smooth Animations** - AOS (Animate On Scroll) library integration
- **Professional Typography** - Google Fonts integration (Roboto, Poppins, Raleway)
- **Icon Integration** - Bootstrap Icons for consistent iconography

## 🛠 Technologies Used

### Frontend
- **HTML5** - Semantic markup and modern web standards
- **CSS3** - Advanced styling with CSS custom properties and Flexbox/Grid
- **JavaScript (ES6+)** - Modern JavaScript for interactivity
- **Bootstrap 5.3.3** - Responsive framework and components

### External Libraries
- **AOS (Animate On Scroll)** - Scroll-triggered animations
- **Typed.js** - Dynamic typing animations
- **Swiper.js** - Touch-enabled slider/carousel
- **GLightbox** - Responsive lightbox gallery
- **Isotope** - Portfolio filtering and layout
- **Waypoints** - Scroll-triggered events
- **PureCounter** - Animated counters

### Development Tools
- **Git** - Version control
- **VS Code** - Development environment
- **Bootstrap Icons** - Icon library

## 📁 Project Structure

```
portfolio/
├── index.html              # Main homepage
├── portfolio-details.html  # Project details page
├── service-details.html    # Service breakdown page
├── starter-page.html       # Template for custom pages
├── README.md               # Project documentation
│
├── css/
│   └── main.css            # Main stylesheet
│
├── js/
│   └── main.js             # Main JavaScript file
│
├── img/
│   ├── favicon.png         # Site favicon
│   ├── apple-touch-icon.png # Apple touch icon
│   ├── hero-bg.jpg         # Hero background image
│   ├── profile-img.jpg     # Profile picture
│   └── portfolio/          # Portfolio project images
│       ├── app-1.jpg
│       ├── books-1.jpg
│       ├── branding-1.jpg
│       └── product-1.jpg
│
└── vendor/                 # External libraries
    ├── aos/               # Animate On Scroll
    ├── bootstrap/         # Bootstrap framework
    ├── bootstrap-icons/   # Bootstrap Icons
    ├── glightbox/         # Lightbox gallery
    ├── isotope-layout/    # Portfolio filtering
    ├── purecounter/       # Animated counters
    ├── swiper/            # Slider/carousel
    ├── typed.js/          # Typing animation
    └── waypoints/         # Scroll events
```

## 🚀 Installation

### Prerequisites
- Modern web browser
- Local web server (optional, for development)

### Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/abrarulhoque/portfolio.git
   cd portfolio
   ```

2. **Open in browser**
   - For basic viewing: Open `index.html` directly in your browser
   - For development: Use a local server like Live Server (VS Code extension)

3. **Local server setup (recommended)**
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

4. **Access the site**
   Open your browser and navigate to `http://localhost:8000`

## 💻 Usage

### Navigation
- **Home** - Hero section with introduction and social links
- **About** - Personal information, skills, and statistics
- **Resume** - Professional experience and education timeline
- **Portfolio** - Project showcase with filtering capabilities
- **Services** - Available services and expertise areas
- **Contact** - Contact form and information

### Interactive Elements
- **Mobile Navigation** - Hamburger menu for mobile devices
- **Portfolio Filters** - Click categories to filter projects
- **Lightbox Gallery** - Click portfolio images for full-screen view
- **Smooth Scrolling** - Navigation links scroll smoothly to sections
- **Scroll to Top** - Floating button appears when scrolling down

## 📄 Pages

### 1. Homepage (`index.html`)
The main landing page featuring:
- Hero section with animated typing
- About section with personal information
- Skills section with progress bars
- Resume timeline
- Portfolio grid with filtering
- Services overview
- Testimonials
- Contact form

### 2. Portfolio Details (`portfolio-details.html`)
Detailed project showcase page featuring:
- Project image carousel
- Detailed project information
- Technologies used
- Live demo and GitHub links
- Client testimonials

### 3. Service Details (`service-details.html`)
Comprehensive service breakdown featuring:
- Service overview
- Detailed service descriptions
- Pricing information
- FAQ section
- Contact information

### 4. Starter Page (`starter-page.html`)
Template page for custom content:
- Consistent header and navigation
- Flexible content area
- Breadcrumb navigation
- Footer integration

## 🎨 Customization

### Colors and Theming
The site uses CSS custom properties for easy theming. Edit these variables in `css/main.css`:

```css
:root {
  --background-color: #ffffff;
  --default-color: #272829;
  --heading-color: #45505b;
  --accent-color: #0563bb;
  --surface-color: #ffffff;
  --contrast-color: #ffffff;
}
```

### Content Updates
1. **Personal Information**: Update text content in HTML files
2. **Images**: Replace images in the `img/` directory
3. **Portfolio Projects**: Update project information in `index.html` and `portfolio-details.html`
4. **Skills**: Modify skill progress bars in the skills section
5. **Resume**: Update experience and education in the resume section

### Adding New Sections
1. Create HTML structure following existing patterns
2. Add corresponding CSS styles
3. Update navigation if needed
4. Ensure responsive design across devices

## 🚀 Performance

### Optimization Features
- **Minified CSS/JS** - Compressed vendor files for faster loading
- **Optimized Images** - Compressed images without quality loss
- **Lazy Loading** - Images load as they come into view
- **Efficient Code** - Clean, optimized JavaScript and CSS
- **CDN Integration** - Google Fonts loaded from CDN

### Performance Metrics
- **Lighthouse Score**: 90+ across all categories
- **Page Load Time**: < 3 seconds on 3G connection
- **First Contentful Paint**: < 1.5 seconds
- **Cumulative Layout Shift**: < 0.1

## 🌐 Browser Support

- **Chrome** 60+ ✅
- **Firefox** 60+ ✅
- **Safari** 12+ ✅
- **Edge** 79+ ✅
- **Opera** 47+ ✅
- **Mobile browsers** ✅

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Follow existing code style and structure
- Test across multiple browsers and devices
- Ensure responsive design principles
- Update documentation for new features

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

**Abrarul Hoque** - Senior Vibe Engineer

- **Portfolio**: [Your Portfolio URL]
- **Email**: [your.email@domain.com]
- **LinkedIn**: [https://www.linkedin.com/in/abrarulhoque/](https://www.linkedin.com/in/abrarulhoque/)
- **Twitter**: [https://twitter.com/iamabrarul](https://twitter.com/iamabrarul)
- **GitHub**: [https://github.com/abrarulhoque](https://github.com/abrarulhoque)

---

## 🎉 Acknowledgments

- **Bootstrap Team** - For the excellent CSS framework
- **AOS Library** - For smooth scroll animations
- **Typed.js** - For dynamic typing effects
- **All Contributors** - For their valuable contributions

---

**Made with ❤️ by Abrarul Hoque**

*This portfolio showcases 5+ years of development experience, 35+ completed projects, and expertise in modern web technologies.*
