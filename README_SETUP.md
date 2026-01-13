# Mukhamad Suhermanto's Academic Website

This is your customized Academic Pages website based on the [Academic Pages template](https://github.com/academicpages/academicpages.github.io).

## What Has Been Customized

### 1. Navigation Menu
The navigation has been updated with your custom sections:
- **Home** - Overview and navigation guide
- **MechEng** - Mechanical Engineering research and publications
- **EnvEng** - Environmental & Ecological Engineering work
- **ML-AI** - Machine Learning and AI projects
- **CV** - Complete curriculum vitae with PDF download

### 2. Site Configuration (`_config.yml`)
- Updated with your personal information
- Set correct GitHub repository (suhermantom/suhermantom.github.io)
- Updated author profile with your details

### 3. Custom Pages Created

#### Home Page (`_pages/about.md`)
- Welcome message and biography
- Navigation guide to all sections
- Research highlights
- Skills and languages overview

#### MechEng Page (`_pages/mecheng.md`)
- Overview of mechanical engineering research
- Focus areas: automotive AC systems, refrigerant technology
- All four publications listed with full citations
- Teaching experience and skills

#### EnvEng Page (`_pages/enveng.md`)
- Environmental and ecological engineering research
- PhD program information
- Sustainability focus areas
- Professional experience at AAARCC

#### ML-AI Page (`_pages/ml-ai.md`)
- Machine learning and AI applications
- Programming skills and projects
- SVR publication highlighted
- Future directions and collaboration opportunities

#### CV Page (`_pages/cv.md`)
- Complete curriculum vitae
- PDF download button at top and bottom
- Education, experience, publications
- Awards, skills, interests, hobbies

### 4. Files Added
- `MSuhermanto_Resume.pdf` in the `files/` directory

## How to Deploy to GitHub Pages

### Option 1: Create a New Repository
1. Create a new repository on GitHub named `suhermantom.github.io`
2. Initialize it and push all files from the `github-site` directory:
   ```bash
   cd github-site
   git init
   git add .
   git commit -m "Initial commit: Academic website"
   git branch -M main
   git remote add origin https://github.com/suhermantom/suhermantom.github.io.git
   git push -u origin main
   ```

### Option 2: Update Existing Repository
If you already have a `suhermantom.github.io` repository:
1. Backup your existing repository
2. Replace the contents with files from `github-site/`
3. Commit and push:
   ```bash
   git add .
   git commit -m "Update to new Academic Pages template"
   git push
   ```

### Enable GitHub Pages
1. Go to your repository settings on GitHub
2. Navigate to "Pages" section
3. Under "Source", select the `main` branch
4. Save the settings
5. Your site will be live at: https://suhermantom.github.io

## Testing Locally

To preview your site locally before deploying:

### Prerequisites
Install Ruby and Jekyll:
- **Windows**: Use RubyInstaller from https://rubyinstaller.org/
- **Mac**: Ruby is pre-installed; install bundler: `gem install bundler`
- **Linux**: `sudo apt install ruby-dev ruby-bundler nodejs`

### Running Locally
```bash
cd github-site
bundle install
bundle exec jekyll serve
```

Then open your browser to: http://localhost:4000

## Customization Tips

### Adding a Profile Picture
1. Replace `images/profile.png` with your photo
2. Keep the filename as `profile.png` or update `avatar` in `_config.yml`

### Adding More Content
- **Blog posts**: Add `.md` files to `_posts/`
- **Publications**: Add `.md` files to `_publications/`
- **Teaching materials**: Add `.md` files to `_teaching/`
- **Portfolio items**: Add `.md` files to `_portfolio/`

### Linking Course Material Repositories
When you create GitHub repositories for your course materials:
1. Edit the respective page (`mecheng.md`, `enveng.md`, or `ml-ai.md`)
2. Add links in the "Course Materials & Resources" section:
   ```markdown
   - [Thermodynamics Course](https://github.com/suhermantom/thermodynamics-course)
   ```

### Updating Your CV
When you update your CV:
1. Replace `files/MSuhermanto_Resume.pdf` with the new version
2. Update content in `_pages/cv.md` if needed
3. Commit and push the changes

## File Structure Overview

```
github-site/
├── _config.yml           # Main site configuration
├── _data/
│   └── navigation.yml    # Navigation menu configuration
├── _pages/
│   ├── about.md         # Home page
│   ├── cv.md            # CV page
│   ├── mecheng.md       # Mechanical Engineering page
│   ├── enveng.md        # Environmental Engineering page
│   └── ml-ai.md         # ML-AI page
├── files/
│   └── MSuhermanto_Resume.pdf  # Your CV PDF
└── images/
    └── profile.png      # Profile picture (update with yours)
```

## Next Steps

1. **Add your profile picture**: Replace `images/profile.png`
2. **Deploy to GitHub**: Follow deployment instructions above
3. **Test your site**: Visit https://suhermantom.github.io after deployment
4. **Create course repositories**: Set up separate repositories for course materials
5. **Link course repos**: Add links in the respective pages
6. **Regular updates**: Keep your CV and research updated

## Support & Resources

- [Academic Pages Documentation](https://academicpages.github.io/)
- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)

## Contact

For questions or issues with this website, contact:
- **Email**: msuherma@purdue.edu
- **GitHub**: https://github.com/suhermantom

---

*Last updated: January 13, 2026*

