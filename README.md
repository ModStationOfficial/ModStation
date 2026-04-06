# ModStation - Ultimate Gaming Hub

Welcome to ModStation, your premier destination for modded games and APKs!

## Features

- **Modern Design**: Sleek, responsive interface with smooth animations
- **Categorized Games**: Organized sections for different game types
- **Easy Navigation**: Fixed header with smooth scrolling
- **Contact Form**: Built-in contact functionality
- **Mobile Friendly**: Responsive design that works on all devices

## How to Add Games

1. **Upload Images**: Place your game thumbnails in the `images/` folder
2. **Update HTML**: Add game cards to the appropriate category sections in `index.html`
3. **Game Card Structure**:
   ```html
   <div class="game-card">
       <img src="images/your-game-thumbnail.jpg" alt="Game Name">
       <div class="game-info">
           <h3>Game Name</h3>
           <p>Brief description of the mod</p>
           <a href="YOUR_DOWNLOAD_LINK" class="btn-download">Download APK</a>
       </div>
   </div>
   ```

## Categories

- **Action**: High-octane action games with mods
- **RPG**: Immersive role-playing adventures
- **Strategy**: Think, plan, and conquer
- **Racing**: Speed through tracks with mods
- **Puzzle**: Challenge your mind
- **Multiplayer**: Play with friends online

## File Structure

```
ModStation/
├── index.html          # Main website file
├── style.css           # Styling and layout
├── script.js           # JavaScript functionality
├── images/             # Game thumbnails and assets
│   └── placeholder.svg # Placeholder image
└── README.md           # This file
```

## Customization

- **Colors**: Edit the CSS variables in `style.css` for custom colors
- **Fonts**: Change the Google Fonts import in `index.html`
- **Layout**: Modify the grid layouts in `style.css` for different arrangements

## Deployment

Simply upload all files to your web server. No special configuration needed!

## Support

For questions or support, use the contact form on the website or reach out to the developer.

---

**Disclaimer**: Ensure all uploaded content complies with copyright laws and platform policies.