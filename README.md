# 🍪 Sweet Cookies | עוגיות מתוקות

A modern, beautifully designed landing page for a home bakery, featuring full RTL (Right-to-Left) support for Hebrew.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## 🌟 Overview

This is a single-page website for "Sweet Cookies" (עוגיות מתוקות), a fictional home bakery. The site showcases:
- Eye-catching hero section with background image
- Product catalog with 6 items (cookies and cakes)
- About section highlighting bakery values
- Contact information with business hours
- Fully responsive design for all devices

## ✨ Features

- **RTL Support** - Full Hebrew language support with right-to-left layout
- **Responsive Design** - Optimized for mobile, tablet, and desktop
- **Modern UI** - Clean, contemporary design with smooth animations
- **Custom Color Palette** - Carefully crafted color scheme
- **Google Fonts** - Premium Heebo font for Hebrew typography
- **Smooth Scrolling** - Seamless navigation between sections
- **Mobile Menu** - Hamburger menu for mobile devices
- **Interactive Cards** - Hover effects on product cards

## 🛠️ Technologies

- HTML5
- CSS3 (Grid, Flexbox, CSS Variables)
- Vanilla JavaScript
- Google Fonts (Heebo)
- Unsplash (Images)

## 🚀 Getting Started

### Prerequisites

No dependencies required! Just a modern web browser.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR-USERNAME/cake.git
cd cake
```

2. Open `index.html` in your browser:
```bash
# Windows
start index.html

# Mac
open index.html

# Linux
xdg-open index.html
```

Or use a local server:
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve
```

3. Navigate to: `http://localhost:8000`

## 📁 Project Structure

```
cake/
├── index.html          # Main HTML file
├── cake.py            # Python file (currently empty)
├── pand.ipynb         # Jupyter Notebook
├── README.md          # This file
├── LICENSE            # MIT License
└── .gitignore         # Git ignore rules
```

## 🎨 Color Palette

```css
--muted-teal: #83b692ff      /* Soft teal */
--rosy-taupe: #be8c88ff      /* Rosy brown */
--bubblegum-pink: #f9627dff  /* Vibrant pink */
--blue-slate: #546a76ff      /* Slate blue */
--sand: #aa9b5fff            /* Sandy brown */
--golden-pollen: #ffcb47ff   /* Golden yellow */
```

## 📱 Responsive Breakpoints

The site is optimized for:
- 📱 Mobile (up to 768px)
- 💻 Tablet (768px - 1024px)
- 🖥️ Desktop (1024px+)

## 🔧 Customization

### Changing Colors

Edit CSS variables in the `:root` selector within the `<style>` tag:
```css
:root {
    --bubblegum-pink: #YOUR-COLOR;
    /* ... */
}
```

### Adding Products

Copy the `.product-card` structure and customize:
```html
<div class="product-card">
    <img src="URL" alt="Description" class="product-image">
    <div class="product-info">
        <h3>Product Name</h3>
        <p>Product description</p>
        <div class="product-price">₪XX / unit</div>
        <a href="#contact" class="order-button">Order</a>
    </div>
</div>
```

### Translating to Other Languages

1. Change `lang="he"` and `dir="rtl"` attributes in `<html>` tag
2. Update all text content
3. Adjust font family in CSS (Heebo is optimized for Hebrew)

## 🌐 Demo

[Live Demo](#) - ((https://miriamtubul.github.io/cake/))

## 📸 Screenshots

The website includes:
- Hero section with stunning background image
- Product grid with interactive hover effects
- Gradient background about section
- Styled contact section with business details

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



## 🙏 Acknowledgments

- Images: [Unsplash](https://unsplash.com)
- Fonts: [Google Fonts](https://fonts.google.com)
- Inspiration: Love for homemade pastries ❤️

## 📌 Future Enhancements

- [ ] Add online ordering form
- [ ] Integrate payment gateway
- [ ] Add customer testimonials section
- [ ] Create admin panel for product management
- [ ] Add image gallery
- [ ] Implement dark mode

---

⭐ If you like this project, please give it a star!

## 📄 Hebrew Description

**עוגיות מתוקות** - אתר תדמית מודרני למאפייה ביתית עם תמיכה מלאה בעברית וכיוון RTL. האתר כולל קטלוג מוצרים, סקירת המאפייה ופרטי יצירת קשר.
