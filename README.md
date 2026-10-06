# Segawa Abdul - Portfolio Website

This is a personal portfolio website hosted on GitHub Pages, showcasing my work, skills, and projects.

## 🌐 Live Website
Visit the portfolio at: [https://snowden-7.github.io/](https://snowden-7.github.io/)

## 📋 Features
- **About Section**: Introduction and professional background
- **Skills Display**: Visual representation of technical skills
- **Projects Showcase**: Grid layout for displaying projects with descriptions
- **Contact Links**: Direct links to LinkedIn and GitHub profiles
- **Responsive Design**: Optimized for both desktop and mobile devices
- **Modern UI**: Gradient backgrounds and smooth animations

## 🔄 How to Update Your Portfolio

### Updating About Section
1. Open `index.html`
2. Find the `<section id="about">` section
3. Edit the text within the `<p>` tags to update your bio
4. Modify the skills by adding/removing `<span class="skill-tag">` elements

### Adding New Projects
1. Open `index.html`
2. Find the `<div class="projects-grid">` section
3. Copy an existing `<div class="project-card">` block
4. Update the project title, description, and technology badges
5. Paste it within the projects-grid div

Example project card structure:
```html
<div class="project-card">
    <h3>Project Name</h3>
    <p>Project description goes here...</p>
    <div class="project-tech">
        <span class="tech-badge">Technology 1</span>
        <span class="tech-badge">Technology 2</span>
    </div>
</div>
```

### Updating Contact Information
1. Open `index.html`
2. Find the `<section id="contact">` section
3. Update the LinkedIn URL in the href attribute
4. Add additional contact buttons if needed

### Customizing Colors
The website uses a purple gradient theme. To change colors:
1. Find the CSS `<style>` section in `index.html`
2. Update the gradient colors in `background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);`
3. Modify other color values like `#667eea` and `#764ba2` throughout the CSS
```html
<div>  https://app.letsdefend.io/my-rewards/detail/255df242337c4570925db53037ad1984
```
## 🛠️ Technologies Used
- HTML5
- CSS3
- GitHub Pages

## 📝 License
© 2025 Segawa Abdul. All rights reserved.
