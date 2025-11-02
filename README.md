# Department of Zoology - GBDC Larkana Website

## 📁 Folder Structure

```
ZOOLOGY-SITE/
├── index.html
├── style.css
├── script.js
├── images/
│   ├── zoology-logo.jpg
│   ├── college logo.jpg
│   └── main.jpg
└── README.md
```

## 🖼️ Image Setup

**IMPORTANT:** Create an `images` folder in the same directory as `index.html` and place your images there:

1. **zoology-logo.jpg** - Zoology department logo (left side of header)
2. **college logo.jpg** - College logo (right side of header)
3. **main.jpg** - College building image (hero section)

The images are now using **relative paths** (`images/filename.jpg`) instead of absolute paths, so they will work correctly.

## ✨ Features

### Modern Eligibility Section
- Beautiful gradient background
- Animated icon badges
- Two modern cards with:
  - SVG icons that rotate on hover
  - Gradient top borders
  - Smooth hover animations
  - Badge system for important info
  - Large card numbers in background

### Three.js Animations
- 1000 animated particles
- DNA helix structure
- 15 rotating molecular shapes
- Mouse-following camera
- Parallax scrolling

### Color Scheme
- Primary Green: #008000
- Primary Blue: #1e5ba8
- Light Green: #4CAF50
- Dark Blue: #0d3b66

## 🚀 How to Use

1. Create the `images` folder
2. Add your three images to the folder
3. Open `index.html` in a web browser
4. Enjoy the modern, animated website!

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop computers
- Tablets
- Mobile phones

## 🎨 Customization

You can easily customize colors by editing the CSS variables in `style.css`:

```css
:root {
    --primary-green: #008000;
    --primary-blue: #1e5ba8;
    --dark-blue: #0d3b66;
    --light-green: #4CAF50;
}
```
