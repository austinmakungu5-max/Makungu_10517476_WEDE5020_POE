 85
 86
 87
 88
 89
 90
 91
 92
 93
 94
 95
 96
 97
 98
 99
100
101
102
103
104
105
106
107
108
109
110
111
112
113
114
115
116
117
118
119
120
121
122
123
124
125
126
127
128
129
130
131
132
133
134
135
136
137
138
139
140
141
142
143
144
145
146
147
148
149
150
151
152
153
154
155
156
157
158
159
# CrenShaws Sneakers — Website Project
- Screenshot evidence of the desktop, tablet, and mobile views has been
  added to `/screenshots` and is referenced below.


Part 3 (JavaScript functionality and SEO) will follow in a future
submission/edit.

## Sitemap
```
Home (index.html)
├── About Us (about.html)
├── Services (services.html)
├── Get in Touch (enquiry.html)
└── Contact (contact.html)
```
All pages are on the same level and are reachable from the main
navigation menu on every page.

## Changelog

### Part 1
- 9 August 2026 — Initial HTML structure created for all 5 pages.
- 13 August 2026 — Basic CSS styling applied (colour palette, typography, layout).

### Part 2
- 25 August 2026 — Fixed broken homepage navigation (links previously all
  pointed to `#`).
- 25 August 2026 — Linked a single external stylesheet (`css/style.css`) from
  every page; removed the reference to a non-existent `css/style.css`
  on the old Contact page and the unlinked pages.
- 25 August 2026 — Added real `<main>` content to About, Services, Enquiry, and
  Contact pages (previously empty).
- 25 August 2026 — Renamed `enquries.html` to `enquiry.html` and corrected all
  navigation links referencing it.
- 28 August 2026 — Removed image references to files that didn't exist in the
  project (`brand1-logo.jpg`–`brand5-logo.jpg`, `product4.jpg`–`product8.jpg`).
- 1 September 2026 — Added `box-shadow` to cards, hero images, and the primary
  button for visual depth.
- 1 September 2026 — Added `:focus` and `:active` states to nav links, the
  button, and form inputs (previously only `:hover` was styled) for
  better accessibility and interactivity feedback.
- 9 September 2026 — Added `letter-spacing` to header text and the button for
  refined typography.
- 10 September 2026 — Restructured product/service listings into a `.cards` CSS
  Grid container.
- 10 September 2026 — Implemented responsive design: added `@media screen and
  (max-width: ...)` breakpoints at 768px (tablet) and 480px (mobile);
  `.container` grids collapse from 3 to 2 to 1 columns; navigation
  stacks vertically on mobile.
- 15 September 2026 — Restructured navigation to a `nav > ul > li > a` pattern on
  all 5 pages.
- 15 September 2026 — Replaced `.cards`/`.card` with a reusable `.container` /
  `.container div` pattern; applied it to the homepage featured drop,
  the new Style Inspiration gallery, the Services cards, and the About
  page team cards.
- 15 September 2026 — Added six promotional-style images to a new "Style
  Inspiration" gallery on the homepage, each with `srcset` for
  responsive loading.
- 15 September 2026 — Generated multiple image resolutions (480w/800w/1200w) and
  added `srcset`/`sizes` to the hero and featured product images for
  responsive, bandwidth-friendly image loading.
- 18 September 2026 — Added screenshot evidence of desktop/tablet/mobile views to
  the README.
- 18 September 2026 — Removed macOS system files (`__MACOSX/`, `._*`) from the
  project folder before packaging for submission.

## References
- MDN Web Docs — CSS Grid Layout: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout
- MDN Web Docs — Using media queries: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries
- MDN Web Docs — Responsive images (`srcset`/`sizes`/`picture`):
  https://developer.mozilla.org/en-US/docs/Web/HTML/Guides/Responsive_images
- MDN Web Docs — CSS pseudo-classes (`:hover`, `:focus`, `:active`):
  https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes
- Google Maps embed used on the Contact page: https://www.google.com/

Use Control + Shift + m to toggle the tab key moving focus. Alternatively, use esc then tab to move to the next interactive element on the page.
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
