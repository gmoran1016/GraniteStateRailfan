# Granite State Railfan

A railfanning website dedicated to New Hampshire and New England railroad content - photography, videography, and railfan adventures.

**Live Site:** [granitestaterailfan.com](https://www.granitestaterailfan.com)<br>
**Content Creator:** Griffin  
**Last Updated:** November 2026

## Project Structure

```
├── .assetsignore           # Files excluded from public static asset uploads
├── index.html              # Main website (homepage)
├── _redirects              # Cloudflare Workers static asset redirects
├── _headers                # Cloudflare Workers static asset headers
├── wrangler.toml           # Cloudflare Workers static assets config
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
- [Facebook](https://www.facebook.com/granitestaterailfan/)
- [TikTok](https://www.tiktok.com/@granitestaterailfan)

## Deployment

### Cloudflare Workers Builds

This static site is deployed as a Cloudflare Worker with static assets:

1. **Auto-deployed** from the connected Git repository's `main` branch
2. **Configured via `wrangler.toml`** with `assets.directory = "."`
3. **Deployed with** `npx wrangler deploy`
4. **Routing and headers** handled by `_redirects` and `_headers`

#### Deployment Steps:

1. Connect the repository to Cloudflare Workers Builds
2. Set the production branch to `main` and the root directory to `/`
3. Leave the build command empty for this static site
4. Set the deploy command to `npx wrangler deploy`

#### Environment

- Build: Static files only (no build process needed)
- Runtime: Cloudflare Workers static assets
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
- **Cloudflare Workers** - Edge hosting for static assets
- **Wrangler** - Cloudflare Workers deployment tooling

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
- **Facebook:** [Granite State Railfan](https://www.facebook.com/granitestaterailfan/)
- **TikTok:** [@granitestaterailfan](https://www.tiktok.com/@granitestaterailfan)

---

**© 2026 Granite State Railfan**  
New Hampshire Railfanning & Railroad Media
