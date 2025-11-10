# Tejaaswin Raja - Resume Website

A modern, responsive resume website showcasing academic achievements, research work, leadership experience, and community service.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Easy to Update**: Simple HTML structure for adding new content
- **Image Support**: Organized folder structure for photos and research images
- **GitHub Pages Ready**: Can be deployed directly to GitHub Pages for free hosting

## File Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript for interactions
├── images/             # Image folder
│   ├── profile.jpg     # Profile picture (add your photo here)
│   └── research/       # Research project images
│       ├── mircore-research.jpg
│       ├── dental-anxiety.jpg
│       ├── orp-probe.jpg
│       ├── tribometer.jpg
│       └── computational-bio.jpg
└── README.md          # This file
```

## Setting Up Images

### Required Images

1. **Profile Picture** (`images/profile.jpg`)
   - Recommended size: 400x400px or larger (square)
   - Format: JPG or PNG
   - This will be displayed in the hero section

2. **Research Project Images** (`images/research/`)
   - Recommended size: 800x400px or larger (landscape)
   - Format: JPG or PNG
   - Add images for each research project:
     - `mircore-research.jpg` - Neuronal Vesicle Formation research
     - `dental-anxiety.jpg` - Dental Anxiety & Bruxism research
     - `orp-probe.jpg` - Oxidation Reduction Probe research
     - `tribometer.jpg` - Tribometer research
     - `computational-bio.jpg` - Computational Biology research

### Adding More Images Later

The website is structured to easily accommodate additional research projects and photos:

1. **Adding New Research Projects**: 
   - Add a new `<div class="project-card">` section in the Research section
   - Place your image in `images/research/` folder
   - Update the image path in the HTML

2. **Adding More Photos**:
   - Create new folders in `images/` as needed (e.g., `images/awards/`, `images/activities/`)
   - Reference them in the HTML where needed

## Deployment to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right, then "New repository"
3. Name it (e.g., `tejaaswin-resume` or `resume-website`)
4. Make it **Public** (required for free GitHub Pages)
5. Click "Create repository"

### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**
1. In your new repository, click "uploading an existing file"
2. Drag and drop all your files (index.html, styles.css, script.js, images folder)
3. Commit the changes

**Option B: Using Git Command Line**
```bash
# Navigate to your project folder
cd path/to/your/project

# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit - Resume website"

# Add your GitHub repository as remote
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"
7. Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

### Step 4: Custom Domain (Optional)

If you have a custom domain:
1. In GitHub Pages settings, add your custom domain
2. Update your domain's DNS settings as instructed by GitHub

## Updating Content

### To Update Personal Information:
- Edit `index.html` and search for the section you want to update
- All content is clearly marked with comments

### To Add New Research Projects:
1. Add your research image to `images/research/`
2. In `index.html`, find the Research section (`<section id="research">`)
3. Copy an existing project card and modify it with your new research details

### To Change Colors/Styling:
- Edit `styles.css`
- Main colors are defined at the top in `:root` variables

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Notes

- All images should be optimized for web (use tools like [TinyPNG](https://tinypng.com/) to reduce file size)
- The website uses Google Fonts (Inter) - no additional setup needed
- All links in the navigation will work once deployed
- The mobile menu will automatically work on smaller screens

## Future Enhancements

The website structure supports:
- Adding more research projects with images
- Adding a portfolio/gallery section
- Adding blog posts or articles
- Adding downloadable PDF resume
- Adding contact form functionality

## Support

If you need help updating content or adding features, the code is well-commented and organized for easy modification.

---

**Good luck with your college applications!** 🎓

