AJTECH.DEV — DIGITAL IDENTITY KIT
================================

Main website: index.html
Original profile image: profile.webp
AJTech brand mark: aj-mark.png
Social preview: ajtech-preview-v2.jpg (1200 x 630 pixels)
QR for public card: ajtech-qr.png
Reusable developer credit: DEVELOPER_FOOTER_SNIPPET.html

PUBLISH ON GITHUB PAGES
1. Extract this ZIP. Do NOT upload the ZIP itself as a site.
2. Open https://github.com/ranaasad-dev/ajtech-connect
3. Upload the files from this ZIP into the root of the existing repository.
4. Replace the old index.html and keep all accompanying image files. Commit.
5. Wait for GitHub Pages deployment. Check the live website:
   https://ranaasad-dev.github.io/ajtech-connect/

FUNCTIONS
- View work: opens portfolio.
- WhatsApp: opens direct chat (number not displayed on card).
  NOTE: The recipient number can still be revealed by inspecting the wa.me destination.
- LinkedIn / GitHub: external profiles.
- Email: Gmail compose; alternative opens default email app.
- Save Contact: downloads vCard with name, email and professional links, no phone number.
- Share Card: device share sheet or copy link fallback.
- QR Code: opens a scannable QR, downloadable for posters and banners.

DEVELOPER CREDIT
- Open DEVELOPER_FOOTER_SNIPPET.html and copy the short snippet into
  the footer of any client website, with the client's permission.
- The credit always links back to the same central AJTech.dev digital card.
- Do not overwrite other websites' brand identity with AJTech.dev branding.

TECHNICAL
- Static HTML/CSS/JavaScript, no server, tracker, external font or JavaScript dependency.
- Inline SVG icons; responsive layout; large enough controls; keyboard support.
- Image loading and page performance depend on browser/network.
- Social preview display is controlled by each messaging platform and may be cached.
- To change email or URLs, edit links + contact constants in index.html.
