# GraniteStateRailfan

A railfanning website dedicated to New Hampshire and New England railroad content - photography, videography, and railfan adventures.

## Project Structure

```
├── index.html              # Main website (homepage)
├── _redirects              # Cloudflare Pages routing configuration
├── _headers                # Cloudflare Pages cache and security headers
├── wrangler.toml           # Cloudflare Pages deployment config
├── README.md               # This file
├── assets/
│   ├── images/             # All image assets (logos, banners, photos)
│   │   ├── Banner x2.png
│   │   ├── Logo X2 .png
│   │   └── mec.jpg
│   └── fonts/              # Font files
│       └── MECold.ttf
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

---

**© 2026 Granite State Railfan**  
New Hampshire Railfanning & Railroad Media
