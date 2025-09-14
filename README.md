Professional-CV-Template

A clean, modern, and responsive CV template built with HTML5 and CSS3. This template recreates a professional resume layout with proper typography hierarchy, color-coded sections, and print-friendly styling.

🚀 Demo

[Live Demo](https://stackdevsoftware.github.io/cv-template)

⚡️Features

- **Clean Professional Design** - Minimal and elegant layout
- **Color-Coded Sections** - Green section headers, blue company names for easy scanning
- **Responsive Layout** - Looks great on desktop, tablet, and mobile
- **Print Optimized** - Printer-friendly styling
- **Easy Customization** - Simple HTML structure and well-commented CSS
- **Cross-Browser Compatible** - Works on all modern browsers
- **Semantic HTML** - Proper markup for accessibility and SEO

🛠️ Built With

- HTML5 - Semantic markup structure
- CSS3 - Modern styling with flexbox and grid
- Font: Arial (web-safe font for universal compatibility)

📋 Getting Started

Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, or any editor)
- Basic knowledge of HTML/CSS (for customization)

📁 Project Structure

```
cv-template/
├── index.html          # Main CV file with embedded CSS
├── screenshots/        # Preview images
│   ├── desktop-view.png
│   └── mobile-view.png
├── README.md          # This file
└── LICENSE            # MIT License
```

🎨 Customization Guide

Updating Your Information

1. Personal Details
   ```html
   <h1 class="name">Your Name</h1>
   <div class="job-title">Junior Frontend Developer</div>
   ```

2. Contact Information
   ```html
   <div class="contact-info">
       123 Your Street<br>
       Your City, ST 12345<br>
       (123) 456-7890<br>
       your.email@example.com
   </div>
   ```

3. Skills Section
   ```html
   <div class="skills">
       HTML, CSS, JavaScript, React, Node.js...
   </div>
   ```

Color Customization

The template uses a consistent color scheme:

- Section Headers: `#4CAF50` (Green)
- Company/School Names: `#4285F4` (Blue)  
- Body Text: `#666` (Gray)
- Main Text: `#333` (Dark Gray)

To change colors, modify these values in the CSS:

```css
.section-title {
    color: #4CAF50; /* Change this to your preferred color */
}
```

Adding New Sections

1. Add a new section title:
   ```html
   <div class="section-title">New Section</div>
   ```

2. Add your content with appropriate classes:
   ```html
   <div class="entry">
       <div class="entry-header">Title</div>
       <div class="description">Description</div>
   </div>
   ```

📄 Template Sections

The template includes the following sections:

1. Header - Name, job title, and contact information
2. Skills - Technical and soft skills
3. Education - Academic background
4. Experience - Work history with achievements
5. Online Presence - Social media and portfolio links

📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.