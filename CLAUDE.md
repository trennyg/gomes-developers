# Task: Hero Section Copy & Layout Edit

## Goal
Edit the hero section of `index.html` to reorganise the text elements as described below.

---

## Current Hero Structure (top to bottom)
1. `MUMBAI · CONSTRUCTION & REDEVELOPMENT`  ← spaced-caps line, gold/copper colour, centred
2. GD monogram logo (SVG or image)
3. *Gomes Developer's* (script/italic font)
4. `CONSTRUCTION · REDEVELOPMENT`  ← spaced-caps line, same gold/copper colour
5. Hero body copy + CTAs

---

## Required Changes

### 1. Top line — remove "CONSTRUCTION & REDEVELOPMENT", keep only "MUMBAI ·"
- Find the element containing `MUMBAI · CONSTRUCTION & REDEVELOPMENT`
- Change its text content to just `MUMBAI ·`
- Keep the same element, same font, same letter-spacing, same colour, same `text-align: center` (ensure it is centred if not already)

### 2. Below the GD logo / "Gomes Developer's" script — replace existing subtitle line
- Find the element currently containing `CONSTRUCTION · REDEVELOPMENT` (the one that sits directly below the logo/script in the hero)
- Change its text to `CONSTRUCTION & REDEVELOPMENT`
- It must use **exactly the same styling** (font-family, font-size, letter-spacing, text-transform, colour) as the original top line (`MUMBAI · CONSTRUCTION & REDEVELOPMENT`) had — i.e. spaced uppercase caps in the gold/copper tone (approx `#C9A96E` or whatever CSS variable/value is used for that colour)
- Do NOT add any new CSS classes; reuse the existing class/style already used by the top line element, or copy its inline styles

### 3. Remove the duplicate
- After step 2, there should now be only ONE `CONSTRUCTION & REDEVELOPMENT` line in the hero (the new one below the logo). Confirm the old top-line text has already been replaced in step 1.

---

## Verification checklist before finishing
- [ ] Top of hero shows only `MUMBAI ·` (centred, same styling as before)
- [ ] Below the GD logo / "Gomes Developer's" script: `CONSTRUCTION & REDEVELOPMENT` in gold spaced-caps
- [ ] No stray `CONSTRUCTION · REDEVELOPMENT` or `CONSTRUCTION & REDEVELOPMENT` text remaining elsewhere in the hero
- [ ] No visual regressions on the rest of the page
- [ ] HTML is valid; no broken tags

---

## Notes
- Only edit `index.html` (and/or the associated CSS file if styles need tweaking — but prefer reusing existing classes)
- Do not change any other sections (About, Services, Projects, Contact, Footer)
- Do not alter the GD monogram logo, the "Gomes Developer's" script text, or the hero body copy / CTA buttons
