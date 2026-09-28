# Naveen's contact page

Live at https://naveenvenk17.github.io/network-site/

A static, mobile-first contact page hosted with GitHub Pages. No build step, tracking, or external frontend dependencies.

- Edit `index.html` for links and visible details, `style.css` for appearance.
- Edit `naveen-venkat.vcf` when contact details change (keep CRLF line endings).
- `assets/naveen-wallpaper.png` is a 1170 × 2532 phone wallpaper. Keep the complete white QR square visible when setting it as wallpaper.
- `assets/contact-qr.png` is the standalone QR code. It points to the live page, so changes to the page do not require a new QR.

GitHub Pages publishes the root of the `main` branch. Contact saving opens/downloads a vCard; the receiving phone controls the final import/save confirmation. WhatsApp pre-fills a message without sending it.

Preview locally with `python3 -m http.server 8765`.
