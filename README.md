# Yuelong Xiao — Academic Homepage

> Assistant Professor @ College of Forestry, Guangxi University  
> Forest Parameter Mapping & Ecological Remote Sensing

## 🚀 Deployment Guide

### Option 1: GitHub Pages (Recommended · Free)

1. **Create a GitHub repository**  
   - Name: `yuelongxiao.github.io` (or any name, e.g. `academic-homepage`)
   - Public repo

2. **Push files**  
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial commit: academic homepage"
   git remote add origin https://github.com/YOUR_USERNAME/yuelongxiao.github.io.git
   git push -u origin main
   ```

3. **Enable Pages**  
   Repository → Settings → Pages → Source: "Deploy from branch" → main → / (root) → Save

4. **Visit**  
   `https://YOUR_USERNAME.github.io` (if repo named `YOUR_USERNAME.github.io`)  
   or `https://YOUR_USERNAME.github.io/academic-homepage/`

### Option 2: Custom Domain

In Settings → Pages, add your custom domain and add a CNAME record in DNS.

## ✏️ How to Maintain

Everything is in **one file** (`index.html`). Open it in any text editor:

| To change | Search for |
|-----------|-----------|
| Email | `yuelong_x@126.com` |
| GitHub link | `github.com/yourname` |
| Google Scholar / ORCID | `#` placeholder links |
| Avatar initial letter | `hero-avatar` div (change "Y" to your photo) |
| Bio text | Edit under `<section id="about">` |

### Adding a Publication

Add this template inside `<ul class="pub-list">`:

```html
<li class="pub-item">
    <div class="pub-year">2025</div>
    <div class="pub-info">
        <div class="title"><a href="https://doi.org/xxx">Paper Title</a></div>
        <div class="authors">Author 1, <u>Xiao, Y.</u>, Author 3</div>
        <div class="journal"><em>Journal Name</em>, vol. X, pp. Y–Z</div>
        <div class="pub-tags">
            <span class="pub-tag pdf">PDF</span>
            <span class="pub-tag code">Code</span>
        </div>
    </div>
</li>
```

### Adding a Project

Copy a `<li class="timeline-item">` block inside the timeline list.

## 🎨 Tech Stack

- Pure HTML + CSS + JS, zero dependencies
- Fonts: Inter (English) + Noto Sans SC (Chinese fallback)
- Icons: Font Awesome + Academicons
- Responsive (mobile, tablet, desktop)
- Single file, no server, no database

---

**Made with 🦐 by 虾米**
