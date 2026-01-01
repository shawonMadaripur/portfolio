# Django Backend Developer Portfolio

A professional, modern portfolio website for showcasing your Django backend development skills and projects.

## 📁 Project Structure

```
shawon/
├── index.html          # Main HTML file
├── style.css           # Professional styling
├── script.js           # Interactive functionality
├── assets/
│   └── profile.jpg     # Your professional photo (ADD YOUR PHOTO HERE)
└── README.md           # This file
```

## 🖼️ How to Add Your Professional Photo

1. **Save your photo in the assets folder:**
   - Place your professional photo in: `assets/profile.jpg`
   - Recommended dimensions: 350x400px or similar portrait ratio
   - Supported formats: JPG, PNG, WebP
   - Keep file size under 200KB for optimal performance

2. **The photo will automatically appear:**
   - In the hero section on the right side
   - With a professional gold border
   - With a smooth hover effect
   - Responsive on all devices

## ✨ Features

### Professional Design
- **Color Scheme:** Dark blue & gold (professional enterprise colors)
- **Typography:** Modern sans-serif fonts
- **Responsive:** Works perfectly on mobile, tablet, and desktop
- **Animations:** Smooth transitions and hover effects

### Sections Included
- 🏠 **Hero** - Introduction with your professional photo
- 👤 **About** - Your professional summary with statistics
- 💼 **Skills** - Organized skill categories
- 🎯 **Projects** - Featured project showcase (6 projects)
- 📝 **Experience** - Professional timeline
- 📧 **Contact** - Contact form and social links
- 🔗 **Footer** - Professional footer

## 🎨 Customization Guide

### Update Personal Information

**In index.html:**
- Replace "Shawon" with your name
- Update contact email: `shawon@example.com`
- Update phone: `+1 (234) 567-8900`
- Update location: `San Francisco, CA`
- Update social links in the contact section

### Customize About Section
- Update the about text to reflect your experience
- Modify statistics (Years Experience, Projects, Clients)

### Update Skills
Change the skill categories and badges in the skills section:
```html
<div class="skill-category">
    <h3>Your Category</h3>
    <ul>
        <li><span class="badge">Your Skill</span></li>
    </ul>
</div>
```

### Add Your Projects
Replace the featured projects with your actual projects:
```html
<div class="project-card">
    <div class="project-header">
        <i class="fas fa-icon-name"></i>
    </div>
    <h3>Your Project Title</h3>
    <p class="project-description">Your project description</p>
    <div class="project-tags">
        <span class="tag">Technology1</span>
        <span class="tag">Technology2</span>
    </div>
    <a href="#" class="project-link">View Project <i class="fas fa-arrow-right"></i></a>
</div>
```

### Update Experience
Modify the timeline items in the experience section with your actual work history.

## 🎯 Color Reference

- **Primary Dark Blue:** #1a3a52
- **Gold Accent:** #d4a574
- **Medium Blue:** #2d5a7b
- **Dark Background:** #0f1923
- **Light Text:** #e8eef5
- **Gray:** #6b7280

## 🚀 How to Deploy

### Local Testing
Simply open `index.html` in your web browser to view the portfolio.

### Online Hosting Options
1. **GitHub Pages** - Free hosting
2. **Netlify** - Easy deployment from GitHub
3. **Vercel** - Optimized for web projects
4. **Your Own Server** - Full control

## 📱 Browser Support

- Chrome/Edge (Latest)
- Firefox (Latest)
- Safari (Latest)
- Mobile browsers

## ♿ Accessibility

- Semantic HTML structure
- Proper color contrast ratios
- Keyboard navigation support
- ARIA labels where needed

## 📦 Dependencies

- Font Awesome Icons (CDN) - For icons
- No other external dependencies

## 💡 Pro Tips

1. **Photo Quality:** Use a high-quality, professional photo
2. **Professional Tone:** Maintain consistent professional messaging throughout
3. **Keep Updated:** Regularly update projects and experience
4. **Mobile First:** Test on mobile devices for optimal display
5. **SEO:** Update meta tags with your information

## 🔧 Customizing Colors

To change the color scheme globally, edit the CSS variables in `style.css`:

```css
:root {
    --primary: #1a3a52;      /* Change primary color */
    --secondary: #d4a574;    /* Change accent color */
    --accent: #2d5a7b;       /* Change accent shade */
    --dark-bg: #0f1923;      /* Change background */
    --light-text: #e8eef5;   /* Change text color */
    --gray: #6b7280;         /* Change secondary text */
    --border: #2d3e5f;       /* Change border color */
}
```

## 📞 Need Help?

This portfolio template is fully customizable and professional. Make sure to:
- Update all contact information
- Add your real projects and experience
- Use a professional photo
- Test on multiple devices

---

**Created:** January 2026
**Type:** Professional Portfolio
**Specialization:** Django Backend Developer