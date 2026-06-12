# Pon Vignesh — Portfolio

A terminal-inspired, fully animated portfolio website built with HTML, CSS, and JavaScript.

## 📁 Project Structure

```
vignesh-portfolio/
├── index.html          # Main portfolio (Hero, Projects, About, Academics, Skills, Connect)
├── projects.html       # All projects detail page
├── skills.html         # Full stack skills detail page
├── css/                # (Move styles here later if needed)
├── images/             # Add your project screenshots here
│   ├── project-1.png   # Predictive Maintenance screenshot
│   ├── project-2.png   # Python Mini Projects screenshot
│   ├── project-3.png   # AWS Data Pipeline screenshot
│   └── project-4.png   # Bank Account System screenshot
└── resume.pdf          # Add your resume here
```

## 🚀 Quick Start

1. **Download** the ZIP and extract it
2. **Open in VS Code**: File → Open Folder → select `vignesh-portfolio/`
3. **Install Live Server** extension in VS Code
4. **Right-click `index.html`** → "Open with Live Server"

## 🎨 Features

| Feature | Description |
|---------|-------------|
| **Scatter Text** | Name letters repel away from cursor |
| **Tile Platform** | Background tiles push away from cursor |
| **Typewriter Roles** | 7 roles cycle with typing/deleting effect |
| **3D Card Popups** | Project cards lift with extruded shadow |
| **Theme Toggle** | BLACK_WHITE ↔ COLOR_SOLID switch |
| **Live Clock** | Real-time IST clock |
| **GitHub API** | Auto-fetches public repo count |
| **Scroll Reveal** | Cards animate in as you scroll |
| **Bottom Nav** | Fixed navigation bar (appears in color mode) |

## 📝 What to Customize in VS Code

### 1. Add Project Screenshots
In `index.html`, find these comments and replace with `<img>` tags:
```html
<!-- REPLACE WITH: <img src="images/project-1.png" alt="..."> -->
```
Drop your screenshots into the `images/` folder.

### 2. Add Your Resume
Drop `resume.pdf` in the root folder. The RESUME button in the About section already links to it.

### 3. Update GitHub Repo Count (if API fails)
In `index.html`, find:
```javascript
document.getElementById('repoCount').textContent = '12';
```
Change `'12'` to your actual public repo count.

### 4. Move CSS to External File (Optional)
Copy everything inside `<style>` tags from `index.html` to `css/style.css`, then add:
```html
<link rel="stylesheet" href="css/style.css">
```

## 🔗 Pages

| Page | URL | How to Open |
|------|-----|-------------|
| Home | `index.html` | Main page |
| All Projects | `projects.html` | Click "ALL PROJECTS" button |
| Full Stack | `skills.html` | Click "FULL STACK" button |

## 📧 Contact

- **Email**: pongineshw@gmail.com
- **GitHub**: https://github.com/Vignesh16714
- **LinkedIn**: https://www.linkedin.com/in/ponvigneshwaran-m-13222b326/

---
Built with 💻 by Pon Vignesh
