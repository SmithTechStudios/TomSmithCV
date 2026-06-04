# Tom Smith — HTML CV

A static HTML résumé with Tailwind CSS, dark mode, and LinkedIn-style experience cards.

## View locally

Open [`index.html`](index.html) in your browser (double-click or drag into Chrome/Edge).

Requires an internet connection on first load for the Tailwind CDN script.

## Dark mode

Use the sun/moon button (top-right). Your choice is saved in `localStorage` under `cv-theme`. On first visit, the page follows your system light/dark preference.

## Print to PDF

1. Open `index.html` in Chrome or Edge.
2. Press `Ctrl+P` (Print).
3. Destination: **Save as PDF**.
4. Enable **Background graphics** if you want accent colours in the PDF.
5. The page forces a light layout when printing.

## Editing content

All content is in [`index.html`](index.html). Each job is an `<article class="experience-card">` block — copy an existing block to add roles, or edit text in place.

Update the **Egress** description and bullets with your real achievements when ready.

## Profile photo & logos

- Profile photo: [`assets/avatar.jpg`](assets/avatar.jpg)
- Company logos: [`assets/logos/`](assets/logos/) (`egress.png`, `nimble.png`, `3squared.png`, `tribal.png` from LinkedIn; SEAMS and side projects still use SVG placeholders)

Replace any image file to update the CV; keep the same filename or update the matching `<img src="...">` in `index.html`.

## Source PDF

Archived reference: [`source/cv.pdf`](source/cv.pdf)
