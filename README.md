# 404-Google-Style

> A meticulously crafted, pixel-perfect recreation of Google's iconic 404 error page using pure HTML and CSS.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34C26?logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![Web Standard](https://img.shields.io/badge/Web-Standard-brightgreen)](https://www.w3.org/standards/)

## 🎯 Overview

**404-Google-Style** is an educational project that faithfully reproduces Google's classic 404 error page layout. This project demonstrates modern web development practices using semantic HTML5 and responsive CSS3, without any external dependencies or frameworks.

This is a **pure HTML and CSS implementation** with no JavaScript, making it extremely lightweight, fast, and easy to customize for your own projects.

### Use Cases

- 🎓 Learning semantic HTML and CSS best practices
- 🎨 Studying minimalist design principles
- 🔧 Creating custom 404 pages for your websites
- 📱 Understanding responsive web design
- 🏗️ Using as a boilerplate for error pages

## ✨ Features

- **Pure HTML & CSS** – No dependencies, no framework overhead
- **Semantic Markup** – Proper HTML5 structure with accessibility in mind
- **Responsive Design** – Looks perfect on desktop, tablet, and mobile devices
- **Lightweight** – Minimal CSS (~2KB) for maximum performance
- **Accessibility** – ARIA labels and semantic HTML for screen readers
- **Zero JavaScript** – Fast rendering and no runtime overhead
- **Cross-Browser Compatible** – Works on all modern browsers
- **Easy to Customize** – Simple structure for quick modifications

## 🚀 Quick Start

### Option 1: Direct Usage

1. Clone the repository:
```bash
git clone https://github.com/ViratiAkiraNandhanReddy/404-google-style.git
cd 404-google-style
```

2. Open in your browser:
```bash
# Open index.html directly
open index.html

# Or use a local server (Python 3)
python -m http.server 8000

# Or use Node.js http-server
npx http-server
```

3. Visit `http://localhost:8000` in your browser

### Option 2: Inline Version

For quick integration, use the standalone `inline.html` file which contains all CSS embedded:

```bash
open inline.html
```

### Option 3: Integration into Your Project

Copy the HTML structure and CSS from this project into your error page:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="initial-scale=1, minimum-scale=1, width=device-width">
  <title>Error 404 (Not Found)</title>
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <a href="https://yoursite.com/"><span id="logo" aria-label="Logo"></span></a>
  <p><b>404.</b> <ins>That's an error.</ins>
  <p>The requested URL <code>/example</code> was not found on this server. <ins>That's all we know.</ins>
</body>
</html>
```

## 📁 Project Structure

```
404-google-style/
├── index.html                 # Main 404 page (HTML with external CSS)
├── inline.html                # Standalone version (all-in-one)
├── README.md                  # This file
├── LICENSE                    # MIT License
├── CONTRIBUTING.md            # Contribution guidelines
├── SECURITY.md                # Security policy
├── css/
│   └── styles.css             # Complete stylesheet
└── .github/
    └── PULL_REQUEST_TEMPLATE.md
```

## 🎨 Customization

### Changing Colors

Edit `css/styles.css` to modify the design:

```css
/* Change the background color */
body {
  background-color: #f5f5f5;
}

/* Change text color */
p {
  color: #202124;
}
```

### Changing the Logo/Brand

Replace the logo link in HTML:

```html
<!-- Original: -->
<a href="https://www.google.com/"><span id="logo" aria-label="Google"></span></a>

<!-- Your version: -->
<a href="https://yoursite.com/"><span id="logo" aria-label="YourBrand"></span></a>
```

### Modifying Error Message

Update the error message text:

```html
<p><b>404.</b> <ins>That's an error.</ins>
<p>The requested URL <code>/custom-path</code> was not found on this server. <ins>Custom message here.</ins>
```

### Adding Dynamic Content

You can use server-side templating or JavaScript to dynamically populate the error message:

```html
<p>The requested URL <code id="path"></code> was not found on this server.</p>
<script>
  document.getElementById('path').textContent = window.location.pathname;
</script>
```

## 🌐 Browser Support

| Browser | Version | Support |
|---------|---------|---------|
| Chrome | Latest | ✅ Full |
| Firefox | Latest | ✅ Full |
| Safari | Latest | ✅ Full |
| Edge | Latest | ✅ Full |
| IE | 11 | ⚠️ Partial |
| Mobile (iOS) | Safari 12+ | ✅ Full |
| Mobile (Android) | Chrome 90+ | ✅ Full |

## 🤝 Contributing

We welcome contributions! This project is open to improvements, bug fixes, and enhancements.

## ⚖️ Disclaimer

**This project is for educational and demonstration purposes only.**

- ℹ️ This is **NOT affiliated with or endorsed by Google Inc.**
- ℹ️ Google is a registered trademark of Google LLC
- ℹ️ This is a **recreation of the design** for learning purposes
- ℹ️ All branding and assets belong to their respective owners
- ℹ️ Use this project responsibly and respectfully

For commercial use or integration into Google-related services, ensure compliance with Google's terms of service.

## 📞 Support

- 📖 **Documentation** – See [CONTRIBUTING.md](CONTRIBUTING.md)
- 🐛 **Found a Bug?** – [Open an issue](https://github.com/ViratiAkiraNandhanReddy/404-google-style/issues)
- 💡 **Have an Idea?** – [Start a discussion](https://github.com/ViratiAkiraNandhanReddy/404-google-style/discussions)

## 🌟 Show Your Support

If you found this project helpful:
- ⭐ Star this repository
- 🔄 Share with others
- 📢 Mention in your projects
- 🤝 Contribute improvements
