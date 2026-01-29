# Novaxia – Online Meeting Booking Page

This repository contains a lightweight, static landing page hosted on **GitHub Pages**, designed to allow clients to easily book advisory meetings through **Calendly**.

It includes:
- a central booking overview page with all meeting types, and
- dedicated landing pages for individual meeting types, allowing direct links to be shared with clients.

---

## ✨ Features

- Clean, minimal UI with subtle animations
- Responsive layout (mobile, tablet, desktop)
- Overview page with multiple meeting types displayed as cards
- Dedicated landing pages for individual meeting types
- Direct Calendly integration (no backend required)
- Custom branding (logo, colors, favicon)
- Hosted entirely on GitHub Pages

---

## 🗂 Project Structure
```
/
├─ index.html                # Redirect or language selector (optional)
├─ styles.css
├─ assets/
|  ├─ favicon.ico
│  └─ logo.png
│
├─ en/
│  ├─ index.html
│  └─ meetings/
|     ├─ advisor.hmtl
│     ├─ banking.html
|     ├─ business.html
|     ├─ call.html
|     ├─ investment.html
|     ├─ legal.html
│     ├─ property.html
│     ├─ legal.html
│     └─ tax_accounting.html
│
└─ gr/
   ├─ index.html
   └─ meetings/
     ├─ advisor.hmtl
     ├─ banking.html
     ├─ business.html
     ├─ call.html
     ├─ investment.html
     ├─ legal.html
     ├─ property.html
     ├─ legal.html
     └─ tax_accounting.html

Each language is organized in its own folder, sharing common styles and assets.
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

1. Client opens a booking page (overview or direct link)
2. Client selects the meeting option
3. Client is redirected to Calendly
4. Date and time are selected
5. Booking is confirmed via Calendly

---

## License

This project is licensed under the MIT License.

The license applies to the source code only.  
Branding assets, including the Novaxia name, logo, and written content, are not licensed for reuse.

---

If you need enhancements such as inline Calendly embeds, analytics, or custom domains, the structure is ready to support them.
