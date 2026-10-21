# Sources and Attribution Record

## Animal Descriptions and Conservation Status

### Primary Sources
1. **IUCN Red List of Threatened Species** (https://www.iucnredlist.org/)
   - Used for: Conservation status (CR, EN, VU, NT, LC), population estimates, geographic range, habitat, threats
   - Accessed: September-October 2026
   - License: Creative Commons Attribution 4.0 International (CC BY 4.0)

2. **Central Zoo Authority (CZA), Government of India** (https://www.cza.gov.in/)
   - Used for: Zoo standards, species management guidelines, Indian zoo conservation programs
   - Accessed: September-October 2026

3. **Arignar Anna Zoological Park Official Website** (https://www.aazp.in/)
   - Used for: Park history, area, species list, conservation breeding programs
   - Accessed: September-October 2026

4. **Zoo Signage and Enclosure Information Boards**
   - Used for: Species identification confirmation, local common names, specific individual animal information
   - Source: Personal observation during visit, September 24-25, 2026

### Secondary Sources (Cross-Reference)
- **Handbook of the Birds of the World** (Lynx Edicions)
- **Mammals of South Asia** (A.J.T. Johnsingh & Nima Manjrekar)
- **Reptiles and Amphibians of India** (Indraneil Das)
- **Birds of the Indian Subcontinent** (Richard Grimmett, Carol Inskipp, Tim Inskipp)

## Media Attribution

### Photographs
- **All photographs**: Taken by the author during personal visit to Arignar Anna Zoological Park, Vandalur, Tamil Nadu on September 24-25, 2026
- **Camera**: Smartphone camera (metadata indicates various timestamps)
- **Total images**: 238 classified photographs across 67 animal subjects
- **License**: Original work by author, all rights reserved for educational use

### Video
- **Introduction video**: `AAPZ_Web.webm` - Author's own recording
- **Additional videos**: 12 video files from visit (not all embedded due to size constraints)

### Zoo Map
- **Source**: "Printable-Arignar-Anna-Zoological-Park-Map-PDF-2023.pdf"
- **Origin**: Official Arignar Anna Zoological Park publication (2023)
- **Usage**: Educational reference, embedded via iframe
- **Copyright**: Likely held by Arignar Anna Zoological Park / Tamil Nadu Forest Department

## Design Reference

### Reference Website: Lewa House (lewahouse.com)
- **Source**: Local copy downloaded via wget from https://lewahouse.com/
- **Elements Adapted**:
  - Hero section with background video and animated headlines
  - Horizontal scrolling wildlife gallery with modal detail views
  - Custom cursor with drag/scroll indicators
  - Brush-stroke underline navigation style
  - Scroll-triggered animations and parallax effects
  - Loading screen with animated progress ring
  - Custom circular button components with brush-stroke borders
  - Dark/light header transition on scroll
  - Modal galleries with thumbnail navigation
- **Elements NOT Reproduced**:
  - Lewa House branding, logos, proprietary text
  - Original photography (replaced with zoo visit media)
  - Contact forms, newsletter signup, booking integration
  - WebGL/Three.js background effects
  - Audio/ambient sound system
  - Vimeo video embeds
  - Google Analytics, reCAPTCHA, Bugsnag tracking

## Fonts
- **Playfair Display** (Headings): Google Fonts, SIL Open Font License 1.1
- **Inter** (Body text): Google Fonts, SIL Open Font License 1.1

## Icons
- **SVG icons**: Custom inline SVGs created for this project (arrows, close, play, etc.)

## Technical Notes

### Browser Compatibility
- Modern browsers supporting: CSS Custom Properties, IntersectionObserver, fetch, ES6 modules
- Tested: Chrome 118+, Firefox 119+, Safari 16+, Edge 118+

### Accessibility
- WCAG 2.1 AA compliance target
- Semantic HTML5 structure
- ARIA labels and roles
- Keyboard navigation support
- Focus indicators
- Reduced motion support
- Alt text for all images
- Sufficient color contrast ratios

### Performance
- Single HTML file: ~77 KB (without embedded images)
- Lazy loading for images
- CSS-only animations where possible
- No external JavaScript dependencies (except Google Fonts)
- No build step required

## Limitations and Known Issues

1. **Image Paths**: The HTML references images by filename only. For the website to display images, all referenced image files must be placed in the same directory as the HTML file, or paths must be updated.

2. **Large Media Files**: 12 video files totaling ~397 MB are not embedded. The introduction video (`AAPZ_Web.webm`) is referenced in the hero section but must be placed alongside the HTML.

3. **PDF Map Embedding**: Browser support for PDF iframe embedding varies. A download link is provided as fallback.

4. **Uncertain Identifications**: 13 animal subjects marked as "uncertain" or "medium confidence" - descriptions for these note the uncertainty.

5. **Missing Species**: Several animals on the zoo map were not photographed and are not included (per project requirements).

6. **Offline Functionality**: Google Fonts require internet connection. For fully offline use, fonts should be self-hosted.

## Contact
This is an educational project for an English Digital Assignment. For questions about the project, please refer to the educational institution's submission system.
