# ARTSIDE — Flex Voke Artist Website

Official website for **Onosedere Flex Voke** — Inter-Disciplinary Artist, Muralist & Interior Decorator.
Built by ARTSIDE | [flex_voke on Instagram](https://www.instagram.com/flex_voke)

---

## 🗂 Project Structure

```
artside/
├── index.html          ← Main website (Home, Services, Contact — single file)
├── css/
│   └── style.css       ← All styles
├── js/
│   └── main.js         ← Navigation, scroll reveal, lightbox
├── images/             ← All artwork & portrait images
└── README.md
```

---

## 🚀 How to Host on GitHub Pages

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click the **+** icon → **New repository**
3. Name it: `artside` (or `flex-voke` or anything you like)
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload the Files
**Option A — Drag & Drop (easiest):**
1. On the new repo page, click **uploading an existing file**
2. Drag the entire `artside` folder contents into the window
3. Make sure the structure is: `index.html` at the root, `css/`, `js/`, `images/` as folders
4. Click **Commit changes**

**Option B — Using Git (for developers):**
```bash
cd artside
git init
git add .
git commit -m "Initial website launch"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/artside.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. In your repository, go to **Settings**
2. Scroll down to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch, **/ (root)** folder
5. Click **Save**

### Step 4 — Your site is live! 🎉
GitHub will give you a URL like:
```
https://YOUR_USERNAME.github.io/artside/
```
It may take 1–2 minutes to go live the first time.

---

## 🌐 Custom Domain (Optional)
If you have a domain like `artsideng.com`:
1. In GitHub Pages settings, add your custom domain
2. In your domain registrar's DNS, add a CNAME record pointing to `YOUR_USERNAME.github.io`

---

## ✏️ How to Update Content

**To change text:** Open `index.html` and search for the text you want to edit.

**To swap an image:** Replace the file in the `images/` folder with the same filename.

**To add a new portfolio image:** Add the image to `images/` and copy one of the `portfolio-item` blocks in `index.html`.

---

## 📱 Features
- ✅ Fully responsive — mobile first
- ✅ Smooth scroll-reveal animations
- ✅ Image lightbox (click any artwork to enlarge)
- ✅ WhatsApp direct message with pre-filled text
- ✅ 3-page structure: Home, Services, Contact
- ✅ No frameworks — pure HTML, CSS, JS
- ✅ Fast loading — no dependencies except Google Fonts

---

## 📞 Contact
**WhatsApp:** +234 701 301 6802
**Email:** Artside@atomicmail.io
**Instagram:** [@flex_voke](https://www.instagram.com/flex_voke)
