# Disney's Musical Representation: An Interactive Timeline

A visual essay exploring how Disney's musical representation of non-Western cultures evolved from 1953-2021, from overt racist caricature through Orientalist stereotyping to consultative appropriation.

## 🎯 Project Overview

This interactive visual essay transforms an academic research paper into an engaging multimedia experience, combining:
- **TimelineJS** for chronological navigation through seven decades
- **Detailed analysis pages** for each film with musical examples
- **Embedded YouTube clips** demonstrating the actual sounds being analyzed
- **Theoretical framework** explaining power dynamics and cultural hegemony
- **Clear thesis argument** about continuity in power despite methodological changes

## 📚 The Central Argument

> Although Disney has replaced the stereotyped music of its earlier films with collaborative compositions of its modern releases, **this methodological shift masks a continuity in power**. Current inclusion strategies only serve to insulate the corporation from critique, allowing it to commodify cultural difference while maintaining strict Western control over the final product.

## 📁 Project Structure

```
musc102/
├── index.html                    # Main page with thesis, timeline, phase overview
├── css/
│   └── style.css                # Custom styling with academic aesthetic
├── js/
│   └── timeline-data.js         # Timeline configuration with all films
├── pages/
│   ├── theory.html              # Theoretical framework (Orientalism, Hegemony, etc.)
│   ├── methodology.html          # Research approach and analytical methods
│   ├── peter-pan.html           # Pre-Phase I (1953)
│   ├── aladdin.html             # Phase I (1992)
│   ├── pocahontas.html          # Phase I (1995)
│   ├── mulan.html               # Phase I (1998)
│   ├── lilo-stitch.html         # Transition (2002)
│   ├── frozen.html              # Transition (2013)
│   ├── moana.html               # Phase II (2016)
│   ├── frozen2.html             # Phase II (2019)
│   └── encanto.html             # Phase II (2021)
└── README_TIMELINE.md           # This file
```

## 🎬 Films Analyzed

### Pre-Phase I: Foundational Colonial Mechanism
- **Peter Pan (1953)** - Overt racist caricature with "What Made the Red Man Red?"

### Phase I: The Renaissance Era (Orientalism & Sanitization)
- **Aladdin (1992)** - "Aural shorthand" and musical Orientalism
- **Pocahontas (1995)** - Sanitizing colonial violence through pop ballads
- **Mulan (1998)** - Ideological binaries: East = oppressive, West = liberating

### Transition Period
- **Lilo & Stitch (2002)** - Hawaiian culture as backdrop, Elvis as emotional core
- **Frozen (2013)** - Generic "frozen north" criticism that changed Disney's approach

### Phase II: The Modern Era (Consultative Appropriation)
- **Moana (2016)** - "Revise for English ears" - collaboration without authority
- **Frozen II (2019)** - Kulning instead of joik; "Hey Na Na music" dismissal
- **Encanto (2021)** - Most successful collaboration, but cultural amalgamation persists

## 🚀 Deployment to GitHub Pages

### Quick Deploy (5 minutes):

```bash
# 1. Navigate to your project
cd /Users/catherinehe/musc102

# 2. Add all new files
git add index.html css/ js/ pages/ README_TIMELINE.md

# 3. Commit with descriptive message
git commit -m "Add interactive timeline visual essay with 9 film analyses"

# 4. Push to GitHub
git push origin main
```

### Enable GitHub Pages:
1. Go to your repository on GitHub
2. Click **Settings** (top right navigation)
3. Scroll to **Pages** (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

### Access Your Site:
After 3-5 minutes, your site will be live at:
```
https://[your-username].github.io/musc102/
```

For example: `https://catherinehe.github.io/musc102/`

## 🎨 Site Structure & Navigation

### Homepage Features

1. **Thesis Statement Section**
   - Clear articulation of central argument
   - Key question about decolonization vs. adaptation

2. **Quick Navigation Cards**
   - Theory page link
   - Methodology page link
   - Jump to timeline

3. **Interactive Timeline**
   - 10 major events from 1953-2021
   - YouTube clips embedded directly
   - Click for film-specific deep dives

4. **Phase Overview**
   - Pre-Phase I: Overt Caricature
   - Phase I: Orientalism & Sanitization
   - Phase II: Consultative Appropriation
   - Visual comparison of characteristics

5. **Conclusion Preview**
   - Summary of argument
   - Call for genuine redistribution of authority

### Navigation Flow

```
Homepage (index.html)
├── Theory → Orientalism, Hegemony, Commodity Racism, Culture Industry
├── Methodology → Research design, phase categorization, analytical methods
└── Timeline → Click any event
    ├── Peter Pan → Foundational colonial mechanism
    ├── Aladdin → Orientalist "aural shorthand"
    ├── Pocahontas → Historical sanitization
    ├── Mulan → Musical ideological binaries
    ├── Lilo & Stitch → Superficial Hawaiianness
    ├── Frozen → The critique that changed everything
    ├── Moana → "Revise for English ears"
    ├── Frozen II → Kulning vs. joik
    └── Encanto → Success with amalgamation
```

## 🎵 Musical Examples

Each film page includes:
- **Multiple YouTube embeds** of key songs
- **Comparative examples** (e.g., authentic bambuco vs. simplified version)
- **Visual analysis** of what musical choices reveal
- **Quotes from composers** showing decision-making process

### Example: Encanto Page Shows
- "Dos Oruguitas" (all-Spanish success)
- "We Don't Talk About Bruno" + authentic Cuban guajira for comparison
- "The Dysfunctional Tango" + authentic Argentine tango
- "Waiting on a Miracle" + authentic Colombian bambuco
- Analysis of what simplification reveals about power

## 📖 Theoretical Framework

The site provides deep engagement with:

### 1. **Music as Music Culture** (Slobin)
- Supercultures vs. subcultures
- How Disney teaches audiences to hear non-Western music through Western paradigms

### 2. **Orientalism** (Said)
- Construction of the "Other" as exotic and inferior
- Musical stereotypes serving Western fantasies

### 3. **Cultural Hegemony** (Gramsci)
- Power through consent, not force
- How hegemony adapts to absorb critique

### 4. **Commodity Racism** (hooks)
- Ethnicity as "spice" for mainstream culture
- Difference enhances flavor but never replaces foundation

### 5. **The Culture Industry** (Adorno & Horkheimer)
- Profit maximization subordinates artistic integrity
- Western conventions positioned as "universal"

## 🔍 Key Features

### For Academic Use
- **Scholarly rigor:** Properly cited sources, theoretical grounding
- **Evidence-based:** Musical analysis, interview quotes, pattern identification
- **Critical analysis:** Not just description, but examination of power dynamics
- **Multimedia:** Allows audiences to hear what's being analyzed

### For General Audiences
- **Accessible language:** Clear explanations without jargon overload
- **Visual appeal:** Modern, clean design with engaging layout
- **Interactive:** Timeline exploration, clickable deep dives
- **Multimedia:** YouTube embeds make abstract concepts concrete

### For Educators
Can be used for:
- Media Studies courses
- Ethnomusicology seminars
- Anthropology of globalization
- Critical race theory applications
- Corporate cultural hegemony case studies

## 🛠️ Customization Guide

### Adding More Films

1. **Update timeline data** (`js/timeline-data.js`):
```javascript
{
    "start_date": {"year": "YYYY", "month": "MM"},
    "text": {
        "headline": "Film Title: Brief Description",
        "text": `<p>Analysis summary</p>
                <p><a href="pages/filename.html">→ Read Full Analysis</a></p>`
    },
    "media": {
        "url": "https://www.youtube.com/watch?v=VIDEO_ID",
        "caption": "Song title - what to notice",
        "credit": "Disney"
    },
    "group": "Phase X"
}
```

2. **Create new film page** in `pages/` folder using existing templates

3. **Add to phase overview** on homepage if needed

### Changing Colors

Edit `css/style.css`:
```css
:root {
    --primary-color: #1a1a2e;      /* Dark blue header */
    --secondary-color: #16213e;    /* Darker blue gradient */
    --accent-color: #e94560;       /* Red highlights */
    --text-color: #333;            /* Body text */
    --light-bg: #f8f9fa;          /* Light section backgrounds */
}
```

### Modifying Timeline Settings

In `index.html`:
```javascript
window.timeline = new TL.Timeline('timeline-embed', timelineData, {
    scale_factor: 2,           // Zoom level (1-3)
    initial_zoom: 2,           // Starting zoom (1-10)
    timenav_height: 200,       // Bottom navigation height (pixels)
    marker_height_min: 30      // Minimum marker size
});
```

## 📊 Content Guidelines

### Film Analysis Pages Should Include

1. **Overview** - Context and significance
2. **Musical analysis** - Specific songs with YouTube embeds
3. **Power dynamics** - Who controls creative decisions?
4. **Theoretical application** - Connect to framework
5. **Key quotes** - From composers, consultants, scholars
6. **Comparison** - To other phases or films
7. **Cultural impact** - What audiences learn
8. **Further reading** - Scholarly sources

### Writing Style

- **Academic but accessible:** Rigor without unnecessary jargon
- **Evidence-based:** Every claim supported by musical evidence, quotes, or scholarship
- **Critical but fair:** Analyze power dynamics without assuming bad faith
- **Engaging:** Use specific examples, vivid quotes, concrete details

## 🎓 Academic Context

### Research Question
Has Disney's evolution in representing non-Western cultures constituted genuine decolonization or merely sophisticated adaptation of cultural hegemony?

### Methodology
- Multi-method approach combining ethnomusicological analysis, critical discourse analysis, and comparative historical study
- Phase-based categorization (Pre-Phase I → Phase I → Phase II)
- Analysis of musical structures, instrumentation, narrative function, and production materials

### Key Findings
1. Methods evolved (exclusion → consultation)
2. Power dynamics persist (Western control maintained)
3. Pattern across phases: non-Western = atmosphere, Western = emotional core
4. Consultants provide legitimacy, executives make decisions
5. Economic imperatives ("English ears") override authenticity

### Conclusion
True decolonization requires redistribution of creative authority, not just better consultation. Until Indigenous and non-Western creators hold the power to define their own sonic narratives, Disney's music remains a sophisticated instrument of Western hegemony disguised as respect.

## 🐛 Troubleshooting

### Timeline Not Loading
- Check browser console (F12) for errors
- Verify `timeline-data.js` has valid JavaScript syntax (commas, quotes)
- Ensure TimelineJS CDN links are accessible
- Clear browser cache

### Videos Not Embedding
- Verify YouTube video IDs are correct
- Check that videos allow embedding (some are restricted)
- Try in different browser (Firefox, Chrome, Safari)
- Check your network doesn't block YouTube

### GitHub Pages Not Updating
- Wait 5-10 minutes after pushing
- Check **Settings → Pages** shows green checkmark
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Check for build errors in **Actions** tab

### Mobile Display Issues
- All designs are responsive, but test on actual devices
- Horizontal timeline scrolling works on mobile
- Video embeds maintain aspect ratio

## 💡 Enhancement Ideas

### Additional Films to Add
- **The Lion King (1994)** - Appropriation of African music and "Circle of Life"
- **The Princess and the Frog (2009)** - Jazz, New Orleans, and Black cultural representation
- **Raya and the Last Dragon (2021)** - Pan-Southeast Asian amalgamation
- **Coco (2017)** - Mexican Day of the Dead and musical authenticity

### Advanced Features
- **Search functionality:** Filter timeline by keyword, theme, or phase
- **Audio clips:** Isolated musical themes for comparison
- **Side-by-side player:** Compare authentic vs. Disney versions simultaneously
- **Interactive musical notation:** Show what pentatonic scales, augmented seconds look like
- **Scholar video interviews:** Embedded expert commentary
- **Community voices:** Perspectives from represented cultures (if permissions obtained)
- **Citation generator:** Export bibliography in multiple formats
- **Multi-language support:** Spanish, Hawaiian, Sámi, etc.

### Educational Tools
- **Discussion questions** for each film
- **Worksheet templates** for students
- **Glossary** of musical and theoretical terms
- **Further viewing** recommendations
- **Primary source links** to interviews and production materials

## 📚 Complete Bibliography

Available in individual film pages and the theory page. Key sources include:

- Armstrong, Rebecca. "Time to Face the Music." *Social Sciences* 7.7 (2018)
- Mihailova, Mihaela. "Negotiable Diversity." *Oxford Handbook of the Disney Musical* (2025)
- Anjirbag, Michelle Anya. "Mulan and Moana." *Social Sciences* 7.11 (2018)
- hooks, bell. "Eating the Other." *Black Looks* (1992)
- Said, Edward. *Orientalism* (1978)
- Jiménez, Manuela. "Encanto's 'Colombian' Soundtrack" (2024)

[See complete citations in film pages and theory page]

## 📧 Credits & Attribution

### Original Research
[Your Name] - Research, analysis, and writing

### Interactive Design
Built with TimelineJS by Knight Lab (Northwestern University)

### Hosting
GitHub Pages

### Disney Content
All Disney film content remains property of The Walt Disney Company and is used under Fair Use for educational commentary and criticism.

## 📄 License

This educational project is intended for academic and non-commercial use. When using or referencing this work, please provide appropriate academic citation.

## 🎯 Quick Start Checklist

- [ ] Navigate to project directory
- [ ] Run `git add .`
- [ ] Commit: `git commit -m "Add interactive timeline"`
- [ ] Push: `git push origin main`
- [ ] Enable GitHub Pages in Settings
- [ ] Wait 5-10 minutes
- [ ] Visit `https://[username].github.io/musc102/`
- [ ] Test all links and videos
- [ ] Share with colleagues/classmates!

---

## Final Notes

This interactive timeline demonstrates that scholarly research can be both rigorous and accessible. By combining academic analysis with multimedia presentation, we create opportunities for:

- **Deeper engagement:** Audiences hear what they're reading about
- **Broader reach:** Accessible format invites non-academic audiences
- **Critical media literacy:** Teaches analytical skills through specific examples
- **Ongoing dialogue:** Framework for discussing representation in new releases

The goal isn't just to critique Disney—it's to develop frameworks for understanding how cultural power operates through seemingly benign entertainment. As new films release, this timeline can grow, tracking whether Disney's approach continues to adapt without redistributing authority, or whether genuine decolonization becomes possible.

**The song may sound more inclusive, but the conductors remain unchanged.**

---

**Last Updated:** December 2025  
**Version:** 2.0 (Expanded with 9 films, theory page, methodology page)
