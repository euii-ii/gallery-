# CarouselVision 🎠

A stunning and fully responsive 3D rotating image carousel built with pure HTML and CSS. CarouselVision transforms ordinary image galleries into captivating visual experiences, perfect for portfolios, product showcases, or any creative display needs.

## ✨ Features

**Zero Dependencies**: Built entirely with HTML5 and CSS3 - no JavaScript frameworks required.

**Fluid 3D Animations**: Buttery-smooth CSS3 transitions create mesmerizing rotation effects.

**Mobile-First Design**: Optimized for all devices from smartphones to ultra-wide displays.

**Infinite Customization**: Easily modify colors, timing, images, and rotation effects.

**Performance Optimized**: Hardware-accelerated CSS transforms for smooth 60fps animations.

**Accessibility Ready**: Respects user motion preferences and includes proper ARIA labels.

## 📁 Project Architecture

```
🎠 CarouselVision/
├── 📄 index.html          # Core HTML structure
├── 🎨 style.css           # Advanced CSS animations & styling
├── 🖼️  images/             # Gallery image assets
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
└── 📖 README.md           # Project documentation
```

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/euii-ii/carouselvision.git

# Navigate to project directory
cd carouselvision

# Launch in your browser
open index.html
```

### Instant Preview
Simply double-click `index.html` or drag it into any modern web browser to experience the carousel magic!

## ⚡ How It Works

CarouselVision leverages advanced CSS techniques including:

- **CSS Grid & Flexbox**: For precise layout control and centering
- **Transform3D**: Hardware-accelerated 3D rotations and positioning  
- **Keyframe Animations**: Smooth, continuous rotation cycles
- **CSS Variables**: Dynamic theming and easy customization
- **Media Queries**: Responsive breakpoints for all screen sizes

The carousel creates a 3D cylinder effect where images are positioned around a virtual circle, rotating smoothly through CSS transforms.

## 🎨 Customization

### Adding Your Images
Replace images in the `/images` folder and update the HTML image references.

### Adjusting Animation Speed
Modify the animation duration in `style.css`:
```css
.carousel {
  animation-duration: 20s; /* Change this value */
}
```

### Changing Colors & Themes
Update CSS custom properties in the `:root` selector for instant theme changes.

## 🛠️ Built With

**HTML5**: Semantic markup and modern web standards
**CSS3**: Advanced animations, transforms, and responsive design
**Love**: Crafted with attention to detail and user experience

## 🌐 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+  
- ✅ Safari 12+
- ✅ Edge 79+

## 🤝 Contributing

We welcome contributions! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Share your CarouselVision implementations

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

**Made with ❤️ for developers who love beautiful, performant web experiences**
