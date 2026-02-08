# Portfolio Site Structure

```
┌─────────────────────────────────────────────────────────────┐
│                    NAVIGATION BAR (All Pages)                │
│  Home | About | Projects | Gallery | Publications | CV | Contact │
└─────────────────────────────────────────────────────────────┘

┌───────────────────────┐
│    1. HOME PAGE       │
│   (index.html)        │
├───────────────────────┤
│ • Hero Section        │
│ • Statistics (4 stats)│
│ • Quick About         │
│ • Featured Projects   │
│ • CTA Section         │
└───────────┬───────────┘
            │
            ├──────────────┬──────────────┬──────────────┐
            │              │              │              │
┌───────────▼───────┐ ┌───▼──────────┐ ┌─▼────────────┐ │
│  2. ABOUT PAGE    │ │3. PROJECTS   │ │4. GALLERY    │ │
│  (about.html)     │ │ (projects.ht)│ │(gallery.html)│ │
├───────────────────┤ ├──────────────┤ ├──────────────┤ │
│ • Background      │ │• Featured    │ │• Project     │ │
│ • Skills (4 cats) │ │  Projects    │ │  Images      │ │
│ • Education       │ │• Details     │ │• Captions    │ │
│ • Philosophy      │ │• Additional  │ │• Categories  │ │
└───────────────────┘ └──────────────┘ └──────────────┘ │
                                                         │
            ┌────────────────┬───────────────────────────┘
            │                │
┌───────────▼───────┐ ┌─────▼────────┐ ┌──────────────┐
│5. PUBLICATIONS    │ │  6. CV PAGE  │ │7. CONTACT    │
│(publications.html)│ │  (cv.html)   │ │(contact.html)│
├───────────────────┤ ├──────────────┤ ├──────────────┤
│ • Research Works  │ │• Summary     │ │• Contact Form│
│ • Publications    │ │• Experience  │ │• Email/Phone │
│ • Awards          │ │• Education   │ │• Location    │
│ • Certifications  │ │• Projects    │ │• LinkedIn    │
└───────────────────┘ │• Printable   │ │• Opportunities│
                      └──────────────┘ └──────────────┘

┌─────────────────────────────────────────────────────────────┐
│                    FOOTER (All Pages)                        │
│      Quick Links | Contact Info | Copyright                 │
└─────────────────────────────────────────────────────────────┘
```

## File Connections

```
ALL PAGES
    ├── styles.css (shared styling)
    ├── script.js (shared functionality)
    └── Navigation links to all other pages

ASSETS STRUCTURE
portfolio/
├── index.html           ← Homepage
├── about.html          ← About page
├── projects.html       ← Projects showcase
├── gallery.html        ← Image gallery
├── publications.html   ← Research & publications
├── cv.html            ← Curriculum Vitae
├── contact.html       ← Contact form
├── styles.css         ← Shared CSS (ONE file for all)
├── script.js          ← Shared JavaScript
└── images/            ← (Create this for photos)
    ├── profile.jpg
    ├── project1.jpg
    ├── project2.jpg
    └── ...
```

## Navigation Flow

```
User lands on HOME
    ↓
Can navigate to ANY page via nav bar
    ↓
Each page has links to related pages
    ↓
Footer on every page with quick links
    ↓
Smooth scroll animations throughout
```

## Key Features Per Page

| Page          | Primary Purpose                | Key Sections                          |
|---------------|-------------------------------|---------------------------------------|
| Home          | First impression & overview   | Hero, Stats, Featured Projects        |
| About         | Professional background       | Skills, Education, Philosophy         |
| Projects      | Detailed work showcase        | 4 Major projects + Additional work    |
| Gallery       | Visual portfolio             | Image grid with captions              |
| Publications  | Academic contributions        | Research, Papers, Awards              |
| CV            | Complete resume              | Full work history (printable)         |
| Contact       | Communication                | Form, Email, Phone, Social            |

## Color Coding

- 🟦 **Blue sections** = Information display
- 🟧 **Orange elements** = Interactive/CTA
- ⚫ **Dark background** = Professional aesthetic
- ⚪ **Light text** = High readability

## Responsive Breakpoints

- **Desktop**: > 968px (Full layout)
- **Tablet**: 768px - 968px (Adjusted grid)
- **Mobile**: < 768px (Stacked, hamburger menu)

---

**Total Pages**: 7
**Total Files**: 9 (7 HTML + 1 CSS + 1 JS)
**Total Components**: 35+ reusable sections
