# 🍔 Quetta Fast Food - Restaurant Website

<div align="center">

![GitHub repo size](https://img.shields.io/github/repo-size/codewithsadee/foodie)
![GitHub stars](https://img.shields.io/github/stars/codewithsadee/foodie?style=social)
![GitHub forks](https://img.shields.io/github/forks/codewithsadee/foodie?style=social)
[![Twitter Follow](https://img.shields.io/twitter/follow/codewithsadee_?style=social)](https://twitter.com/intent/follow?screen_name=codewithsadee_)
[![YouTube Video Views](https://img.shields.io/youtube/views/5XnX83goEZo?style=social)](https://youtu.be/5XnX83goEZo)

**Quetta Fast Food** is a fully responsive fast food website showcasing delicious burgers and pizzas. Built with pure HTML, CSS, and JavaScript, it provides a modern and engaging user experience.

[🌐 Live Demo](https://foodie-vercel.vercel.app/) • [📱 View on GitHub](https://github.com/codewithsadee/foodie)

</div>

---

## ✨ Features

- ✅ **Fully Responsive Design** - Optimized for all devices (mobile, tablet, desktop)
- ✅ **Modern UI/UX** - Clean and intuitive interface
- ✅ **Interactive Navigation** - Smooth menu toggle and navigation
- ✅ **Search Functionality** - Search box for finding menu items
- ✅ **Product Showcase** - Display of popular food items with categories
- ✅ **Reservation System** - Book a table functionality
- ✅ **Blog Section** - Food and restaurant blog posts
- ✅ **Fast Performance** - Lightweight and optimized code
- ✅ **Cross-browser Compatible** - Works on all modern browsers

---

## 🛠️ Technology Stack

| Technology | Version | Purpose |
|-----------|---------|---------|
| **HTML5** | Latest | Structure & Markup |
| **CSS3** | Latest | Styling & Responsive Design |
| **JavaScript (ES6)** | Latest | Interactivity & Functionality |
| **Google Fonts** | - | Typography (Roboto, Rubik, Shadows Into Light) |
| **Ionicons** | 5.5.2 | Icon Library |

---

## 📁 Project Structure

```
foodie/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css       # Main stylesheet (1769 lines)
│   ├── js/
│   │   └── script.js       # JavaScript functionality
│   └── images/             # Image assets
├── README.md               # Documentation
├── style-guide.md          # Design system & colors
└── index.txt               # Content structure
```

---

## 🎨 Design System

### Color Palette

The project uses a carefully curated color scheme:

- **Primary Colors**: Deep Saffron (`#FFD700`), Dark Orange (`#E67E22`)
- **Neutral Colors**: Rich Black (`#0F1419`), White (`#FFFFFF`), Gainsboro (`#DEDEDE`)
- **Accent Colors**: Champagne Pink (`#E8DCC5`), Tangerine (`#FF9F1C`)
- **Text Colors**: Onyx (`#454545`), Spanish Gray (`#999999`)

### Typography

- **Headings**: Rubik (Bold, Semi-bold)
- **Body Text**: Roboto (Regular, Medium)
- **Decorative**: Shadows Into Light (Cursive)

### CSS Variables

Customizable variables for easy theming:
- Font sizes: `--fs-1` to `--fs-5`
- Font weights: `--fw-500`, `--fw-600`, `--fw-700`
- Section padding: `--section-padding: 60px`
- Transitions: `--transition-1: 0.25s ease`, `--transition-2: 0.5s ease`

See [style-guide.md](style-guide.md) for complete design specifications.

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- [Git](https://git-scm.com/downloads)
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code recommended)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/codewithsadee/foodie.git
   cd foodie
   ```

2. **Open in your browser**

   - **Option 1**: Double-click `index.html` to open it directly
   - **Option 2**: Use a local server
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```
   - Then navigate to `http://localhost:8000` in your browser

3. **Start customizing** - Edit HTML, CSS, and JavaScript files as needed

---

## 📝 Main Sections

### 1. Header & Navigation
- Sticky header that activates on scroll
- Mobile-responsive navigation menu
- Search functionality
- Reservation button

### 2. Hero Section
- Eye-catching banner with CTA
- Hero image and tagline
- "Book A Table" call-to-action

### 3. Promotional Section
- Featured food items (Mexican Pizza, Soft Drinks, etc.)
- Quick access to popular products

### 4. About Section
- Restaurant information
- Key features and benefits
- Call-to-action for ordering

### 5. Food Menu
- Categorized menu items (Pizza, Burger, etc.)
- Popular dishes showcase
- Filter functionality

### 6. Additional Features
- Blog section for food articles
- Contact information
- Back-to-top button

---

## 🎯 How to Customize

### Change Colors

Edit the CSS variables in [assets/css/style.css](assets/css/style.css):

```css
:root {
  --deep-saffron: hsl(32, 100%, 59%);      /* Primary color */
  --dark-orange: hsl(28, 100%, 58%);       /* Secondary color */
  --rich-black-fogra-29: hsl(210, 26%, 7%); /* Text color */
  /* ... more colors ... */
}
```

### Change Typography

Modify font family and sizes:

```css
--ff-rubik: 'Rubik', sans-serif;    /* Heading font */
--ff-roboto: 'Roboto', sans-serif;  /* Body font */
--fs-1: 3.2rem;                      /* Large headings */
```

### Update Content

1. **Logo & Title**: Edit in [index.html](index.html) line 49
2. **Navigation Links**: Modify navbar items in header section
3. **Food Items**: Update menu items in the food menu section
4. **Images**: Replace images in [assets/images/](assets/images/) directory

### Modify Functionality

Edit [assets/js/script.js](assets/js/script.js) to customize:
- Navigation toggle behavior
- Search functionality
- Scroll animations
- Form submissions

---

## 📱 Responsive Breakpoints

The site is optimized for multiple screen sizes:

- **Mobile**: 320px - 767px
- **Tablet**: 768px - 1199px
- **Desktop**: 1200px and above

---

## 🔍 JavaScript Features

### Implemented Functionality

1. **Navbar Toggle** - Mobile menu open/close
2. **Sticky Header** - Header becomes sticky on scroll
3. **Back to Top** - Scroll to top button
4. **Search Box** - Toggle search interface
5. **Active Link Highlighting** - Current page indicator

All functionality is event-driven and uses data attributes for DOM manipulation.

---

## 📦 External Dependencies

```html
<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&family=Rubik:wght@400;500;600;700&family=Shadows+Into+Light&display=swap">

<!-- Ionicons -->
<script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
```

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📞 Contact & Support

- **Twitter**: [@codewithsadee_](https://twitter.com/codewithsadee_)
- **YouTube**: [Code With Sadee](https://www.youtube.com/@codewithsadee)
- **GitHub Issues**: [Report a bug](https://github.com/codewithsadee/foodie/issues)

---

## 📄 License

This project is **open-source and free to use**. No license restrictions apply.

---

## 🎓 Learning Resources

This project is great for learning:
- HTML5 semantic markup
- CSS3 responsive design and flexbox/grid
- Vanilla JavaScript DOM manipulation
- Mobile-first design approach
- Accessibility best practices

---

## 📸 Screenshots

### Desktop View
![Quetta Fast Food Desktop Demo](./readme-images/desktop.png)

---

## 🚦 Deployment

### Deploy to GitHub Pages

1. Push your code to GitHub
2. Go to repository settings
3. Enable GitHub Pages from the `main` or `master` branch
4. Your site will be live at `https://yourusername.github.io/foodie/`

### Deploy to Other Platforms

- **Netlify**: Drag & drop the folder or connect GitHub
- **Vercel**: Import the repository
- **Firebase Hosting**: Follow Firebase deployment guide
- **Any web server**: Upload the files via FTP/SFTP

---

## ✅ Checklist for Customization

- [ ] Update restaurant name and logo
- [ ] Change color scheme to match your brand
- [ ] Update food menu items and prices
- [ ] Replace images with your restaurant's photos
- [ ] Modify contact information
- [ ] Update social media links
- [ ] Add your own content/descriptions
- [ ] Test on mobile devices
- [ ] Deploy to live server

---

## 🐛 Troubleshooting

**Issue**: Icons not showing
- **Solution**: Check internet connection (Ionicons loaded from CDN)

**Issue**: Fonts not loading
- **Solution**: Verify Google Fonts CDN link is active

**Issue**: Responsive design not working
- **Solution**: Check `<meta name="viewport">` tag in HTML

**Issue**: JavaScript not working
- **Solution**: Open browser console for errors, ensure JS file path is correct

---

## 🙌 Acknowledgments

- Design & Development: [codewithsadee](https://github.com/codewithsadee)
- Google Fonts for typography
- Ionicons for icons
- Community feedback and contributions

---

<div align="center">

**Made with ❤️ by codewithsadee**

[⬆ Back to top](#-quetta-fast-food---restaurant-website)

</div>
