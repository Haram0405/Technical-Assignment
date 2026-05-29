# Technical-Assignment

# Timeless Watches — Product Page

A single-file e-commerce product page built with HTML, CSS, and vanilla JS.

---

## Prompts Used

**Prompt 1:**
> "Create same design and structure of this ecommerce website page"
> *(accompanied by a screenshot of the original design)*

**Prompt 2:**
> "Add a README.md explaining: what prompts you used, how AI helped, what you changed."

---

## How AI Helped

- **Interpreted the screenshot** — extracted layout structure, color palette, typography hierarchy, spacing, and component breakdown directly from the image without needing a written spec.
- **Wrote all the code** — full HTML, CSS, and JavaScript in one pass: sticky navbar, two-column product grid, thumbnail gallery, quantity selector, price block, rating row, CTA buttons, newsletter offer box, and features strip.
- **Made design decisions** — chose `Cormorant Garamond` for the product title (a refined serif that suits luxury goods) and `Jost` for UI text, rather than defaulting to generic system fonts.
- **Added interactivity** — the quantity +/− buttons and thumbnail active-state switching were written and wired up automatically.
- **Structured for portability** — everything lives in a single `.html` file with no external dependencies beyond Google Fonts, so it works by just opening the file.

---

## What Was Changed or Added vs. the Original Screenshot

| Area | Original | This Version |
|---|---|---|
| Watch image | Real product photo | Emoji placeholder (swap in your own `<img>`) |
| Thumbnails | Actual photos | Emoji placeholders |
| Wishlist button | Not present | Added below "Add to Bag" |
| Breadcrumb | Not visible | Added below navbar |
| Features strip | Not visible | Added (Shipping · Returns · Security · Warranty) |
| Typography | Generic sans-serif | Cormorant Garamond (titles) + Jost (UI) |
| Hover states | Unknown | Smooth transitions on all interactive elements |
| Responsive layout | Unknown | Collapses to single column on mobile |

---

## How to Customise

1. **Add your watch image** — replace the `<div class="gallery-main-placeholder">` with:
   ```html
   <img src="your-watch.jpg" alt="Elegant Luxury Watch">
   ```
2. **Update thumbnail images** — replace each `.thumb` div's emoji content with `<img>` tags.
3. **Change copy/pricing** — edit the product title, description, and price values directly in the HTML.
4. **Adjust colors** — all brand colors are CSS variables at the top of the `<style>` block (`--navy`, `--gold`, `--cream`, etc.).
