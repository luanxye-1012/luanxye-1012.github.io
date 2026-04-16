# 🎓 Data Science Portfolio — GitHub Pages Template

A clean, dark-themed portfolio for M.S. Data Science students. Built with pure HTML, CSS, and JavaScript — no frameworks, no build step, works directly with GitHub Pages.

---

## 🚀 Setup (5 minutes)

### 1. Create the repository
1. Go to [github.com](https://github.com) → New repository
2. Name it `yourusername.github.io` (replace with your actual GitHub username)
3. Set it to **Public**
4. Click **Create repository**

### 2. Upload your files
Upload all files maintaining this structure:
```
yourusername.github.io/
├── index.html        ← Home page
├── about.html        ← About page
├── resume.html       ← Resume page
├── contact.html      ← Contact page
├── style.css         ← All styles
├── main.js           ← Interactivity
└── assets/
    ├── photo.jpg     ← Your headshot
    ├── proj1.png     ← Project screenshots
    ├── proj2.png
    ├── proj3.png
    ├── proj4.png
    └── resume.pdf    ← Your resume PDF
```

### 3. Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Under "Source", select **Deploy from a branch**
3. Choose **main** branch → **/ (root)**
4. Click **Save**
5. Your site will be live at `https://yourusername.github.io` in ~2 minutes

---

## ✏️ Customization Checklist

### Global — all 4 HTML files
- [ ] Replace `Your Name` with your name (search & replace)
- [ ] Replace `YN` (the logo) with your initials
- [ ] Replace `yourusername` in GitHub links
- [ ] Replace `yourprofile` in LinkedIn links
- [ ] Replace `you@email.com` with your email
- [ ] Update © year if needed

### index.html (Home)
- [ ] Uncomment `<img>` tag and update `src="assets/photo.jpg"`
- [ ] Update the hero subtitle paragraph
- [ ] Update stats (projects, internships, publications)
- [ ] Update project cards with your real projects
- [ ] Update project tags, descriptions, and GitHub links
- [ ] Replace skill pills with your actual skills

### about.html
- [ ] Uncomment `<img>` tag for your photo
- [ ] Update quick facts (location, university, graduation, focus)
- [ ] Update the biography paragraphs
- [ ] Update the timeline (education, internships)
- [ ] Update interests

### resume.html
- [ ] Update education entries
- [ ] Update experience entries and bullet points
- [ ] Update skills table
- [ ] Add your publications and awards
- [ ] Put your PDF resume at `assets/resume.pdf`

### contact.html
- [ ] Update all contact links
- [ ] Set up Formspree: go to [formspree.io](https://formspree.io), create a free account,
  create a form, and replace `YOUR_FORM_ID` in the `<form action="...">` tag
- [ ] Update availability message

---

## 🎨 Customization Tips

### Change the accent color
In `style.css`, find `:root` and change `--accent`:
```css
--accent: #c8f060;   /* lime green — default */
--accent: #60a5fa;   /* blue */
--accent: #f97316;   /* orange */
--accent: #a78bfa;   /* purple */
```

### Add more projects
Copy a `.project-card` div in `index.html` and update content. The grid handles layout automatically.

### Add project images
Replace the `<div class="project-img-placeholder">` with:
```html
<img src="assets/proj1.png" alt="Project Name">
```

### Custom domain
1. Buy a domain (e.g., yourname.com)
2. In repo Settings → Pages → Custom domain, enter your domain
3. Add a `CNAME` file to the repo root containing just your domain

---

## 📁 File Structure

| File | Purpose |
|------|---------|
| `index.html` | Home: hero, summary, project grid |
| `about.html` | Full bio, timeline, interests |
| `resume.html` | Education, experience, skills |
| `contact.html` | Contact channels + form |
| `style.css` | All styles (CSS variables at top) |
| `main.js` | Mobile nav + scroll animations |

---

Built with ♥ for data scientists. No dependencies, no build step — just pure web.
