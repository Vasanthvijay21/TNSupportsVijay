# People Support for CM Vijay
### மக்கள் ஆதரவு · முதல்வர் விஜய்

An **independent citizen-created celebration platform** for Tamil Nadu's democratic milestone.

> ⚖️ **Disclaimer:** This website is not affiliated with the Government of Tamil Nadu, Election Commission of India, TVK party, or any official government authority. This is an independent citizen expression platform for peaceful democratic celebration only.

---

## Features

- 📸 Upload your photo (JPG, PNG, WEBP, up to 10MB)
- 🎨 6 cinematic poster styles
- 🌐 Tamil + English bilingual support
- 📲 Share to WhatsApp, Telegram, Facebook, X/Twitter, Instagram
- 🔒 100% client-side — your photo never leaves your device
- 📱 Mobile-first, PWA installable
- ✅ Graceful error handling

---

## Project Structure

```
cm-vijay-support/
├── index.html      ← Complete single-file app
├── sw.js           ← Service worker (PWA offline)
├── manifest.json   ← PWA manifest
├── robots.txt      ← SEO
├── sitemap.xml     ← SEO
└── README.md
```

---

## Deploy FREE on GitHub Pages

### Step 1: Create GitHub Repository

```bash
# Go to github.com → New repository
# Name: cm-vijay-support
# Public repository
# Don't initialize with README (you have one)
```

### Step 2: Push Code

```bash
# In your project folder:
git init
git add .
git commit -m "Initial commit: CM Vijay Support Platform"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/cm-vijay-support.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Click **Pages** in left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Select **main** branch, **/ (root)** folder
6. Click **Save**

### Step 4: Access Your Site

Your site will be live at:
```
https://YOUR_USERNAME.github.io/cm-vijay-support/
```

(Takes 2-5 minutes to go live after first deploy)

---

## Update sitemap.xml

After deploying, update the URL in `sitemap.xml` and `robots.txt`:

```xml
<!-- sitemap.xml - replace the loc URL -->
<loc>https://YOUR_USERNAME.github.io/cm-vijay-support/</loc>
```

Then push the update:
```bash
git add sitemap.xml robots.txt
git commit -m "Update sitemap with live URL"
git push
```

---

## Tech Stack

- **HTML5 Canvas API** — poster generation
- **CSS3** — glassmorphism, animations, responsive design  
- **Vanilla JavaScript** — no frameworks
- **html2canvas** — loaded from CDN (cdnjs.cloudflare.com)
- **Google Fonts** — Cinzel, Noto Sans Tamil, Playfair Display, DM Sans
- **Web Share API** — native sharing on mobile
- **Service Worker** — PWA offline support

---

## Legal & Compliance

This platform strictly follows:
- Indian Information Technology Act, 2000
- Representation of People Act guidelines
- No hate speech, no misinformation
- No official government logos or seals
- Clearly labeled as citizen-created, non-official platform

---

## Privacy

- Zero data collection
- No server, no database, no analytics
- All image processing in-browser (Canvas API)
- No cookies set by this site

---

## License

This project is released for educational and civic expression purposes. The creators disclaim all liability for user-generated content created using this tool. Users are responsible for ensuring they have rights to photos they upload.

---

*Independent Citizen Platform · Not affiliated with any government or official body*
