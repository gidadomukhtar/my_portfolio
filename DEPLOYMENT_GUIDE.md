# 🚀 Deployment Guide: Gidado's Portfolio + Blog

**Domain:** `gidadomukhta.me` (Namecheap)

---

# 📋 FILES YOU HAVE

```
index.html          → Main portfolio page
blog.html           → NEW: Professional blog page
style.css           → Shared styles
script.js           → Shared functionality
README.md           → Documentation
```

---

# 🔧 QUICK FIX FOR index.html

**Update the navigation link in `index.html`:**

**Find this line:**
```html
<li><a href="blog.html">Skills</a></li>
```

**Replace with:**
```html
<li><a href="blog.html">Blog</a></li>
```

---

# 📂 DEPLOYMENT OPTIONS

## **Option A: Vercel (FASTEST - 5 minutes)**

**Step 1: Create Vercel account**
- Go to `vercel.com`
- Sign up with GitHub

**Step 2: Deploy**
1. Create folder: `my-portfolio`
2. Put all files (index.html, blog.html, style.css, script.js) inside
3. Push to GitHub
4. Import project in Vercel
5. Vercel auto-deploys on every push

**Step 3: Point domain**
1. In Vercel: Settings → Domains
2. Add: `gidadomukhta.me`
3. In Namecheap:
   - Go to DNS settings
   - Add CNAME: `gidadomukhta.me` → `cname.vercel.com`
   - Wait 24 hours for DNS propagation

**Cost:** FREE

---

## **Option B: GitHub Pages (COMPLETELY FREE)**

**Step 1: Create GitHub repo**
```bash
git clone https://github.com/gidadomukhtar/portfolio.git
cd portfolio
# Add all your files
git add .
git commit -m "Initial portfolio"
git push origin main
```

**Step 2: Enable Pages**
1. Go to repo Settings
2. Pages → Source: `main` branch
3. GitHub generates: `gidadomukhtar.github.io`

**Step 3: Point custom domain**
1. In GitHub Pages settings: Add `gidadomukhta.me`
2. In Namecheap:
   - DNS Records → Add A record
   - IP: `185.199.108.153` (GitHub Pages)
   - Or CNAME: `gidadomukhtar.github.io`

**Cost:** FREE

---

## **Option C: Namecheap Hosting (SIMPLE)**

**Step 1: Setup hosting**
- Namecheap → Your domain → Hosting
- Set up cPanel hosting

**Step 2: Upload files**
- FTP to your hosting
- Upload all files to `/public_html`

**Step 3: Done**
- Visit `gidadomukhta.me`
- Should work immediately

**Cost:** ~$3-5/month

---

---

# ✅ RECOMMENDED: VERCEL (Option A)

**Why:**
- ✅ Fastest setup (5 min)
- ✅ Free forever
- ✅ Auto-deploys on GitHub push
- ✅ Professional for MVP portfolio
- ✅ Best performance

---

# 🎯 BLOG PAGE FEATURES

Your new blog.html includes:

✅ **8 blog posts** (you can edit with your real posts)  
✅ **Search functionality** (search by title/content)  
✅ **Category filtering** (.NET/C#, Azure, AI/ML, Architecture, Open Source)  
✅ **Responsive design** (mobile-friendly)  
✅ **Links to external posts** (Dev.to, Medium, LinkedIn)  
✅ **Smooth animations** (matches your portfolio style)  
✅ **Beautiful card layout** (dark theme with gold accents)  

---

# 📝 HOW TO CUSTOMIZE BLOG POSTS

**Edit `blog.html`:**

Find this section:
```html
<!-- POST 1 -->
<div class="blog-post" data-category="Open Source">
    <div class="post-header">
        <span class="post-category">Open Source</span>
        <h3 class="post-title">Your Title Here</h3>
        <div class="post-meta">
            <span>📅 Date</span>
            <span>⏱️ 5 min read</span>
        </div>
    </div>
    <div class="post-footer">
        <p class="post-excerpt">Your excerpt here...</p>
        <div class="post-links">
            <a href="YOUR_URL" class="post-link external" target="_blank">Read on Dev.to</a>
        </div>
    </div>
</div>
```

**What to change:**
- `data-category` → Category name (Open Source, C#, Azure, AI, Architecture)
- `post-title` → Post title
- Date → Publish date
- `post-excerpt` → 2-3 sentence summary
- `href` → Link to your actual post
- Link text → Where to read it

---

# 🔗 CATEGORY OPTIONS

Use these categories:
- `C#` → C#/.NET posts
- `Azure` → Azure/cloud posts
- `AI` → AI/ML posts
- `Architecture` → System design posts
- `Open Source` → Open source/GitHub posts

---

# 📊 CURRENT BLOG POSTS (EXAMPLES)

I've added 8 example posts based on your work:

1. **dotnet/docs PR** (Open Source)
2. **OpenTelemetry** (Architecture)
3. **Why .NET for African Markets** (C#)
4. **Understanding C# Variables** (C#)
5. **EF Core Performance** (Architecture)
6. **AI-Powered Healthcare** (AI)
7. **Azure DevOps CI/CD** (Azure)
8. **ErrorCopy Pro Extension** (Open Source)

**Replace with your actual posts as you write them.**

---

# 🚀 STEP-BY-STEP DEPLOYMENT (VERCEL)

**1. Download files**
- Save `blog.html`, `index.html`, `style.css`, `script.js` locally

**2. Create GitHub repo**
```bash
mkdir gidado-portfolio
cd gidado-portfolio
git init
git add .
git commit -m "Initial portfolio and blog"
git remote add origin https://github.com/gidadomukhtar/gidado-portfolio.git
git push -u origin main
```

**3. Deploy to Vercel**
- Go to `vercel.com`
- Import GitHub repo
- Click Deploy
- Done! Get URL like `gidado-portfolio.vercel.app`

**4. Add custom domain**
- In Vercel: Settings → Domains
- Add: `gidadomukhta.me`
- Follow DNS instructions (update Namecheap)

**5. Wait 24 hours**
- DNS propagation takes time
- Check: `gidadomukhta.me` works

---

# ✅ DEPLOYMENT CHECKLIST

- [ ] Update `index.html` navigation (blog link)
- [ ] Customize blog posts in `blog.html` (replace examples)
- [ ] Add your real post links (Dev.to, Medium, LinkedIn)
- [ ] Test locally: Open `index.html` in browser
- [ ] Push to GitHub
- [ ] Deploy to Vercel (or GitHub Pages)
- [ ] Add domain in Vercel settings
- [ ] Update Namecheap DNS
- [ ] Test: Visit `gidadomukhta.me`

---

# 💡 NEXT: CONTENT

Once deployed, add your **real blog posts**:

1. OpenTelemetry post → Dev.to + LinkedIn
2. ErrorCopy Pro post → Dev.to + LinkedIn
3. C# Learning Hub content → Dev.to + Medium
4. Your other technical articles

**Each post adds to your MVP portfolio.** 📈

---

# 📞 SUPPORT

**Having issues?**

1. Test locally first (open files in browser)
2. Check console for errors (F12)
3. Verify all files are in same folder
4. Check DNS propagation (24-48 hours)

---

**You're ready to deploy!** 🚀

Questions? Let me know.
