# M@sud's English Academy Website

A high-energy, mobile-responsive website built with HTML, CSS, and JavaScript for M@sud's English Academy - Sherpur Branch.

## Features

### 🎨 Design & Animations
- **Vibrant Gradients**: Linear gradients (blue to red) for headers and buttons
- **Bouncing Animations**: Continuous bouncing effect on hero text and section headings
- **Hover Effects**: Interactive cards with transform and shadow animations
- **Smooth Transitions**: All interactive elements have smooth transitions

### 📱 Navigation
- **Sticky Navbar**: Fixed navigation with shadow effects on scroll
- **Three-Dot Menu**: Mobile-friendly kebab menu that slides in from the right
- **Smooth Scrolling**: Seamless navigation between sections
- **Active Link Highlighting**: Current section is highlighted in navigation

### 🏠 Content Sections

#### Hero Section
- Bouncing "M@sud's English Academy" title
- Sub-headline with branch information
- Professional CEO image placeholder
- Call-to-action buttons

#### Courses Section
- **Kid's English**: Nursery to Class 5 (Pink-Purple gradient)
- **Junior English**: Class 6 to Class 9 (Blue-Indigo gradient)  
- **Spoken English**: Professional batch (Green-Teal gradient)
- Interactive hover effects with scale and shadow transforms

#### Mentors Section
- Featured profile of Masudur Rahman (CEO & Founder)
- Professional bio and experience badges
- Circular profile image with border

#### Feedback Section
- **Testimonial Slider**: Auto-rotating every 5 seconds
- Manual navigation with arrow buttons
- Keyboard navigation support (arrow keys)
- Touch/swipe support for mobile devices
- Star ratings and student/parent reviews

#### Contact Section
- Phone numbers: 01813-333 573, 01861-678 922
- Full address with location details
- Embedded Google Maps iframe
- Office hours information

### 💬 Social Integration
- **Facebook Messenger Button**: Floating button with bounce animation
- Links to social media profiles in footer

## Technologies Used

- **HTML5**: Semantic markup and structure
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **JavaScript**: Vanilla JS for interactivity
- **Font Awesome**: Icons for UI elements
- **Google Maps**: Embedded location map

## File Structure

```
c:\education\
├── index.html          # Main HTML file
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## How to View

1. Open `index.html` in any modern web browser
2. The website is fully responsive and works on all devices
3. No server required - runs entirely in the browser

## Customization

### Images
Replace placeholder images with actual photos:
- CEO image: Update `src` attribute in hero and mentors sections
- Student/parent images: Update `src` in testimonial slides

### Colors
Modify gradients in the `<style>` section of `index.html`:
```css
.gradient-bg-blue-red {
    background: linear-gradient(135deg, #2563eb 0%, #dc2626 100%);
}
```

### Contact Information
Update contact details in the contact section:
- Phone numbers
- Address
- Facebook Messenger link
- Google Maps coordinates

### Testimonials
Add or modify testimonials in the feedback section:
- Student/parent names
- Review text
- Ratings

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- **Optimized Animations**: CSS transforms for smooth 60fps animations
- **Lazy Loading**: Images load as needed
- **Intersection Observer**: Efficient scroll-based animations
- **Touch Optimized**: Mobile-friendly interactions

## Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px  
- **Desktop**: > 1024px

## License

© 2024 M@sud's English Academy. All rights reserved.
