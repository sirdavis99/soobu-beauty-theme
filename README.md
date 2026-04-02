# Beauty Theme for Soobu E-Commerce Platform

<p align="center">
  <img src="https://img.shields.io/github/v/release/sirdavis99/soobu-beauty-theme?include_prereleases&label=Version" alt="Version">
  <img src="https://img.shields.io/github/license/sirdavis99/soobu-beauty-theme" alt="License">
  <img src="https://img.shields.io/github/actions/workflow/status/sirdavis99/soobu-beauty-theme/tests" alt="Tests">
  <img src="https://img.shields.io/github/actions/workflow/status/sirdavis99/soobu-beauty-theme/deploy-docs" alt="GitHub Pages">
</p>

A beautiful, modern e-commerce theme designed specifically for the Soobu platform. Perfect for beauty, cosmetics, fashion, and lifestyle online stores.

## ✨ Features

- **Modern & Elegant Design** - Clean UI with beautiful color schemes tailored for beauty brands
- **Fully Responsive** - Seamless experience across desktop, tablet, and mobile devices
- **Easy Customization** - Configure all theme settings through the Soobu admin panel - no coding required
- **Performance Optimized** - Fast loading with clean, efficient code
- **RTL Support** - Full right-to-left language support for Arabic, Hebrew, and other languages
- **SEO Friendly** - Built with SEO best practices in mind

## 📱 Pre-Built Sections

| Section | Description |
|---------|-------------|
| **Header** | Logo, search bar, cart, wishlist, user account |
| **Hero Slider** | Beautiful banner carousel with call-to-action buttons |
| **Categories** | Product category grid display |
| **Featured Products** | Showcase your best products |
| **Bestsellers** | Popular products slider |
| **Brand Logos** | Partner brands carousel |
| **Testimonials** | Customer reviews section |
| **Blog** | Latest articles and news |
| **Newsletter** | Email subscription form |
| **Footer** | Contact info, social links, menus |

## 📂 Theme Structure

```
beauty/
├── assets/
│   ├── css/                    # Stylesheets
│   │   ├── main-style.css      # Main theme styles
│   │   ├── all.min.css         # Font Awesome
│   │   └── swiper-bundle.min.css
│   ├── js/                     # JavaScript files
│   │   ├── custom.js           # Custom theme scripts
│   │   └── tailwind.js         # Tailwind configuration
│   ├── images/                 # Theme images
│   │   ├── logo.png            # Theme logo
│   │   ├── home-banner-*.png   # Home page banners
│   │   └── product-*.png       # Product placeholders
│   └── webfonts/               # Font Awesome fonts
├── views/
│   ├── front_end/
│   │   ├── common/             # Reusable components
│   │   │   ├── offer.blade.php
│   │   │   ├── product_slider.blade.php
│   │   │   ├── sale.blade.php
│   │   │   ├── service.blade.php
│   │   │   └── subscribe.blade.php
│   │   ├── layouts/
│   │   │   └── app.blade.php  # Main layout
│   │   └── partison/
│   │       ├── header.blade.php
│   │       ├── footer.blade.php
│   │       └── announcement.blade.php
│   └── components/
│       ├── product-card.blade.php
│       ├── blog-card.blade.php
│       └── search-popup.blade.php
├── theme_json/                 # Theme configuration
│   ├── home.json               # Home page settings
│   ├── header.json            # Header configuration
│   ├── footer.json             # Footer configuration
│   ├── product.json            # Product page settings
│   ├── blog.json              # Blog page settings
│   └── ...                     # More page configs
├── default_data/
│   └── settings.php           # Default theme settings
└── verification.php           # Theme verification
```

## 🚀 Installation

### Quick Install (Clone)

```bash
# Navigate to your Soobu themes folder
cd /path/to/soobu/themes

# Clone the Beauty theme
git clone https://github.com/sirdavis99/soobu-beauty-theme.git beauty

# Or use SSH
git clone git@github.com:sirdavis99/soobu-beauty-theme.git beauty
```

### Manual Install

1. Download the latest release from the [Releases](https://github.com/sirdavis99/soobu-beauty-theme/releases) page
2. Extract the ZIP file
3. Upload the `beauty` folder to your Soobu themes directory
4. Activate the theme through the Soobu admin panel

## ⚙️ Configuration

After installing the theme, you can customize it through the Soobu admin panel:

1. Go to **Theme Settings** in your Soobu admin
2. Customize sections like:
   - Logo and favicon
   - Header layout and elements
   - Footer content and links
   - Home page sections
   - Colors and typography
   - And much more!

## 🎨 Customization

### Changing Colors

Edit the theme settings in the Soobu admin panel to change:
- Primary colors
- Accent colors
- Background colors
- Text colors

### Adding Your Logo

Upload your logo through the theme settings:
- Recommended size: 200x60px
- Formats: PNG, SVG

### Banner Images

Replace default banners in `assets/images/`:
- `home-banner-01.png` - First slider image
- `home-banner-02.png` - Second slider image
- `home-banner-03.png` - Third slider image

## 🔧 Development

### Requirements

- Soobu e-commerce platform
- PHP 8.2+
- Node.js 20+ (for development)

### Running Tests

```bash
# Validate theme structure
npm run test

# Or run directly
bash .github/workflows/tests.sh
```

## 📄 License

This theme is available for use with the Soobu e-commerce platform.

See [LICENSE](LICENSE) for details.

## 🤝 Contributing

Contributions are welcome! Please read our [Contributing Guide](CONTRIBUTING.md) before submitting a Pull Request.

## 🐛 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/sirdavis99/soobu-beauty-theme/issues) page
2. Create a new issue if needed
3. For Soobu platform issues, visit [Soobu Repository](https://github.com/soobu/soobu)

## 🌐 Related Projects

- [Soobu](https://github.com/soobu/soobu) - Main e-commerce platform
- [Soobu Extensions](https://github.com/soobu/soobu-extensions) - Developer portal for themes

---

<p align="center">
  Made with ❤️ for the Soobu Community
</p>