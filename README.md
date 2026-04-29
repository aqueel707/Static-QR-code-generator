# QR Code Generator

A minimalist static QR code generator that runs entirely in the browser. 
Website live at  https://aqueel707.github.io/Static-QR-code-generator/

## Features

- **Pure Static Generation** – QR codes are generated locally in your browser using JavaScript. No data is sent to any server.
- **Customizable Appearance** – Choose from multiple sizes (128px to 1024px) and select any color for your QR code.
- **Instant Download** – Export your QR code as a PNG image with one click.
- **Responsive Design** – Works beautifully on desktop, tablet, and mobile devices.
- **Keyboard Friendly** – Press `Enter` to generate, `Shift + Enter` for new lines in the input.
- **No Build Step** – Single HTML file. Just open and use.

## Use Cases

- **URLs & Websites** – Share any link instantly
- **Google Maps Locations** – Paste Maps share links (`maps.app.goo.gl/...`) or coordinates
- **WiFi Credentials** – Generate codes for network access
- **Contact Cards (vCard)** – Encode contact information
- **Plain Text** – Any text data up to ~3KB
- **Payment Links** – Venmo, PayPal, or crypto addresses

## How to Use

1. Open `index.html` in any modern browser
2. Enter your text, URL, or data in the input field
3. Select your preferred size and color
4. Click **Generate QR Code** or press `Enter`
5. Download the PNG and use it anywhere

### Google Maps Example

Paste a Google Maps share link directly:

```
https://maps.app.goo.gl/AbCdEfGhIjKlMnOp
```

Or use coordinates:

```
https://www.google.com/maps?q=48.8584,2.2945
```

## Tech Stack

- **HTML5** – Semantic markup
- **CSS3** – Custom properties, flexbox, grid, animations
- **Vanilla JavaScript** – No frameworks, no dependencies except QRCode.js
- **[QRCode.js](https://github.com/davidshimjs/qrcodejs)** – Client-side QR generation library (loaded via CDN)



## Customization

The design uses CSS custom properties for easy theming:

```css
:root {
  --bg: #fafafa;           /* Background color */
  --surface: #ffffff;      /* Card background */
  --text: #1a1a1a;         /* Primary text */
  --accent: #2563eb;       /* Focus states */
  --border: #e5e5e5;       /* Borders */
}
```

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Android)

## License

MIT License – feel free to use, modify, and distribute.

## Acknowledgments

- QR generation powered by [QRCode.js](https://github.com/davidshimjs/qrcodejs)
- Typography: [Inter](https://rsms.me/inter/) by Rasmus Andersson
