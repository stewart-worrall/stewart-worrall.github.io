# Stewart Worrall - Mathematics & Computing Technologies

A modern GitHub Pages site showcasing innovative applications of mathematics and computing technology across various domains including robotics, AI/ML, data science, digital art, computer graphics, and cryptography.

## 🌟 Features

### Modern Design
- **Responsive Layout**: Optimized for all devices and screen sizes
- **Dark/Light Theme**: Toggle between themes with persistent preferences
- **Smooth Animations**: CSS animations and transitions for enhanced UX
- **Modern Typography**: Inter font for content, JetBrains Mono for code

### Innovative UI Elements
- **Interactive Category Cards**: Hover effects and smooth transitions
- **Mathematical Notation**: MathJax integration for beautiful math rendering
- **Code Highlighting**: Prism.js with copy functionality
- **Interactive Demos**: Canvas-based visualizations and simulations
- **Parallax Effects**: Subtle parallax scrolling for depth

### Technology Categories
- 🤖 **Robotics & Control Systems**: Path planning, PID controllers, kinematics
- 🧠 **AI & Machine Learning**: Neural networks, optimization, deep learning
- 📊 **Data Science & Analytics**: Statistics, visualization, big data
- 🎨 **Digital Art & Creative Computing**: Generative art, fractals, creative coding
- 🎮 **Computer Graphics & Visualization**: 3D graphics, ray tracing, geometry
- 🔐 **Cryptography & Security**: Number theory, encryption, blockchain

## 🚀 Getting Started

### Prerequisites
- Ruby 2.6 or higher
- Jekyll 4.3.0 or higher

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/stewart-worrall/stewart-worrall.github.io.git
   cd stewart-worrall.github.io
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **Visit the site**
   Open [http://localhost:4000](http://localhost:4000) in your browser

## 📁 Project Structure

```
stewart-worrall.github.io/
├── _config.yml              # Jekyll configuration
├── _layouts/                # HTML layouts
│   └── default.html         # Main layout with navigation
├── assets/                  # Static assets
│   ├── css/
│   │   └── main.css         # Main stylesheet with CSS variables
│   └── js/
│       └── main.js          # Interactive functionality
├── projects/                # Project pages
│   ├── index.html           # Projects overview
│   └── *.html              # Individual project pages
├── index.html              # Homepage
└── README.md               # This file
```

## 🎨 Customization

### Adding New Projects

1. **Create a new project file** in the `projects/` directory:
   ```html
   ---
   layout: default
   title: Your Project Title
   category: robotics
   tags: [robotics, algorithms, python]
   ---
   
   <!-- Your project content here -->
   ```

2. **Add to the projects grid** in `projects/index.html`

### Styling

The site uses CSS custom properties for easy theming:

```css
:root {
    --accent-primary: #3b82f6;    /* Primary blue */
    --accent-secondary: #8b5cf6;  /* Secondary purple */
    --bg-primary: #ffffff;        /* Background */
    --text-primary: #1e293b;      /* Text color */
}
```

### Interactive Elements

Add interactive demos using the `.interactive-demo` class:

```html
<div class="interactive-demo">
    <h3>Your Demo Title</h3>
    <p>Description of the interactive element</p>
    <div class="demo-controls">
        <button class="btn" onclick="yourFunction()">Launch Demo</button>
    </div>
    <div class="demo-canvas">
        <!-- Your interactive content -->
    </div>
</div>
```

## 🔧 Technologies Used

- **Jekyll**: Static site generator
- **CSS Grid & Flexbox**: Modern layout techniques
- **CSS Custom Properties**: Dynamic theming
- **JavaScript ES6+**: Interactive functionality
- **MathJax**: Mathematical notation rendering
- **Prism.js**: Code syntax highlighting
- **Font Awesome**: Icons
- **Google Fonts**: Typography

## 📱 Responsive Design

The site is fully responsive with breakpoints at:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🌙 Theme System

The site supports both light and dark themes with:
- Automatic theme detection based on system preferences
- Manual theme toggle in the navigation
- Persistent theme selection using localStorage
- Smooth transitions between themes

## 🚀 Deployment

This site is configured for GitHub Pages deployment:

1. **Push to GitHub**: The site will automatically build and deploy
2. **Custom Domain**: Configure in repository settings
3. **HTTPS**: Automatically enabled by GitHub Pages

## 📈 Performance

- **Lazy Loading**: Images and heavy content load on demand
- **Minified Assets**: Optimized CSS and JavaScript
- **CDN Resources**: External libraries loaded from CDNs
- **Efficient Animations**: Hardware-accelerated CSS transforms

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally with `bundle exec jekyll serve`
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🔗 Links

- **Live Site**: [stewart-worrall.github.io](https://stewart-worrall.github.io)
- **GitHub**: [github.com/stewart-worrall](https://github.com/stewart-worrall)
- **LinkedIn**: [linkedin.com/in/your-profile](https://linkedin.com/in/your-profile)

---

Built with ❤️ using modern web technologies to showcase the beautiful intersection of mathematics and computing.
