RK Creative BD — Website (Static HTML/CSS/JS)
===================================================

How to use
----------
1) Open `index.html` in your browser to preview.
2) Replace placeholders:
   - `assets/profile.jpg` -> your real profile photo.
   - `assets/portfolio/*` -> your best designs (JPG/PNG).
   - `assets/foodfolio/*` -> your food & beverage works.
3) Update links/emails:
   - In `index.html`, search for `https://facebook.com/`, `instagram.com`, etc.
   - Replace WhatsApp number in the Contact section: `https://wa.me/8801XXXXXXXXX`.
   - Replace `tel:+8801XXXXXXXXX` and `youremail@example.com`.
4) Edit colors/animations in `css/style.css`.
5) Deploy for free:
   - GitHub: create a repo and upload these files, enable GitHub Pages (Settings → Pages → Deploy from branch → `root`).
   - Netlify/Vercel: drag & drop the folder and deploy.

Notes
-----
- The site is single-page with sections (Home, Services, Portfolio, Foodfolio, About, Contact).
- Smooth animations are controlled by `data-animate` + IntersectionObserver in `js/app.js`.
- The gallery opens images in a simple lightbox.
- The calendar is a simple demo that randomly marks weekends as booked/available — replace with your real availability if needed.
- Everything is designed with a dark red gradient theme.

Enjoy! — Built for RK Creative BD
