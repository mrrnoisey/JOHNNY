# JOHNNY - @noise_ysilent Portfolio

A stylish, interactive portfolio page with animated background, cursor effects, and smooth transitions.

## Features

- 🎨 **Animated Background**: 3D parallax particle effect using Canvas
- ✨ **Interactive Elements**: Cursor trails and click ripple effects
- 🎯 **Responsive Design**: Mobile-friendly layout
- 🔗 **Social Integration**: Quick link to Instagram profile
- ⚡ **Pure HTML/CSS/JS**: No dependencies, fast loading

## Quick Start

### Local Development
```bash
npm start
```
This starts a local server at `http://localhost:8000`

### Deployment

#### GitHub Pages
Push to the `main` branch. The site is automatically deployed to `https://[username].github.io/JOHNNY`

#### Other Hosting
- Netlify: Connect your GitHub repo
- Vercel: Import project and deploy
- Surge.sh: `surge . [domain]`
- Any static hosting service

## Customization

### Update Profile Image
Replace `your-image.jpg` with your actual image file:
```html
<img src="path/to/your-image.jpg">
```

### Update Social Links
Edit the `follow()` function in `index.html`:
```javascript
function follow() {
    window.open("https://your-social-link", "_blank");
}
```

### Modify Bio Text
Update the bio section in the HTML:
```html
<div class="bio">Your bio text here</div>
```

### Change Colors
Edit the CSS variables in `<style>`:
- Primary color: `#00f7ff` (cyan)
- Background: `#050505` (dark)
- Accent: `#ff00ff` (magenta)

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

## License

MIT

---

**Follow**: [@noise_ysilent](https://instagram.com/noise_ysilent)