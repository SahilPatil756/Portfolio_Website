# Sahil Patil - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience in AI, Full-Stack Development, and Cloud Computing.

## 🚀 Live Demo

[Visit Portfolio Website](https://your-portfolio-link.com) 

## ✨ Features

- **Modern Design**: Clean, dark-themed UI with gradient accents
- **Responsive**: Fully responsive across all devices
- **Interactive Elements**: 
  - Three.js particle background animation
  - Smooth scrolling navigation
  - Animated skill tags and project cards
  - Testimonial slider
- **Contact Form**: Real-time email integration using EmailJS
- **Performance Optimized**: Fast loading times with optimized assets

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox, Animations
- **JavaScript** - ES6+ features, DOM manipulation
- **Three.js** - 3D background animations
- **Font Awesome** - Icons

### Backend Services
- **EmailJS** - Contact form email service

## 📁 Project Structure

```
portfolio-website/
│
├── index.html                 # Main HTML file
├── assets/                    # Static assets
│   ├── images/               # Project images and icons
│   ├── css/                  # CSS files (if separated)
│   └── js/                   # JavaScript files (if separated)
├── README.md                 # Project documentation
└── .gitignore               # Git ignore file
```

## 🎯 Sections

1. **Hero** - Introduction with call-to-action buttons
2. **About** - Personal information and skills
3. **Projects** - Portfolio projects with descriptions and links
4. **Experience** - Work experience and certifications timeline
5. **Testimonials** - Client and colleague feedback
6. **Contact** - Contact form and social links

## 📧 Email Configuration

The contact form uses EmailJS to send emails directly to your inbox:

1. **Sign up** for [EmailJS](https://www.emailjs.com/)
2. **Add Email Service** (Gmail/Outlook)
3. **Create Email Template** with variables:
   - `{{name}}` - Sender's name
   - `{{email}}` - Sender's email
   - `{{subject}}` - Email subject
   - `{{message}}` - Email content
4. **Update credentials** in the JavaScript code

## 🎨 Color Scheme

```css
:root {
  --primary: #6C63FF;     /* Purple */
  --secondary: #00D4AA;   /* Teal */
  --accent: #FF6B8B;      /* Pink */
  --background: #0F0F1E;  /* Dark blue */
  --surface: #1A1A2E;     /* Lighter dark blue */
  --text: #E2E8F0;        /* Light gray */
}
```

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 992px
- **Desktop**: > 992px

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
