# dachshund-name

# 🐕 Dachshund Name Generator

A playful, lightweight web application for generating creative and fun names for your dachshund (wiener dog). Built with vanilla JavaScript and featuring a charming UI with no dependencies.

![Dachshund Name Generator](https://dachshund.name/og-image.jpg)

## ✨ Features

- **150+ Creative Names** - Curated collection of unique dachshund-themed names
- **Instant Generation** - Click to generate random names instantly
- **Copy to Clipboard** - One-click copying of generated names
- **Recent Picks History** - Automatically saves your last 7 generated names
- **Fun Animations** - "Shuffle" button with animated name cycling
- **Export Functionality** - Download your recent picks as JSON
- **Responsive Design** - Works seamlessly on desktop and mobile
- **Local Storage** - All data stored locally in your browser
- **SEO Optimized** - Includes comprehensive meta tags and Open Graph data

## 🚀 Demo

Visit the live site: [dachshund.name](https://dachshund.name)

## 🛠️ Tech Stack

- Pure HTML5
- Vanilla JavaScript (ES6+)
- CSS3 with custom properties
- LocalStorage API for persistence
- Google Fonts (Nunito & Fredoka)

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/dachshund-name-generator.git
cd dachshund-name-generator
```

2. Add the required image files:
   - `scubadog.svg` - Logo image (or replace with your own dachshund illustration)
   - `dachshundname.png` - QR code image for the sticky widget

3. Open `index.html` in your browser or serve with any static file server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

## 📁 Project Structure

```
dachshund-name-generator/
├── index.html          # Main HTML file with embedded CSS and JS
├── scubadog.svg        # Logo illustration
├── dachshundname.png   # QR code image
├── og-image.jpg        # Open Graph preview image (optional)
└── README.md           # This file
```

## 🎨 Customization

### Adding More Names

Edit the `NAMES` array in the JavaScript section:

```javascript
const NAMES = [
  "Pretzel", "Noodle", "Sausage", 
  // Add your names here
];
```

### Changing Colors

Modify the CSS variables in the `:root` selector:

```css
:root {
  --bg: #FFF5E6;        /* Background color */
  --accent: #E67E22;    /* Primary accent color */
  --dark: #5A3825;      /* Text color */
  --card: #fff7f1;      /* Card background */
}
```

### Adjusting Recent Picks Limit

Change the `MAX_RECENT` constant:

```javascript
const MAX_RECENT = 7; // Change to your preferred number
```

## 🎯 Features Breakdown

### Generate Name Button
Picks a random name from the collection and adds it to recent picks.

### Surprise Button
Generates a random name with the same functionality as the main button.

### Shuffle Button
Creates an animated cycling effect through multiple names before settling on the final pick.

### Copy Button
Copies the current name to clipboard using the Clipboard API.

### Recent Picks
- Displays last 7 generated names
- Click any name to view it again (without re-adding to history)
- Click copy button next to each name for quick copying

### Export JSON
Downloads recent picks as a JSON file for backup or sharing.

## 🌐 SEO & Social Media

The project includes comprehensive meta tags for:
- Search engine optimization
- Open Graph (Facebook)
- Twitter Cards
- Structured data

Update these in the `<head>` section to match your deployment URL.

## 📱 Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add more creative names
- Improve the UI/UX
- Fix bugs
- Enhance documentation

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🐾 Credits

- Dachshund illustration from [FreeSVG.org](https://freesvg.org) (Public Domain)
- Fonts: Nunito and Fredoka from Google Fonts

## 💡 Ideas for Enhancement

- [ ] Add name categories (German, Food-themed, Classic, etc.)
- [ ] Filter by name length
- [ ] Dark mode toggle
- [ ] Share generated names on social media
- [ ] Save favorite names separately
- [ ] Add name meanings/origins
- [ ] Multi-language support

---

Made with ❤️ for dachshund lovers everywhere!