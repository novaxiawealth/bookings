# Novaxia – Online Meeting Booking Page

This repository contains a lightweight, static landing page hosted on **GitHub Pages**, designed to allow clients to easily book advisory meetings through **Calendly**.

The page presents multiple meeting types in a clean, professional layout and redirects users directly to the corresponding Calendly scheduling links.

---

## ✨ Features

- Clean, minimal UI with subtle animations
- Responsive layout (mobile, tablet, desktop)
- Multiple meeting types displayed as cards
- Direct Calendly integration (no backend required)
- Custom branding (logo, colors, favicon)
- Hosted entirely on GitHub Pages

---

## 🗂 Project Structure
```
├─ index.html # Main booking page
├─ styles.css # Page styling
└─ assets/
├─ logo.png # Organization logo
└─ favicon.ico # Site favicon
```
---

## 🔧 Customization

To adapt this page to your needs:

1. **Update meeting links**
   - Replace the Calendly URLs in `index.html` with your own event-type links.

2. **Change branding**
   - Replace `assets/logo.png` with your logo.
   - Update colors in `styles.css` (CSS variables at the top).

3. **Adjust layout**
   - Control how many meeting cards appear per row by editing the `.grid` CSS rule.

---

## 🚀 Deployment

This site is deployed using **GitHub Pages**.

To publish:
1. Push the repository to GitHub
2. Go to **Settings → Pages**
3. Select the `main` branch and root directory
4. Access the site via the generated GitHub Pages URL

---

## 📅 Booking Flow

1. User selects a meeting type
2. User is redirected to Calendly
3. User chooses date & time
4. Booking is confirmed via Calendly

---

## License

This project is licensed under the MIT License.

The license applies to the source code only.  
Branding assets, including the Novaxia name, logo, and written content, are not licensed for reuse.

---

If you need enhancements such as inline Calendly embeds, analytics, or custom domains, the structure is ready to support them.
