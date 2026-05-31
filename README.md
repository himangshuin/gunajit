# Gunajit Kalita — Personal Website

Personal website for **Gunajit Kalita** — Assamese lyricist, poet, composer, social worker and Scientific Officer from Assam, India.

🔗 Instagram: [@gunajit.0](https://www.instagram.com/gunajit.0/)
🎬 YouTube: [@gunajitkalita6667](https://www.youtube.com/@gunajitkalita6667/videos)

---

## Pages

| File | Description |
|------|-------------|
| `index.html` | Home — hero, about preview, featured works, lyric wall, links |
| `about.html` | Full biography, creative timeline, values, skills |
| `songs.html` | Songs & lyrics with filterable grid, featured song |
| `poems.html` | Poetry page with filterable poems, quote wall |
| `contact.html` | Contact form, collaboration types, FAQ |
| `style.css` | Shared stylesheet (imported by all pages) |

---

## Hosting on GitHub Pages

### Step 1 — Create a GitHub Repository

1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click **New repository** (green button or `+` icon)
3. Name it: `gunajit-kalita` (or anything you like)
4. Set visibility to **Public**
5. Leave everything else as default and click **Create repository**

### Step 2 — Upload the Files

**Option A — Upload via browser (easiest):**
1. Open your new repository
2. Click **Add file → Upload files**
3. Drag and drop ALL files: `index.html`, `about.html`, `songs.html`, `poems.html`, `contact.html`, `style.css`
4. Click **Commit changes**

**Option B — Using Git (for developers):**
```bash
git init
git add .
git commit -m "Initial commit — Gunajit Kalita website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/gunajit-kalita.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repository → **Settings** tab
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Branch: `main`, folder: `/ (root)` → click **Save**
5. Wait 1–2 minutes, then your site will be live at:

```
https://YOUR-USERNAME.github.io/gunajit-kalita/
```

---

## Custom Domain (Optional)

If you want a custom domain like `gunajitkalita.com`:

1. Buy a domain from Namecheap, GoDaddy, or similar
2. In **Settings → Pages**, enter your custom domain
3. At your domain registrar, add a CNAME record pointing to `YOUR-USERNAME.github.io`
4. GitHub will auto-provision an SSL certificate within 24 hours

---

## Updating Content

To update any text, images, or links:
1. Open the relevant `.html` file in any text editor (Notepad, VS Code, etc.)
2. Make your changes
3. Upload the updated file to GitHub (same upload process as above)
4. Changes go live in 1–2 minutes

---

## Design

- **Palette:** Dark ink background (`#0c0b09`) with gold accents (`#c9a84c`) and teal highlights
- **Fonts:** Playfair Display (headings), Cormorant Garamond (poetry), DM Mono (labels), Spectral (body)
- **Style:** Literary, poetic — grain texture, ambient glows, scroll-triggered animations
- **Responsive:** Mobile-first, works on all screen sizes

---

## Structure

```
gunajit-kalita/
├── index.html     ← Home page
├── about.html     ← About page
├── songs.html     ← Songs & Lyrics
├── poems.html     ← Poetry
├── contact.html   ← Contact & Collaboration
├── style.css      ← Shared styles
└── README.md      ← This file
```

---

*Built with pure HTML & CSS — no frameworks, no build step, no dependencies.*
*Just open any `.html` file in a browser to preview locally.*
