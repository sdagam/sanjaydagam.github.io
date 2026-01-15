# Sanjay Dagam - Personal Website

A professional personal website for a high school student showcasing research, applied mathematics, mental health advocacy, and iOS development.

## 🚀 Quick Deploy to GitHub Pages

### Step 1: Create GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click the **+** icon → **New repository**
3. Name it `sanjaydagam.github.io` (for a user site) or any name for a project site
4. Make it **Public**
5. Click **Create repository**

### Step 2: Upload Files
1. Clone the repository locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/sanjaydagam.github.io.git
   cd sanjaydagam.github.io
   ```

2. Copy all website files into the repository folder:
   - `index.html`
   - `research.html`
   - `blog.html`
   - `mental-health.html`
   - `apps.html`
   - `activities.html`
   - `styles.css`
   - `script.js`

3. Commit and push:
   ```bash
   git add .
   git commit -m "Initial website upload"
   git push origin main
   ```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (in the left sidebar)
3. Under "Source", select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**

Your site will be live at `https://YOUR_USERNAME.github.io/sanjaydagam.github.io/` within a few minutes!

## 📁 File Structure

```
├── index.html          # Landing page with hero section
├── research.html       # Research projects page
├── blog.html          # Applied Math Blog
├── mental-health.html # Mental Health Initiative
├── apps.html          # iOS Apps showcase
├── activities.html    # Other activities & interests
├── styles.css         # Main stylesheet
├── script.js          # Navigation & animations
└── README.md          # This file
```

## 🎨 Customization

### Adding Your Photo
Replace the placeholder in `index.html`:
```html
<div class="placeholder-image">
    <img src="your-photo.jpg" alt="Sanjay Dagam">
</div>
```

### Updating Contact Info
Search and replace these placeholders across all HTML files:
- `sanjay@example.com` → your actual email
- `https://github.com/sanjaydagam` → your GitHub profile
- `https://linkedin.com/in/sanjaydagam` → your LinkedIn profile

### Adding Blog Posts
In `blog.html`, copy an existing blog card and modify:
```html
<a href="posts/your-new-post.html" class="blog-card">
    <p class="blog-meta">Topic · Month Year</p>
    <h3>Your Post Title</h3>
    <p class="blog-excerpt">Brief description...</p>
</a>
```

### Color Scheme
Edit CSS variables in `styles.css` to customize colors:
```css
:root {
    --color-accent: #2d5a4a;      /* Main accent color */
    --color-accent-light: #3d7a64; /* Hover states */
    --color-bg: #faf9f7;          /* Background */
}
```

## 📱 Features

- **Responsive Design**: Works on desktop, tablet, and mobile
- **Smooth Animations**: Subtle scroll-triggered animations
- **Mobile Navigation**: Hamburger menu for small screens
- **Accessible**: Semantic HTML and keyboard navigation
- **Fast Loading**: No external dependencies except Google Fonts

## 🔧 Development

To modify locally:
1. Open any HTML file in a browser
2. Edit files with any text editor
3. Refresh browser to see changes

For a local development server (optional):
```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve
```

## 📝 License

Feel free to use this template for your own personal website.
