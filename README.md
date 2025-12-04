# Warehouse Management Landing Page

A professional static landing page for warehouse management services with WhatsApp integration for customer inquiries.

## Features

- 🏭 Modern, responsive landing page design
- 📱 WhatsApp integration for instant customer contact
- 📦 Showcase of warehouse management services:
  - Inventory Management
  - Order Fulfillment
  - Storage Solutions
  - Real-Time Tracking
  - Supply Chain Optimization
  - Distribution Services
- 🎨 Clean, professional UI with smooth animations
- 📧 Contact form with email input
- 🌐 Fully responsive (mobile, tablet, desktop)

## Quick Start

1. Clone this repository
2. Configure your WhatsApp number (see Configuration section)
3. Open `index.html` in a browser to preview
4. Deploy to GitHub Pages (see Deployment section)

## Configuration

### Setting Up Your WhatsApp Number

To receive inquiries via WhatsApp, you need to update the phone number in `index.html`:

1. Open `index.html` in a text editor
2. Find this line near the bottom of the file (in the `<script>` section):
   ```javascript
   const WHATSAPP_PHONE_NUMBER = '919876543210'; // <-- CHANGE THIS TO YOUR WHATSAPP NUMBER
   ```
3. Replace `919876543210` with your WhatsApp Business phone number

**Phone Number Format:**
- Use country code + phone number
- No spaces, no `+` symbol, no dashes
- Examples:
  - US: `14155551234` (1 = US country code)
  - UK: `447911123456` (44 = UK country code)
  - India: `919876543210` (91 = India country code)
  - Brazil: `5511999999999` (55 = Brazil country code)

### Customizing Contact Information

To update the displayed email address:
1. Open `index.html`
2. Find the contact section and update `spacesafestorage@spacesafestoragemalaysia` with your email

## Deployment

### GitHub Pages Setup

1. **Push your changes to GitHub**
   ```bash
   git add .
   git commit -m "Add landing page"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click **Settings** → **Pages** (in the left sidebar)
   - Under **Source**, select **Deploy from a branch**
   - Under **Branch**, select `main` and `/ (root)`
   - Click **Save**

3. **Access your site**
   - Wait 1-2 minutes for deployment
   - Your site will be available at: `https://<username>.github.io/<repository-name>/`

### Using a Custom Domain (Optional)

1. In GitHub Pages settings, enter your custom domain
2. Add a CNAME record in your DNS settings pointing to `<username>.github.io`
3. Wait for DNS propagation (can take up to 24 hours)

## Project Structure

```
warehouse-management/
├── index.html      # Main landing page
├── styles.css      # Styling
└── README.md       # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## Customization

### Changing Colors

The color scheme can be customized in `styles.css`. Look for the `:root` section:

```css
:root {
    --primary-color: #2563eb;      /* Main blue color */
    --primary-dark: #1d4ed8;       /* Darker blue */
    --secondary-color: #1e3a5f;    /* Navy blue */
    --accent-color: #10b981;       /* Green for buttons */
    --text-dark: #1f2937;          /* Dark text */
    --text-light: #6b7280;         /* Light text */
}
```

### Adding More Services

To add or modify services, edit the services section in `index.html`:

```html
<div class="service-card">
    <div class="service-icon">🔧</div>
    <h3>Your Service Name</h3>
    <p>Your service description here.</p>
</div>
```

## License

This project is open source and available for personal and commercial use.

---

**Need help?** Contact us via WhatsApp using the form on the landing page!
