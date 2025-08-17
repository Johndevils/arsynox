# Minimal Home - Responsive Dashboard

![Minimal Home Dashboard Preview](https://i.ibb.co/RGRGkDpw/arsynox.jpg)

A clean, minimal, and responsive homepage/dashboard that serves as your personal productivity hub with search capabilities, AI tools access, and productivity features.

## 🌟 Features

- **Multi-Engine Search**: Search using Google, DuckDuckGo, GitHub, YouTube, Pinterest, and Perplexity
- **AI Tools Access**: Quick links to ChatGPT, QwenAI, and Google AI Studio
- **Cloud Platform Shortcuts**: Direct access to Cloudflare, Render, Vercel, Netlify, and GitHub
- **Productivity Tools**:
  - Todo list with localStorage persistence
  - Digital clock showing current time and date
- **Responsive Design**: Works perfectly on mobile, tablet, and desktop
- **Minimal Aesthetic**: Clean design with pastel colors and subtle shadows

## 🛠 Technologies Used

- HTML5
- CSS3 (Flexbox layout, no CSS Grid)
- JavaScript (vanilla, no frameworks)
- Font Awesome Icons
- Modern CSS variables and transitions

## 🚀 How to Use

1. **For immediate use**:
   - Simply save the HTML code as `index.html`
   - Open the file in any modern web browser

2. **Customization**:
   - Modify the color scheme by changing CSS variables in `:root`
   - Add or remove search engines by editing the engine switcher section
   - Customize the AI tools or cloud platforms by modifying their respective sections

## 🎨 Design Principles

- **Minimalist**: Ample whitespace, clean typography, and focused content
- **Responsive**: Adapts to all screen sizes using mobile-first approach
- **Accessible**: Good color contrast and clear visual hierarchy
- **Performant**: No external dependencies beyond Font Awesome CDN
- **User-friendly**: Intuitive interactions with visual feedback

## 📱 Responsive Behavior

| Device       | Layout Behavior                                                                 |
|--------------|-------------------------------------------------------------------------------|
| Mobile       | Vertical layout, scrollable icon bars, stacked todo/clock sections            |
| Tablet       | Optimized spacing, larger touch targets, responsive font sizes                |
| Desktop      | Full-width layout with side-by-side todo/clock sections                       |

## ⚙️ Customization Guide

### Changing Search Engines
Edit the engine switcher section in HTML and update the JavaScript engine configurations:

```html
<!-- Add a new search engine -->
<div class="icon-container">
  <div class="icon" data-engine="newengine" data-url="https://newengine.com/search?q=">
    <i class="fab fa-newengine"></i>
  </div>
</div>
```

### Modifying Color Scheme
Update the CSS variables in the `:root` section:

```css
:root {
  --bg-primary: #f8f9fa;
  --bg-secondary: #ffffff;
  --accent-primary: #6a4c93; /* Main accent color */
  --accent-secondary: #4cc9f0; /* Secondary accent color */
  /* ...other variables... */
}
```

### Adding More Tools
Simply duplicate and modify existing icon containers:

```html
<!-- Add new AI tool -->
<div class="icon-container">
  <div class="icon" data-tool="newtool" data-url="https://newtool.com">
    <i class="fas fa-tool-icon"></i>
  </div>
</div>
```

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with ❤️ - A clean, minimal starting point for your personal homepage or dashboard.
