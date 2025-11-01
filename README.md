# Crypto Seed Validator - Educational Tool

Educational website that protects users from seed phrase phishing scams. Appears as a legitimate validator but immediately clears any input and displays security warnings.

## How It Works

1. User attempts to type or paste a seed phrase into the input field
2. JavaScript intercepts the input event immediately
3. Input field is cleared before any data can be entered
4. Warning banner displays with security education content

## Technical Implementation

- Single-file static site (`index.html`)
- Pure HTML/CSS/JavaScript - no dependencies
- Client-side only - zero data transmission
- Event listeners: `input`, `paste`, `contextmenu`
- Input cleared on first character typed

## Deployment

**Cloudflare R2:**
1. Upload `index.html` to R2 bucket
2. Configure public access
3. Access via R2 URL or custom domain

**Other options:** GitHub Pages, Netlify, Vercel, AWS S3, or any web server.

## Security

- No data storage or transmission
- All processing happens client-side in browser
- No network requests
- No cookies or tracking

## Supported Cryptocurrencies

Displays support for: Bitcoin, Solana, Ethereum, Polygon, Avalanche, Cardano

---

**Warning**: This is an educational tool only. Never enter real seed phrases online.
