# Arignar Anna Zoological Park — Interactive Zoo Blog

**🌐 Live Website: [https://zennial10-spec.github.io/aazp-zoo-blog/](https://zennial10-spec.github.io/aazp-zoo-blog/)**

A polished, single-file interactive blog for **Arignar Anna Zoological Park (AAZP)**, Vandalur, Chennai — built as an educational digital assignment. This project showcases the rich biodiversity of South Asia's largest zoological park through an immersive, responsive web experience.

## 📖 About This Project

This interactive blog was created as an English Digital Assignment to document and present the wildlife of Arignar Anna Zoological Park (also known as Vandalur Zoo). Established in 1855 as the Madras Zoo — India's first public zoo — and relocated to its current 602-hectare campus in the Vandalur Reserve Forest in 1985, AAZP is home to over 2,500 animals across 170+ species.

The project combines **personal photography** from a September 2026 visit with **scientifically accurate descriptions** sourced from the IUCN Red List, Central Zoo Authority publications, and official zoo signage. Every animal card features auto-rotating image slideshows (for species with multiple photos), detailed modal profiles, and conservation status information.

## 📁 Project Structure
```
zoo_project/
├── index.html                    # Main deliverable (open in browser)
├── map_extracted-000.png         # Official zoo map
├── AAPZ_Web.webm                 # Hero background video (~14 MB)
├── otter.jpg                     # Small-clawed Otter photograph
├── *.jpg                         # 197+ animal photographs
├── classification_manifest.json  # Taxonomic data for 58 species
├── SOURCES_AND_ATTRIBUTION.md    # IUCN, CZA, zoo signage citations
├── animal_groups.json            # Animal grouping data
├── media_inventory.json          # Complete media inventory
├── referenced_images.txt         # List of all referenced images
├── LICENSE                       # MIT License + attributions
├── .gitignore                    # Git ignore rules
├── .gitattributes                # Git LFS attributes
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
All images and video are included in the repository for offline use.

### Referenced Files
- **Video**: `AAPZ_Web.webm` (hero background, ~14 MB)
- **Map**: `map_extracted-000.png` (extracted from official PDF)
- **Images**: 197+ renamed animal photos (`*.jpg`)

## 🚀 Deployment

### For Microsoft Teams / Local Viewing
```bash
cd zoo_project
zip -r aazp_zoo_blog.zip .
# Upload ZIP to Teams; recipient extracts and opens index.html
```

### GitHub Pages (Already Deployed)
The site is live at: **https://zennial10-spec.github.io/aazp-zoo-blog/**

To deploy your own fork:
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
- [ ] Open `index.html` in browser (or visit the live site)
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
- **Photography**: Author's personal visit (Sept 2026)
- **Map**: Official AAZP 2023 map (PDF extracted to PNG)
- **Design Inspiration**: Lewa House (lewahouse.com)

## ⚖️ License
Educational project. All photographs © author. Animal descriptions compiled from:
- IUCN Red List (CC BY 4.0)
- Central Zoo Authority (CZA) publications
- Arignar Anna Zoological Park official signage & website

See [LICENSE](LICENSE) for full details.

## 🛠 Technical Stack
- HTML5, CSS3 (Custom Properties, Grid, Flexbox, IntersectionObserver)
- Vanilla JavaScript (ES6+) — no frameworks, no build step
- Google Fonts: Playfair Display, Inter (fetched on first load)
- Zero external JS dependencies

---

**Repository:** https://github.com/zennial10-spec/aazp-zoo-blog  
**Live Demo:** https://zennial10-spec.github.io/aazp-zoo-blog/