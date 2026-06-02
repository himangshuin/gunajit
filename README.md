# Gunajit Kalita — Personal Website

Personal website for **Gunajit Kalita** — Assamese lyricist, poet, composer, social worker and Scientific Officer from Assam, India.

🔗 Instagram: [@gunajit.0](https://www.instagram.com/gunajit.0/)  
🎬 YouTube: [@gunajitkalita6667](https://www.youtube.com/@gunajitkalita6667/videos)

---

## Files Included

| File | Description |
|------|-------------|
| `index.html` | Home page — hero, about preview, works, lyric wall, FAQ |
| `about.html` | Full biography, timeline, values, skills |
| `songs.html` | Songs & lyrics with filterable grid |
| `poems.html` | Poetry page with filterable poems |
| `contact.html` | Contact form, collaboration types, FAQ |
| `style.css` | Shared stylesheet |
| `sitemap.xml` | ✅ Sitemap for Google indexing |
| `robots.txt` | ✅ Crawler instructions for Google |
| `.github/workflows/deploy.yml` | ✅ Auto-deploy to GitHub Pages |

---

## Step 1 — Create GitHub Repository

1. Go to [github.com](https://github.com) and sign in (create a free account if needed)
2. Click **New repository** (green button or `+` icon top-right)
3. Repository name: `gunajitkalita` ← **use this exactly** (your URL will be `username.github.io/gunajitkalita`)
   - OR name it exactly your GitHub username for `username.github.io` as the URL (cleanest)
4. Set visibility to **Public**
5. Click **Create repository** (leave all checkboxes empty)

---

## Step 2 — Upload All Files

**Method A — Browser Upload (No coding needed):**

1. In your new empty repository, click **Add file → Upload files**
2. Drag and drop **ALL** these files and folders:
   - `index.html`
   - `about.html`
   - `songs.html`
   - `poems.html`
   - `contact.html`
   - `style.css`
   - `sitemap.xml`
   - `robots.txt`
   - The `.github` folder (entire folder — drag it in)
3. Scroll down, write commit message: `Initial commit`
4. Click **Commit changes**

> ⚠️ **Important:** You must upload the `.github/workflows/deploy.yml` file for auto-deploy to work.  
> On Mac, hidden folders (starting with `.`) may not show by default — press `Cmd+Shift+.` to reveal them.

**Method B — Git Command Line:**

```bash
cd /path/to/gunajit-folder
git init
git add .
git commit -m "Initial commit — Gunajit Kalita website"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/gunajitkalita.git
git push -u origin main
```

---

## Step 3 — Enable GitHub Pages

1. In your repository, click the **Settings** tab
2. In the left sidebar, click **Pages**
3. Under **Build and deployment → Source**, select: **GitHub Actions**
4. GitHub will detect the `.github/workflows/deploy.yml` automatically
5. Wait **2–3 minutes**
6. Your live URL will appear at the top of the Pages settings:

```
https://YOUR-USERNAME.github.io/gunajitkalita/
```

---

## Step 4 — Update sitemap.xml with Your Real URL

Once you know your GitHub username, open `sitemap.xml` and replace all instances of:
```
https://gunajitkalita.github.io/
```
with your real URL, e.g.:
```
https://YOUR-ACTUAL-USERNAME.github.io/gunajitkalita/
```

Then re-upload `sitemap.xml` to GitHub.

Also update `robots.txt`:
```
Sitemap: https://YOUR-ACTUAL-USERNAME.github.io/gunajitkalita/sitemap.xml
```

---

## Step 5 — Submit to Google (Get Ranked!)

This is how Google finds and indexes your site:

### 5a — Google Search Console

1. Go to [search.google.com/search-console](https://search.google.com/search-console)
2. Click **Add property**
3. Choose **URL prefix** and enter your GitHub Pages URL
4. Verify ownership: choose **HTML tag** method, copy the meta tag, add it inside `<head>` of `index.html`, re-upload, then click Verify
5. After verification, go to **Sitemaps** in the left menu
6. Enter: `sitemap.xml` and click **Submit**
7. Google will begin crawling within 1–7 days

### 5b — Speed up indexing

In Google Search Console:
- Go to **URL Inspection**
- Enter your homepage URL
- Click **Request Indexing**

Repeat for all 5 pages.

---

## Custom Domain (Optional but Recommended)

For a domain like `gunajitkalita.com`:

1. Buy domain from [Namecheap](https://namecheap.com) (~₹1,000/year)
2. In GitHub **Settings → Pages**, enter your custom domain
3. At Namecheap (or your registrar), add:
   - **CNAME record**: `www` → `YOUR-USERNAME.github.io`
   - **A records** (for root domain) pointing to GitHub's IPs:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```
4. GitHub auto-provisions SSL (https) within 24 hours
5. Update `sitemap.xml` and `robots.txt` with your custom domain URL

---

## SEO Features Already Built In

✅ **Meta tags** — title, description, author on all pages  
✅ **Canonical URLs** — prevents duplicate content penalties  
✅ **Open Graph** — rich previews on WhatsApp, Facebook, LinkedIn  
✅ **Twitter Card** — rich previews on Twitter/X  
✅ **JSON-LD Schema** — Google Knowledge Panel (Person, WebSite, CollectionPage)  
✅ **sitemap.xml** — tells Google all your pages  
✅ **robots.txt** — points Google to sitemap  
✅ **Mobile-responsive** — Google ranks mobile-first  
✅ **Fast loading** — pure HTML/CSS, no heavy frameworks  
✅ **FAQ structured content** — targets "Who is Gunajit Kalita" type searches  
✅ **Assamese script** — targets searches in Assamese language  

---

## Updating Content

To change any text or add new songs/poems:
1. Open the relevant `.html` file in any text editor (Notepad, VS Code, etc.)
2. Make your changes and save
3. Upload the updated file to GitHub (same drag-and-drop process)
4. Site updates in ~1 minute automatically

---

## Design

- **Palette:** Dark ink (`#0c0b09`) · Gold accents (`#c9a84c`) · Teal highlights (`#4a8b7e`)
- **Fonts:** Playfair Display · Cormorant Garamond · DM Mono · Spectral
- **Style:** Literary, poetic — grain texture, ambient glows, scroll animations
- **Mobile:** Fully responsive on all screen sizes

---

*Pure HTML & CSS — no frameworks, no build step, no dependencies.*  
*Preview locally: just open any `.html` file in a browser.*

© 2025 Gunajit Kalita · সংগ্রামৰ আন এটি নাম জীৱন
