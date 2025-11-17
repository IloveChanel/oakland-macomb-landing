# MVP Painting - Oakland & Macomb Landing Page

## Setup Instructions

### Adding Your Images

1. **Logo Image**
   - Place your logo image in: `assets/images/logos/logo-black.png`
   - Then uncomment line 145 in `index.html` and remove the temporary text logo (lines 146-148)

2. **Hero Background Image**
   - Place your hero image in: `assets/images/hero-about/hero-about-1.jpg`
   - Then update line 159 in `index.html` to use the image (instructions are in the comment)

3. **Favicon** (optional)
   - Place your favicon in: `assets/favicon.ico`

### Current Status

✅ All CSS is now embedded (no external dependencies needed)
✅ Folder structure created
✅ Page works standalone with placeholder logo
✅ Hero section has gradient background (ready for image overlay)

### Next Steps

1. Add your logo image to `assets/images/logos/`
2. Add your hero image to `assets/images/hero-about/`
3. Uncomment the image tags in the HTML
4. Open `index.html` in your browser to preview

### File Structure
```
oakland-macomb-landing page.html/
├── index.html
├── README.md
└── assets/
    ├── favicon.ico (add your favicon here)
    ├── images/
    │   ├── logos/
    │   │   └── logo-black.png (add your logo here)
    │   └── hero-about/
    │       └── hero-about-1.jpg (add your hero image here)
    └── css/ (empty - CSS now embedded in HTML)
```

### Image Specifications

- **Logo**: PNG format, transparent background recommended, ~48px height
- **Hero Image**: JPG format, 1920x1080px or larger recommended
- **Favicon**: ICO format, 32x32px or 16x16px

