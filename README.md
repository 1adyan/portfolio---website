# portfolio---website
Personal Portfolio Website - HTML5 &amp; CSS3|

# Project Overview
This is a personal portfolio website created using HTML5 and CSS3 as part of my web development coursework. The site showcases my projects, provides information about me, and includes a contact form.

# Color Scheme
I used Adobe Color to create a harmonious color scheme based on professional web design principles.

**Selected Colors:**
- Primary: #2C3E50 (Dark Blue-Grey)
- Secondary: #3498DB (Bright Blue)
- Accent: #E74C3C (Red)
- Light: #ECF0F1 (Light Grey)
- Dark: #34495E (Dark Grey)

**Scheme Type:** Complementary color scheme
**Rationale:** This scheme provides good contrast for readability while maintaining a professional appearance suitable for a portfolio site.

## Viewport Dimensions

### Full-Size (Desktop/Laptop)
- **Min-width:** 960px
- **Rationale:** Standard desktop viewport as per course materials. This width works well on most laptop and desktop monitors and is easily divisible for column layouts.

### Tablet
- **Min-width:** 481px and Max-width: 960px
- **Rationale:** Covers most tablet devices in both portrait and landscape orientations. This range accommodates iPads and Android tablets.

### Mobile (Smartphone)
- **Max-width:** 480px
- **Rationale:** Targets smartphone devices. This ensures the site is fully responsive on smaller screens with appropriate single-column layouts.

## Gradient Usage

### Linear Gradient
- **Location:** Header section (all pages)
- **Implementation:** Top-to-bottom gradient from dark to light primary colors
- **Code:** Applied in `style-full.css` to the `header` element

### Angle Linear Gradient
- **Location:** Project cards on Projects page
- **Implementation:** 45-degree diagonal gradient for visual interest
- **Code:** Applied in `style-full.css` to the `.project-card` class

## Form Validation
The contact form includes HTML5 validation:
- **Email field:** Uses `type="email"` for email format validation
- **Phone field:** Uses `type="tel"` with pattern attribute for phone number format
- **Required fields:** Name, Email, and Message are marked as required
- **Comments field:** Textarea with character limit guidance

## Semantic HTML5 Tags Used
- `<header>` - Page headers with navigation
- `<nav>` - Navigation menus
- `<main>` - Main content area
- `<article>` - Project descriptions
- `<section>` - Content sections
- `<aside>` - Sidebar content on About page
- `<footer>` - Page footers
- `<figure>` and `<figcaption>` - Images with captions

## Technologies Used
- HTML5
- CSS3
- No JavaScript frameworks
- No Flexbox (per assignment requirements)

## Testing & Validation

All pages have been validated using:
- W3C Markup Validation Service (HTML)
- W3C CSS Validation Service (CSS)
- W3C Link Checker
- WAVE Web Accessibility Evaluation Tool

## Live Site
[View Live Portfolio](https://YOUR-USERNAME.github.io/portfolio---website/)

## Repository
[GitHub Repository](https://github.com/YOUR-USERNAME/portfolio---website)

## Author
Adyan Iqbal
100963100
