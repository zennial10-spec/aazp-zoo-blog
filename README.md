# Arignar Anna Zoological Park — Interactive Zoo Blog

A polished, single-file interactive blog for **Arignar Anna Zoological Park (AAZP)**, Vandalur, Chennai — built as an educational digital assignment.

## 🌐 Live Preview
Open `index.html` in any modern browser (Chrome, Firefox, Safari, Edge).

## 📁 Project Structure
```
zoo_project/
├── index.html                    # Main deliverable
├── map_extracted-000.png         # Official zoo map
├── AAPZ_Web.webm                 # Hero background video (~14 MB)
├── *.jpg                         # 150+ animal photographs
├── classification_manifest.json  # Taxonomic data for 58 species
├── SOURCES_AND_ATTRIBUTION.md    # IUCN, CZA, zoo signage citations
├── assets/                       # (optional) organized assets
└── README.md                     # This file
```

## ✨ Features
- **Hero Section**: Full-screen background video with animated headlines & counter animation
- **About AAZP**: Comprehensive park overview — history, scale, conservation, education
- **Wildlife Gallery**: 58 animal species cards with **auto-rotating slideshows** (2–4s), hover-pause, cross-fade
- **Animal Profiles**: Click any card → modal with detailed description, conservation status, thumbnail gallery
- **Static Map**: Official zoo map with download link
- **Reflection Section**: Conservation insights & status key
- **Animated Counters**: Stats count up on scroll (170+ Species, 602 Hectares, 2,500+ Animals, 1 Day Visit)
- **Responsive Design**: Desktop, tablet, mobile with hamburger menu
- **Dark/Light Mode**: Auto via `prefers-color-scheme`
- **Accessibility**: WCAG 2.1 AA (semantic HTML, ARIA, keyboard nav, reduced motion)
- **Single File**: All HTML, CSS, JavaScript in `index.html` — no build tools, no dependencies

## 🎨 Design
Clean, editorial aesthetic with:
- **Typography**: Playfair Display (headings) + Inter (body)
- **Colors**: Earth tones, dark mode support
- **Animations**: Scroll-reveal, counter ease-out, slideshow cross-fade
- **No external dependencies** — fully offline after first load

## 📸 Media
All images and video must be in the same folder as `index.html` for offline use.

### Quick Setup
```bash
# Copy media from source (if not already present)
cp /home/haivaan/Pictures/Vandulur_zoo/*.jpg .
cp /home/haivaan/Pictures/Vandulur_zoo/*.webm .
cp /home/haivaan/zoo_project/map_extracted-000.png .
```

### Referenced Files
- **Video**: `AAPZ_Web.webm` (hero background, ~14 MB)
- **Map**: `map_extracted-000.png` (extracted from official PDF)
- **Images**: 150+ renamed animal photos (`*.jpg`)

## 🚀 Deployment
### For Microsoft Teams / Local Viewing
```bash
cd zoo_project
zip -r aazp_zoo_blog.zip .
# Upload ZIP to Teams; recipient extracts and opens index.html
```

### GitHub Pages (Optional)
```bash
git init
git add .
git commit -m "Initial commit: AAZP interactive zoo blog"
git branch -M main
git remote add origin https://github.com/<username>/aazp-zoo-blog.git
git push -u origin main
# Enable Pages: Settings → Pages → Deploy from main branch / (root)
```

## 🧪 Quick Test Checklist
- [ ] Open `index.html` in browser
- [ ] Hero video autoplays, counters animate on scroll
- [ ] Click animal card → modal opens with correct data & slideshow
- [ ] Navigate modal gallery (arrows, keys, thumbnails)
- [ ] Hover animal cards → slideshow pauses, resumes on leave
- [ ] Mobile menu works (< 768px)
- [ ] Dark/light mode follows OS preference
- [ ] Keyboard navigation (Tab, Enter, Escape, Arrows)
- [ ] No console errors (DevTools)

## 📄 Sources & Attribution
- **Animal Data**: IUCN Red List (CC BY 4.0), CZA publications, AAZP signage
- **Photography**: Author's personal visit (Sept 2024)
- **Map**: Official AAZP 2023 map (PDF extracted to PNG)
- **Design Inspiration**: Lewa House (lewahouse.com)

## ⚖️ License
Educational project. All photographs © author. Animal descriptions compiled from:
- IUCN Red List (CC BY 4.0)
- Central Zoo Authority (CZA) publications
- Arignar Anna Zoological Park official signage & website

## 🛠 Technical Stack
- HTML5, CSS3 (Custom Properties, Grid, Flexbox, IntersectionObserver)
- Vanilla JavaScript (ES6+) — no frameworks, no build step
- Google Fonts: Playfair Display, Inter (fetched on first load)
- Zero external JS dependencies