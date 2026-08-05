# 🚀 MANOHAR's Portfolio Website

A modern, clean, and responsive portfolio website built with HTML, CSS, and JavaScript.

## 📋 Features

- ✨ Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Smooth animations and transitions
- 🔗 Sticky navigation bar
- 📦 No dependencies required (vanilla HTML/CSS/JS)
- ⚡ Fast and lightweight
- 🎛️ Easy to customize

## 📁 Project Structure

```
portfolio/
├── index.html      # Main HTML file with all sections
├── styles.css      # All styling and responsive design
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## 🎨 Customization Guide

### 1. **Basic Information**
Open `index.html` and update:
- Name in the hero section (already set to "MANOHAR")
- College/University name
- Your bio and description

### 2. **Skills Section**
Edit the skills categories and tags:
- Add or remove skill categories (Frontend, Backend, Tools, etc.)
- Update skill tags with your actual skills
- Current skills are placeholders - replace with yours

### 3. **Projects**
Update the three project cards:
- **Project Title**: Change "Project One", "Project Two", etc.
- **Description**: Write a meaningful description
- **Technologies**: Update the tech stack tags
- **Links**: Replace `#` with actual GitHub repo and live demo links

Example:
```html
<div class="project-card">
    <div class="project-image" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);"></div>
    <div class="project-content">
        <h3>My Awesome Project</h3>
        <p>A full-stack e-commerce application built with React and Node.js...</p>
        <div class="project-tags">
            <span>React</span>
            <span>Node.js</span>
            <span>MongoDB</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/yourname/project" class="project-link">View Code</a>
            <a href="https://your-project-link.com" class="project-link">Live Demo</a>
        </div>
    </div>
</div>
```

### 4. **Education**
Update your degree information:
- Program name
- University/College name
- Year/Status (Currently Pursuing, 2023-2024, etc.)

### 5. **Contact Links**
Replace placeholder links with your actual social profiles:
- GitHub: `https://github.com/yourusername`
- LinkedIn: `https://linkedin.com/in/yourprofile`
- Email: `mailto:your.email@example.com`
- Twitter: `https://twitter.com/yourhandle`

### 6. **Colors (Optional)**
Change the color scheme in `styles.css`:
```css
:root {
    --primary-color: #667eea;      /* Main purple */
    --secondary-color: #764ba2;    /* Darker purple */
    --text-dark: #2d3748;          /* Dark text */
    --text-light: #718096;         /* Light text */
    --bg-light: #f7fafc;           /* Light background */
    --bg-white: #ffffff;           /* White background */
}
```

## 🚀 How to Use

### Option 1: Local File
1. Save the three files (`index.html`, `styles.css`, `script.js`) in a folder
2. Open `index.html` in your web browser
3. The website will load locally

### Option 2: Deploy Online (Free Options)
**Netlify:**
1. Drag & drop your folder to Netlify.com
2. Get a live URL instantly

**GitHub Pages:**
1. Create a GitHub repository
2. Push the files
3. Go to Settings → Pages
4. Deploy from main branch
5. Your site will be live at `yourusername.github.io/repository-name`

**Vercel:**
1. Sign up at vercel.com
2. Import your GitHub repository
3. Deploy with one click

## 📝 Sections Included

1. **Navigation** - Sticky navbar with smooth scrolling
2. **Hero Section** - Eye-catching introduction
3. **About** - Brief bio about yourself
4. **Skills** - Organized by category (Frontend, Backend, Tools, Business)
5. **Projects** - Showcase your best work (3 sample projects included)
6. **Education** - Your academic background
7. **Contact** - Social links and contact methods
8. **Footer** - Copyright information

## 🔧 Responsive Design

The portfolio is fully responsive and looks great on:
- 📱 Mobile phones (320px and up)
- 📱 Tablets (768px and up)
- 💻 Desktops (1200px and up)

## ✅ Customization Checklist

- [ ] Update your name/logo
- [ ] Update about me section
- [ ] Update skills with your actual skills
- [ ] Add/update 3 projects with real descriptions and links
- [ ] Update education information
- [ ] Add your social media links
- [ ] Change colors if desired
- [ ] Test on mobile devices
- [ ] Deploy to the web

## 📞 Need Help?

To add more sections or features, you can:
1. Follow the existing pattern in the HTML
2. Add new styles to `styles.css`
3. Use similar structure and naming conventions

Common additions:
- **Blog Section**: Copy the projects grid structure
- **Experience Section**: Similar to education structure
- **Testimonials**: Can use the project card structure
- **Contact Form**: Add a form in the contact section

## 🎓 Learning Notes

This portfolio uses:
- **Semantic HTML5** for proper structure
- **CSS Grid & Flexbox** for responsive layouts
- **CSS Variables** for easy customization
- **Vanilla JavaScript** for interactivity
- **Font Awesome Icons** for social links
- **Google Fonts** (optional - already in CSS)

## 📄 License

Feel free to use this template for your own portfolio. No attribution needed!

---

**Good luck with your portfolio! 🚀**

Remember to update your information before sharing with others.
