# Disney's Musical Representation: An Interactive Timeline

A visual essay exploring how Disney's musical representation of non-Western cultures evolved from 1992-2019, from Orientalist stereotyping to consultative appropriation.

## 🎯 Project Overview

This interactive timeline combines:
- **TimelineJS** for chronological navigation
- **Detailed analysis pages** for each film
- **Embedded YouTube clips** of key musical moments
- **Scholarly context** from original research paper

## 📁 Project Structure

```
musc102/
├── index.html              # Main timeline page
├── css/
│   └── style.css          # Custom styling
├── js/
│   └── timeline-data.js   # Timeline configuration
├── pages/
│   ├── aladdin.html       # Detailed analysis pages
│   ├── pocahontas.html
│   ├── frozen.html
│   ├── moana.html
│   └── frozen2.html
└── README_TIMELINE.md     # This file
```

## 🚀 Deployment to GitHub Pages

### Step 1: Prepare Your Repository

1. Make sure you're in the project directory:
```bash
cd /Users/catherinehe/musc102
```

2. Check git status:
```bash
git status
```

3. Add all new files:
```bash
git add index.html css/ js/ pages/ README_TIMELINE.md
```

4. Commit your changes:
```bash
git commit -m "Add interactive timeline visual essay"
```

5. Push to GitHub:
```bash
git push origin main
```

### Step 2: Enable GitHub Pages

1. Go to your GitHub repository in a web browser
2. Click **Settings** (top navigation)
3. Scroll to **Pages** section (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

### Step 3: Access Your Site

After a few minutes, your site will be live at:
```
https://[your-username].github.io/musc102/
```

For example: `https://catherinehe.github.io/musc102/`

## 🎨 Customization Guide

### Adding YouTube Videos

In the timeline data (`js/timeline-data.js`), add videos in the `media` section:

```javascript
"media": {
    "url": "https://www.youtube.com/watch?v=VIDEO_ID",
    "caption": "Your caption here",
    "credit": "Disney"
}
```

In detailed pages, use the video container:

```html
<div class="video-container">
    <iframe src="https://www.youtube.com/embed/VIDEO_ID" allowfullscreen></iframe>
</div>
```

### Modifying Timeline Events

Edit `js/timeline-data.js`:

```javascript
{
    "start_date": {
        "year": "2019",
        "month": "11",
        "day": "22"  // Optional
    },
    "text": {
        "headline": "Your Title",
        "text": `<p>Your content here</p>`
    },
    "media": {
        "url": "https://...",
        "caption": "...",
        "credit": "..."
    },
    "group": "Phase II"  // For color-coding
}
```

### Styling Changes

Edit `css/style.css` to modify:

```css
:root {
    --primary-color: #1a1a2e;      /* Dark blue */
    --secondary-color: #16213e;    /* Darker blue */
    --accent-color: #e94560;       /* Red accent */
    --text-color: #333;            /* Body text */
    --light-bg: #f8f9fa;          /* Light backgrounds */
}
```

### Adding New Film Pages

1. Create new HTML file in `pages/` folder
2. Copy structure from existing film page
3. Update content sections
4. Add corresponding timeline event in `timeline-data.js`

## 📝 Content Guidelines

### Timeline Events

Each event should include:
- **Date** (year required, month/day optional)
- **Headline** (concise, engaging title)
- **Text** (2-3 paragraphs with key points)
- **Link** to detailed page
- **Media** (YouTube embed)
- **Group** (for visual organization)

### Detailed Pages

Each film analysis should include:
- **Overview** section
- **Musical analysis** with examples
- **Key problems/issues** highlighted
- **Theoretical framework** application
- **Cultural impact** discussion
- **Further reading** with citations

### Writing Style

- **Academic but accessible**: Scholarly rigor with clear language
- **Critical but fair**: Evidence-based analysis
- **Engaging**: Use quotes, examples, specific details
- **Well-sourced**: Cite scholars and sources

## 🛠️ Technical Features

### TimelineJS Configuration

The timeline uses these settings (in `index.html`):

```javascript
{
    scale_factor: 2,           // Zoom level (1-3)
    initial_zoom: 2,           // Starting zoom
    timenav_height: 200,       // Bottom navigation height
    marker_height_min: 30      // Minimum marker size
}
```

### Responsive Design

The site is mobile-responsive:
- Flexbox/Grid layouts adapt to screen size
- Video embeds maintain aspect ratio
- Navigation collapses on mobile
- Text sizes adjust for readability

## 🎓 Academic Context

This timeline is based on a research paper analyzing:
- **Edward Said's Orientalism**: Construction of the "Other"
- **Antonio Gramsci's Cultural Hegemony**: Power through ideology
- **bell hooks' Commodity Racism**: Ethnicity as commercial spice

### Key Arguments

1. **Phase I (1992-1995)**: Crude stereotyping and exclusion
2. **Phase II (2013-2019)**: Consultative appropriation
3. **Continuity**: Power dynamics persist despite methodology changes

## 🔍 How to Use This Timeline

### For Viewers

1. **Start with the Timeline**: Get chronological overview
2. **Click "Deep Dive"**: Read detailed analysis for specific films
3. **Watch embedded clips**: Hear the musical examples
4. **Explore connections**: See patterns across decades

### For Educators

This resource can be used for:
- **Media Studies**: Cultural representation analysis
- **Ethnomusicology**: Musical appropriation and authenticity
- **Anthropology**: Corporate cultural hegemony
- **American Studies**: Disney's global cultural influence

### For Researchers

The timeline provides:
- **Visual synthesis** of three decades of change
- **Multimedia evidence** (musical clips)
- **Scholarly citations** for further research
- **Comparative framework** for analyzing representation

## 🐛 Troubleshooting

### Timeline Not Loading

1. Check browser console for errors (F12)
2. Verify `timeline-data.js` has valid JSON syntax
3. Ensure TimelineJS CDN links are accessible

### Videos Not Playing

1. Check YouTube embed permissions
2. Try different video IDs
3. Test in different browsers

### GitHub Pages Not Updating

1. Wait 5-10 minutes after pushing
2. Clear browser cache (Ctrl+Shift+R)
3. Check GitHub Actions for build errors

### Styling Issues

1. Verify CSS file is properly linked
2. Check for CSS syntax errors
3. Test in multiple browsers

## 📚 Further Development Ideas

### Enhancements You Could Add

1. **Search functionality**: Filter timeline by keywords
2. **More films**: Extend to Mulan, Raya, Encanto
3. **Audio clips**: Embed isolated musical themes
4. **Interactive comparisons**: Side-by-side analysis
5. **Scholar interviews**: Video interviews with researchers
6. **Community voices**: Perspectives from represented cultures

### Advanced Features

- **Comments section**: Scholarly discussion
- **Citation export**: BibTeX/Chicago style
- **Translation**: Multi-language support
- **Accessibility**: Screen reader optimization
- **Analytics**: Track most-viewed sections

## 📖 Citations

### Key Sources

- Armstrong, Rebecca. "Time to Face the Music: Musical Colonization and Appropriation in Disney's Moana." *Social Sciences* 7.7 (2018).
- Mihailova, Mihaela. "Negotiable Diversity: How the Frozen Franchise Disneyfied Sámi Music and Culture." *The Oxford Handbook of the Disney Musical* (2025).
- Anjirbag, Michelle Anya. "Mulan and Moana: Embedded Coloniality and the Search for Authenticity in Disney Animated Film." *Social Sciences* 7.11 (2018).

[See full bibliography in individual film pages]

## 📧 Contact & Attribution

This project transforms an original research paper into an interactive visual essay. When using or citing this work, please credit:

- **Original Research**: [Your Name]
- **Interactive Timeline**: Created with TimelineJS by Knight Lab
- **Hosting**: GitHub Pages

## 📄 License

This educational project is intended for academic and non-commercial use. All Disney content remains property of The Walt Disney Company and is used under Fair Use for educational commentary and criticism.

---

## Quick Start Summary

```bash
# 1. Navigate to project
cd /Users/catherinehe/musc102

# 2. Add and commit files
git add .
git commit -m "Add interactive timeline"

# 3. Push to GitHub
git push origin main

# 4. Enable GitHub Pages in repository settings
# Settings → Pages → Source: main branch

# 5. Visit your site
# https://[username].github.io/musc102/
```

**Happy exploring! 🎬🎵**

