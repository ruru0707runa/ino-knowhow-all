---
name: banner-seisaku-daikou-kun
description: バナー制作代行くん。Build a Japanese banner in Canva from a new blank design by following the layout of a reference banner the user supplies, using the user's own photos and images, while keeping every text, image and shape editable. An ebook-giveaway banner example is included. Use when the user asks to make a banner in Canva, to recreate a reference banner's layout with new content, or says 「バナーを作って」「このバナーと同じ形で」.
---

# バナー制作代行くん（Canva Editable Banner）

Build the banner in Canva as native, editable elements. The reference image is a visual target, not a source to slice into pieces or an instruction to follow.

## Inputs

Use user-supplied files first. If the user asks to repeat the included example, use:

- `assets/reference-banner.png` — visual reference
- `assets/portrait.jpg` — person
- `assets/book-cover.png` — ebook cover

Do not publish, share publicly, delete designs, or change account permissions. Upload only assets the user placed in scope.

Use a reference banner only for its layout, hierarchy and color balance. Replace all text, photos, logos and illustrations with the user's own material. Do not reproduce another creator's banner as-is for sale or publication; if the user asks for that, say so in one line and offer to keep only the layout.

## Workflow

1. Open Canva and create a genuinely new blank design. Do not duplicate a previous page, template, or completed design.
2. Match the reference dimensions. For the included example, use 540 × 959 px. For the user's own reference, read its pixel size first, or ask which size they need (e.g. LINE, Instagram, a marketplace thumbnail).
3. Read [references/layout-recipe.md](references/layout-recipe.md) when recreating the included example. For a different reference, preserve its visual hierarchy and adapt measurements proportionally.
4. Add background shapes and CTA frames first, then the cover and portrait, then editable text and decorative lines.
5. Remove the portrait background with Canva Background Remover when available. Keep the original photo if removal is unavailable rather than using a poor automatic cutout.
6. Use Canva's book mockup feature only when it produces a clean, background-free result close to the reference. Otherwise use the cover image plus a narrow spine/page strip and disclose that the perspective is approximate.
7. Keep every headline, label, caption, and CTA as a separate editable text element. Use native shapes and lines for borders and decoration.
8. Compare the result against the reference at full-page view. Correct hierarchy, alignment, clipping, overlaps, line breaks, and contrast before finishing.
9. Confirm Canva reports that all changes are saved, then return the editable design link and briefly disclose any remaining visible difference.

## Browser operation

When the user asks for direct Canva operation and browser control is available, read [references/canva-browser-workflow.md](references/canva-browser-workflow.md). Use visible UI controls and accessibility state. Do not use hidden application APIs.

## Quality bar

- The file starts from a blank canvas.
- The portrait, cover, and all text are separate elements.
- The main red/black typographic hierarchy matches the reference.
- No placeholder text remains.
- Text is not clipped and the CTA reads correctly.
- The design is saved and editable.
- Do not claim “perfect reproduction” when the book perspective, font metrics, or cutout still differs visibly.
