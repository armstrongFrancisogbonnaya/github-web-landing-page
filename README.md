# Gift Card Offers Landing Page

A responsive, animated landing page for gift card promotional offers with a premium dark purple and gold theme.

## Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Animated Elements**: 
  - Floating gift card badges with hover effects
  - Sparkle/particle animation falling from the top
  - Pulsing navigation buttons
  - Shimmer effects on text
- **Color Theme**: Deep purple (#1a0a2e, #2d1b4e) with gold (#ffd700) accents
- **Form**: Email and zip code collection with validation
- **Gift Card Display**: Animated $500 gift cards for Walmart, Amazon, Apple, PayPal, and Google Play

## How to Use

1. Clone this repository
2. Open `index.html` in a web browser
3. Or use a local server:

```bash
# Using Python
python -m http.server 3000

# Using Node.js (if you have http-server installed)
npx http-server -p 3000
```

Then visit `http://localhost:3000` in your browser.

## Customization

### Changing the Offer Link

Edit the JavaScript in `index.html` to change where the form submits:

```javascript
window.location.href = 'https://your-link-here.com';
```

### Changing Gift Card Values

Find and replace `$500` with your desired value in the HTML.

### Changing Colors

Update the CSS variables in the `<style>` section:
- Background: `#1a0a2e`, `#2d1b4e`
- Accents: `#6b21a8`, `#4c1d95`
- Gold: `#ffd700`, `#ffeb3b`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is provided as-is for promotional landing page purposes.

## Credits

Designed for Affilomint Exclusive CPA Network gift card promotions.
