# Responsive Bootstrap Landing Page Template

This is a responsive landing page template built with Bootstrap 5, designed as a versatile starting point for various web projects. The template features multiple sections including a navigation bar, hero section, about us, feature cards, counters, services, pricing tables, a contact form, and a footer. It incorporates modern web design practices with animations and a custom Persian font, making it particularly suitable for Persian-speaking audiences, though it can be adapted for any language.

## Features

- **Responsive Design**: Fully responsive layout using Bootstrap 5, optimized for all screen sizes.
- **Navigation Bar**: Includes a dropdown menu and changes color on scroll for enhanced usability.
- **Hero Section**: Eye-catching introduction with a call-to-action button and background image.
- **About Us Section**: Combines text and imagery to present information effectively.
- **Details Section**: Feature cards with images and descriptions for showcasing content.
- **Counters Section**: Animated statistics display using PureCounter.
- **Features Section**: Highlights key aspects with icons and detailed descriptions.
- **Services Section**: Interactive boxes with hover effects and customizable styling.
- **Pricing Tables**: Four distinct pricing plans with hover animations.
- **Contact Form**: Form layout ready for backend integration (currently set to `#`).
- **Footer**: Includes social links, navigation, and author credits.
- **Animations**: Smooth scroll animations powered by AOS (Animate On Scroll).
- **Custom Font**: Uses the Persian "Vazir" font for a localized experience.

## Technologies Used

- **HTML5**: Semantic markup for structure.
- **CSS3**: Custom styles in `main.css` with transitions and hover effects.
- **[Bootstrap 5.3.3](https://getbootstrap.com/)**: Framework for responsive design and components.
- **[Bootstrap Icons 1.11.3](https://icons.getbootstrap.com/)**: Icon library for visual elements.
- **[AOS (Animate On Scroll)](https://michalsnik.github.io/aos/)**: Library for scroll-based animations.
- **[Alpine.js 3.14.0](https://alpinejs.dev/)**: Lightweight JavaScript for dynamic header behavior.
- **[PureCounter](https://github.com/srexi/purecounterjs)**: JavaScript library for animated counters.
- **Font**: [Vazir](https://github.com/rastikerdar/vazir-font) (Persian typeface).

## Installation

To set up the project locally:

1. **Clone or Download**:  
   Clone the repository using `git clone <repository-url>` or download the ZIP file from GitHub.
2. **Open the Project**:  
   Navigate to the project directory and open `index.html` in a web browser.

**Note**: The template relies on CDN links for Bootstrap, Bootstrap Icons, AOS, Alpine.js, and PureCounter. An internet connection is required to load these resources. For offline use, download the libraries and update the file paths in `index.html` to reference local copies.

## Usage

- Open `index.html` in a web browser to view the landing page.
- Scroll through the sections to experience the animations and interact with the navigation bar.
- The contact form is a placeholder; it requires a backend setup to process submissions.

## Customization

Customize the template to suit your needs:

- **Content**: Edit text within HTML elements to update the content (currently in Persian).
- **Styles**: Modify `main.css` to adjust colors, layouts, or add new styles. Leverage Bootstrap classes for additional styling.
- **Sections**: Add, remove, or rearrange sections by editing the HTML structure.
- **Images**: Replace placeholder images in the `images` folder with your own (e.g., `intro-img.png`, `about.jpg`).
- **Contact Form**: Update the `action` attribute in the `<form>` tag to point to a backend script for form handling.
- **Email Addresses**: Replace obfuscated email placeholders in the contact section with actual addresses (currently protected by Cloudflare).
- **Animations**: Adjust AOS effects by modifying `data-aos` attributes (e.g., `fade-up`, `zoom-in`). See the [AOS documentation](https://michalsnik.github.io/aos/) for options.
- **Counters**: Change the `data-purecounter-start` and `data-purecounter-end` values in the counters section to display different statistics.
- **Language**: Translate the Persian content to any language by updating the text in `index.html`.

For advanced customization, refer to the [Bootstrap documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/) for available classes and components.

## Credits

- **Libraries**:
  - [Bootstrap](https://getbootstrap.com/)
  - [Bootstrap Icons](https://icons.getbootstrap.com/)
  - [AOS](https://michalsnik.github.io/aos/)
  - [Alpine.js](https://alpinejs.dev/)
  - [PureCounter](https://github.com/srexi/purecounterjs)
- **Font**: [Vazir](https://github.com/rastikerdar/vazir-font)
- **Author**: Zaniar Karimi

## License

This project is licensed under the MIT License. See below for details:

---

**MIT License**

Copyright (c) 2023 Zaniar Karimi

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---
