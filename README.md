# Stephen Yousif Ashara — Portfolio

> Personal portfolio website for **Stephen Yousif Ashara** — Pharmaceutical Quality Assurance & Supply Chain Specialist with 6+ years of experience in South Sudan's public health sector.

**Live site:** [https://YOUR-USERNAME.github.io/stephen-portfolio](https://YOUR-USERNAME.github.io/stephen-portfolio)

---

## ✨ Features

- **Fully static** — pure HTML, CSS & vanilla JS. No build tools, no dependencies.
- **Custom cursor** with smooth lerp animation
- **Scroll-triggered animations** via a self-contained AOS (Animate On Scroll) system
- **Responsive** — mobile-first, works on all screen sizes
- **Accessible** — semantic HTML5, proper ARIA labels, keyboard navigable
- **Fast** — single CSS file, single JS file, no frameworks
- **GitHub Pages ready** — push and deploy in minutes

---

## 📁 Project Structure

```
stephen-portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styles (tokens, components, responsive)
├── js/
│   └── main.js         # Cursor, scroll, animations, form handler
├── assets/             # Place your profile photo or other images here
└── README.md
```

---

## 🚀 Deploy to GitHub Pages (Step-by-Step)

### 1. Create a GitHub repository

1. Go to [github.com](https://github.com) and sign in (or create a free account).
2. Click **"New repository"**.
3. Name it: `stephen-portfolio` (or any name you like).
4. Set it to **Public**.
5. Click **"Create repository"**.

### 2. Upload your files

**Option A — Via GitHub website (easiest):**
1. Open your new repository.
2. Click **"Add file" → "Upload files"**.
3. Drag and drop the entire `stephen-portfolio` folder contents.
4. Click **"Commit changes"**.

**Option B — Via Git (command line):**
```bash
cd stephen-portfolio
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/stephen-portfolio.git
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository → **Settings** tab.
2. Scroll to **"Pages"** in the left sidebar.
3. Under **"Branch"**, select `main` and folder `/root`.
4. Click **Save**.
5. Wait ~60 seconds, then visit:
   ```
   https://YOUR-USERNAME.github.io/stephen-portfolio/
   ```

---

## 🎨 Customisation

| What to change | Where |
|---|---|
| Your name / bio / contacts | `index.html` |
| Colors, fonts, spacing | `css/style.css` (`:root` tokens at the top) |
| Animations & form behaviour | `js/main.js` |
| Add a profile photo | Place image in `assets/`, reference in `index.html` |

### To add a profile photo

Place your photo (e.g. `photo.jpg`) inside the `assets/` folder, then add this inside `.hero-right` in `index.html`:

```html
<img src="assets/photo.jpg" alt="Stephen Yousif Ashara" class="hero-photo" />
```

And in `css/style.css`:

```css
.hero-photo {
  width: 220px; height: 220px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid var(--gold);
  margin-bottom: 2rem;
}
```

---

## 📬 Contact Form

The contact form uses a `mailto:` link — clicking **Send Message** opens the visitor's default email client pre-filled with the message. No backend or server required.

---

## 📄 License

© 2026 Stephen Yousif Ashara. All rights reserved.
