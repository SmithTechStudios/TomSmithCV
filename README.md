# Tom Smith — HTML CV

A static HTML résumé with Tailwind CSS, dark mode, and LinkedIn-style experience cards.

## View locally

Open [`index.html`](index.html) in your browser (double-click or drag into Chrome/Edge).

Requires an internet connection on first load for the Tailwind CDN script.

## Dark mode

Use the sun/moon button (top-right). Your choice is saved in `localStorage` under `cv-theme`. On first visit, the page follows your system light/dark preference.

## Download / print to PDF

Click **Download PDF** (top-right), or press `Ctrl+P`. Choose **Save as PDF** as the destination.

Enable **Background graphics** if you want accent colours in the PDF. The page forces a light layout when printing and hides the toolbar buttons.

## Editing content

All content is in [`index.html`](index.html). Each job is an `<article class="experience-card">` block — copy an existing block to add roles, or edit text in place.

Update the **Egress** description and bullets with your real achievements when ready.

## Profile photo & logos

- Profile photo: [`assets/avatar.jpg`](assets/avatar.jpg)
- Company logos: [`assets/logos/`](assets/logos/) (`egress.png`, `nimble.png`, `3squared.png`, `seams.svg`, `tribal.png`, `bgquest.png`, `funday.png`, `squadstats.png`, `nomorebindays.png`)

Replace any image file to update the CV; keep the same filename or update the matching `<img src="...">` in `index.html`.

## Source PDF

Archived reference: [`source/cv.pdf`](source/cv.pdf)
