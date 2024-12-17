# Simple GitHub Press Kit Page

A clean, responsive press kit template that can be hosted directly on GitHub Pages. This template provides a single-page website with all the essential elements needed for a game's press coverage.

## 🚀 Quick Start

1. Fork this repository
2. Replace the example content in `index.html` with your game's information
3. Add your images to the appropriate directories
4. Deploy using GitHub Pages or your preferred hosting

## 📁 Structure

```
simple-github-presskit-page/
├── images/
│   ├── awards/      # Award badges and trophies
│   ├── banner/      # Header banner images
│   ├── logos/       # Game logos in various formats
│   ├── promo/       # Key art and promotional images
│   └── screenshots/ # Gameplay screenshots and GIFs
└── index.html       # Main press kit webpage
```

## 🔧 Features

### Navigation
- Sticky navigation bar with smooth scrolling
- Automatically highlights current section
- Mobile-responsive dropdown menu

### Image Management
- Responsive image grid
- Automatic thumbnail generation
- Support for both static images and GIFs
- Organized directory structure for different asset types

### Layout
- Two-column layout for desktop
- Single-column responsive layout for mobile
- Flexible grid system for screenshots and promotional images

### Components
- Factsheet section for key information
- Embedded video support
- Team member listings
- Contact information with social links
- Awards showcase
- Additional links section

## 🎨 Customization

### Styling
All styles are contained in the `<style>` tag within `index.html`. The CSS is organized into sections:
- Base styles and resets
- Layout components
- Navigation styles
- Grid systems
- Media queries for responsiveness

### Adding Sections
1. Add a new section to the HTML:
```html
<section id="your-section">
    <h2>Section Title</h2>
    <div class="content">
        <!-- Your content here -->
    </div>
</section>
```

2. Add a navigation link:
```html
<a href="#your-section">Section Title</a>
```

## 📱 Responsive Design

The template includes breakpoints for:
- Desktop (> 768px)
- Tablet (480px - 768px)
- Mobile (< 480px)

Key responsive features:
- Collapsing navigation
- Adjusting grid layouts
- Scaling images
- Reorganizing two-column layout

## 🛠️ Development

### Prerequisites
- Basic understanding of HTML/CSS
- Text editor
- Web browser
- GitHub account (for forking and deployment)

### Local Development
1. Clone the repository
2. Open `index.html` in a browser
3. Make changes and refresh to see updates

### Testing
Test your press kit across:
- Different browsers (Chrome, Firefox, Safari)
- Various screen sizes
- Both desktop and mobile devices

## 📄 License

This project is licensed under the MIT License - see below for details:

```
MIT License

Copyright (c) 2024

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 💡 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.