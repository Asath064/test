# Neon Portfolio Website

A modern, futuristic personal portfolio website featuring a neon-themed UI on a dark background. Built with pure HTML, CSS, and JavaScript.

## Features

### Visual Design
- **Dark Theme**: Deep navy/black background for a sleek, modern look
- **Neon Accents**: Cyan, electric blue, neon purple, and neon green colors
- **Glowing Effects**: Soft glows on borders, buttons, and headings
- **Smooth Animations**: Hover effects, transitions, and subtle animations
- **Clean Typography**: Using Orbitron and Rajdhani fonts for a tech-focused aesthetic

### Sections

1. **Hero Section**
   - Full-screen introduction
   - Name with neon glow effect
   - Professional tagline
   - Call-to-action buttons
   - Animated scroll indicator

2. **About Me**
   - Personal background and interests
   - Icon cards with neon outlines
   - Clean, readable layout

3. **Skills**
   - Organized by categories (Programming, Electronics, Tools)
   - Interactive skill cards with hover effects
   - Neon-bordered cards

4. **Projects**
   - Card-based layout
   - Hover effects with neon glow
   - Tech stack tags
   - Project descriptions

5. **Achievements & Certifications**
   - Timeline layout
   - Neon gradient separator line
   - Organized chronologically

6. **Contact**
   - Interactive contact form
   - Neon-outlined input fields
   - Social media links with glow effects
   - Form submission with feedback

### Interactive Features
- Responsive navigation with mobile hamburger menu
- Smooth scrolling between sections
- Intersection observer for section animations
- Parallax effect on hero decorations
- Custom cursor glow effect (desktop only)
- Active navigation state tracking
- Form validation and submission feedback

## Responsive Design

Fully responsive across all devices:
- **Desktop**: Full feature set with advanced effects
- **Tablet**: Optimized layout with touch-friendly interactions
- **Mobile**: Hamburger menu, stacked layouts, optimized spacing

Breakpoints:
- 968px: Mobile navigation
- 768px: Tablet adjustments
- 480px: Mobile optimizations

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Grid, Flexbox, animations
- **JavaScript**: ES6+, Intersection Observer API, DOM manipulation
- **Google Fonts**: Orbitron & Rajdhani

## Performance Optimizations

- Smooth scrolling with `scroll-behavior: smooth`
- CSS transitions for performance
- Intersection Observer for lazy animations
- Reduced motion support for accessibility
- Optimized asset loading

## Accessibility

- Semantic HTML structure
- ARIA labels where needed
- Keyboard navigation support
- Reduced motion preferences respected
- High contrast neon colors for readability

## Browser Support

Compatible with all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## Getting Started

1. Clone the repository
2. Open `index.html` in your browser
3. Customize the content in `index.html`
4. Adjust colors and styles in `styles.css`
5. Modify interactions in `script.js`

## Customization

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --neon-cyan: #00ffff;
    --neon-blue: #0066ff;
    --neon-purple: #cc00ff;
    --neon-green: #00ff88;
}
```

### Content
Update sections in `index.html`:
- Change name and tagline in hero section
- Update about text
- Modify skills list
- Add/remove projects
- Update achievements
- Change contact information

### Fonts
Replace Google Fonts in `index.html` and update CSS variables:
```css
--font-heading: 'Orbitron', sans-serif;
--font-body: 'Rajdhani', sans-serif;
```

## License

This project is open source and available for personal and commercial use.

## Credits

Designed and developed with a focus on modern web standards and futuristic aesthetics.

---

**Note**: Remember to update the personal information, project links, and social media URLs with your own content before deploying.
