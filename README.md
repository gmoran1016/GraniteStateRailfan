# Granite State Railfan

A railfanning website dedicated to New Hampshire and New England railroad content - photography, videography, and railfan adventures.

**Live Site:** [granite-state-railfan.pages.dev](https://granite-state-railfan.pages.dev)  
**Content Creator:** Griffin  
**Last Updated:** June 2026

## Project Structure

```
├── index.html              # Main website (homepage)
├── _redirects              # Cloudflare Pages routing configuration
├── _headers                # Cloudflare Pages cache and security headers
├── wrangler.toml           # Cloudflare Pages deployment config
├── README.md               # This file
├── assets/
│   ├── images/             # All image assets (logos, banners, photos)
│   │   ├── banner-x2.png
│   │   ├── logo-x2.png
│   │   └── mec.jpg
│   └── fonts/              # Font files
│       └── mecold.ttf
└── docs/                   # Documentation and additional resources
    ├── mecold.pdf
    └── mecold.txt
```

## Features

- 📸 Railroad photography showcase
- 🎥 Train video highlights
- 🚂 New Hampshire & New England focus
- 📱 Fully responsive design
- 🎨 Custom MECold font styling
- 🟢 Green & copper color scheme

## Social Links

- [YouTube](https://www.youtube.com/@granitestaterailfan)
- [Instagram](https://www.instagram.com/granitestaterailfan/)
- [Facebook](https://www.facebook.com/profile.php?id=61589875160674)

## Deployment

### Cloudflare Pages

This site is optimized for Cloudflare Pages deployment:

1. **Auto-deployed** from git repository
2. **Configured via `wrangler.toml`** for build settings
3. **Routing handled** by `_redirects` file
4. **Cache & security** configured via `_headers` file

#### Deployment Steps:

1. Connect your repository to Cloudflare Pages
2. Set build command: `echo "Static site ready"`
3. Set publish directory: `.` (root)
4. Deploy!

#### Environment

- Build: Static files only (no build process needed)
- Runtime: Cloudflare Pages (edge deployment)
- Assets: Cached for performance

## Local Development

Simply open `index.html` in your browser or use a local server:

```bash
# Python 3
python -m http.server 8000

# Node.js
npx http-server

# Then visit: http://localhost:8000
```

## File Organization

- **index.html** - Single-page website with embedded CSS
- **assets/images/** - All PNG, JPG, and image files
- **assets/fonts/** - TTF and web font files
- **docs/** - Additional documentation, PDFs, and resources
- **_redirects** - URL routing and SPA fallback for Cloudflare
- **_headers** - Cache control and security headers

## Browser Support

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive design
- CSS Grid and Flexbox layouts

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Responsive design with CSS Variables and Grid/Flexbox
- **Custom Fonts** - MECold TrueType font for branding
- **Cloudflare Pages** - Edge hosting and deployment
- **Wrangler** - Cloudflare Pages CLI tooling

## Getting Started

### Prerequisites
- A modern web browser
- (Optional) Git for cloning the repository
- (Optional) Local web server for development

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/GraniteStateRailfan.git
   cd GraniteStateRailfan
   ```

2. Start a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Or Node.js
   npx http-server
   ```

3. Open in browser: `http://localhost:8000`

## Contributing

Contributions are welcome! Please feel free to:
- Report bugs or issues
- Suggest new features or content
- Submit pull requests with improvements

## License

This project is the intellectual property of Granite State Railfan. Use and modification for personal use only without explicit permission.

## Contact & Social

- **YouTube:** [@granitestaterailfan](https://www.youtube.com/@granitestaterailfan)
- **Instagram:** [@granitestaterailfan](https://www.instagram.com/granitestaterailfan/)
- **Facebook:** [Granite State Railfan](https://www.facebook.com/profile.php?id=61589875160674)

---

**© 2026 Granite State Railfan**  
New Hampshire Railfanning & Railroad Media
