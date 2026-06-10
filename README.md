# ✨ OLIVIA'S EMAIL COPY ZONE ✨

A deliberately retro, GeoCities/AOL-aesthetic portfolio website for an email copywriting business. Maximum 90s vibes, minimum restraint.

## 🌟 Features

- **Neon aesthetic** - Bright, clashing colors with glowing effects
- **Retro typography** - VT323 font for that authentic early-internet feel
- **Animated elements** - Blinking text, sparkling effects, floating animations
- **Cursor trail** - Star/sparkle particles follow your mouse
- **Responsive design** - Works on mobile despite the chaotic aesthetic
- **Portfolio showcase** - Case study cards with bold, colorful styling
- **Contact form** - Styled as a classic 90s chat window
- **Easter egg** - Konami code (↑↑↓↓←→←→BA) activates a surprise!
- **Guestbook section** - Classic web 1.0 vibes
- **Visitor counter** - Increments on each page load

## 📁 File Structure

```
.
├── index.html      # Main portfolio page
├── styles.css      # All styling (animations, colors, layout)
├── script.js       # Interactive effects (cursor trail, form handling, Easter egg)
└── README.md       # This file
```

## 🚀 Getting Started

1. Clone or download this repo
2. Open `index.html` in your browser
3. Customize the content with your actual portfolio information

## ✏️ Customization

### Update Your Info
Edit `index.html` to change:
- Your name and headline
- Portfolio case studies (update descriptions, metrics, results)
- Contact email and social links
- Skills section
- Guestbook entries (optional)

### Form Submission
The contact form currently shows a retro alert. To make it functional:

**Option 1: Use Formspree (free, no backend needed)**
1. Go to [formspree.io](https://formspree.io/)
2. Create a new form
3. In `script.js`, uncomment the fetch code and replace `YOUR_FORM_ID`

**Option 2: Use Netlify Forms**
1. Deploy to Netlify
2. Add `netlify` attribute to the form in `index.html`
3. Works out of the box!

### Color Scheme
All colors are defined in `styles.css`. Main palette:
- **Neon Pink**: `#ff00ff`
- **Cyan**: `#00ffff`
- **Bright Yellow**: `#ffff00`
- **Lime Green**: `#00ff00`
- **Electric Blue**: `#0066ff`
- **Dark backgrounds**: `#000000`, `#000066`, `#330066`

### Fonts
Change the font by editing the `font-family` in `styles.css`. Current: `VT323` (retro bitmap font)

Alternative retro fonts from Google Fonts:
- `Press Start 2P` - 8-bit style
- `Space Mono` - Monospace retro
- `Courier Prime` - Typewriter vibes

## 🎨 Adding More Content

### New Portfolio Items
Add to the `.portfolio-grid` in `index.html`:
```html
<div class="portfolio-item blue-box">
    <div class="portfolio-label">CASE STUDY #5</div>
    <h3>Your Project Title</h3>
    <p>Description of what you did and results.</p>
    <p class="small-text">📊 Metrics go here</p>
</div>
```

### New Skills
Add to the `.skills-container`:
```html
<div class="skill-box">
    <h3>📊 New Skill Category</h3>
    <p>Description of your expertise</p>
</div>
```

### New Sidebar Widgets
Add to the `.sidebar`:
```html
<div class="widget purple-widget">
    <div class="widget-title">🎯 WIDGET TITLE 🎯</div>
    <p>Your content here</p>
</div>
```

Widget color classes: `purple-widget`, `neon-widget`, `lime-widget`, `pink-widget`

## 🔊 Audio (Optional)

To add AOL notification sounds or background music:
1. Add audio files to your project
2. In `script.js`, uncomment the `playNotificationSound()` function
3. Update the audio file path

## 📱 Mobile Optimization

The site is responsive and works on mobile, but some effects may be reduced:
- Cursor trail disabled on touch devices (no mouse)
- Font sizes reduce on small screens
- Grid layouts stack to single column

## 🐛 Browser Support

Works best in modern browsers:
- ✅ Chrome/Edge
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers

(NOT tested in IE5, despite what the badge says 😄)

## 🎮 Easter Egg

Try entering the Konami Code: **↑ ↑ ↓ ↓ ← → ← → B A**

## 📝 Tips for Maximum Retro Impact

1. **Use exclamation marks!!!** They look more excited
2. **Add emoji** - More emoji = more retro (within reason)
3. **Keep animations** - Don't tone down the blinking and sparkles
4. **Bold claims** - "ELITE", "BEST", "PROFESSIONAL" in all caps
5. **Fake badges** - Add more "best viewed in" and certification badges
6. **Awkward spacing** - Uneven margins are on-brand for GeoCities

## 📄 License

Make it your own! This is your portfolio now. 

---

**Last updated**: Today ⭐

*"The best time to have a retro portfolio was 20 years ago. The second best time is now."*
