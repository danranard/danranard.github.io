# Academic Webpage

A clean, professional single-page academic website for a theoretical physics postdoc.

## Structure

- **index.html** - Main webpage with all content
- **style.css** - Styling and responsive design
- **figures/** - Directory for paper figures/images (create this)
- **cv.pdf** - Your CV (add this file)

## Customization Guide

### 1. Basic Information (Header)
Edit these in `index.html`:
- Your name (line 22)
- Title/position (line 23)
- Institution (line 24)
- Research tagline (line 25)

### 2. About Section
Replace placeholder text with:
- Your bio (paragraphs)
- PhD details
- Research interests list

### 3. Research & Featured Papers
For each featured paper:
- Update title, authors, venue
- Add arXiv/journal links
- Write 2-3 sentence description
- Add figure to `figures/` folder
- Update image path and caption

### 4. Publications List
Add your papers in reverse chronological order:
- Title with link
- Authors (bold your name)
- Journal/arXiv info

### 5. Contact Information
Update:
- Email address
- Office location/building
- Google Scholar ID
- arXiv author ID
- ORCID (optional)
- GitHub (optional)

### 6. Links
Update all placeholder links:
- Google Scholar: Replace `YOUR_ID` with your Google Scholar ID
- arXiv: Replace `YOUR_ARXIV_ID` with your arXiv author ID
- ORCID: Add your ORCID identifier
- Paper links: Add actual arXiv/DOI links

## Adding Figures

1. Create a `figures/` directory in the same folder as `index.html`
2. Add your paper figures (PNG, JPG, or SVG recommended)
3. Name them descriptively: `paper1.png`, `topological_phase_diagram.png`, etc.
4. Reference them in the HTML: `<img src="figures/your-figure.png" alt="Description">`

## Local Testing

Simply open `index.html` in your browser:
- **Windows**: Double-click the file or right-click → Open with → Browser
- **Mac/Linux**: `open index.html` or `xdg-open index.html`

For live development (auto-refresh on changes), you can use:
- VS Code Live Server extension
- Python: `python -m http.server 8000` (then visit `localhost:8000`)
- Node.js: `npx http-server`

## Deploying to GitHub Pages

### Step 1: Create Repository
1. Go to GitHub and create a new repository named `username.github.io` (or any name)
2. Make it public

### Step 2: Push Your Files
```bash
cd webpage
git init
git add .
git commit -m "Initial commit of academic webpage"
git branch -M main
git remote add origin https://github.com/username/username.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select `main` branch and `/ (root)` folder
4. Click **Save**
5. Your site will be live at `https://username.github.io` (or `https://username.github.io/repo-name`)

### Step 4: Update
Whenever you make changes:
```bash
git add .
git commit -m "Update content"
git push
```

Changes will be live in 1-2 minutes.

## Custom Domain (Optional)

If you want to use a custom domain (e.g., `yourname.com`):
1. Add a file named `CNAME` with your domain name
2. Configure DNS with your domain registrar to point to GitHub Pages
3. See GitHub's [custom domain documentation](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)

## Design Features

- **Clean, academic aesthetic** - Professional and information-focused
- **Responsive design** - Works on mobile, tablet, and desktop
- **Single-page layout** - Smooth scrolling navigation
- **Semantic HTML** - Good for accessibility and SEO
- **Fast loading** - Minimal dependencies, pure CSS
- **Print-friendly** - Optimized print styles included

## Browser Compatibility

Works in all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Tips

- **Keep it updated**: Update papers and info regularly
- **Compress images**: Use optimized images (< 500KB each) for faster loading
- **Test mobile**: Check how it looks on your phone
- **Proofread**: Have colleagues review your content
- **Analytics** (optional): Add Google Analytics if you want to track visits

## License

This template is free to use and modify for your personal academic webpage.

