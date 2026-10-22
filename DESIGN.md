# Bunifulab Link Hub — Design Notes

## Intent
Turn a basic link-in-bio page into a personal app launchpad: visitors should understand who Mark is, what he builds, and how to open each app in seconds.

## Direction: Field Notes
- Dark graphite canvas with a restrained lime accent, softened borders, and a subtle technical grid.
- Strong editorial headline; concise project descriptions.
- Two-column app cards on desktop and a single-column stack on mobile.
- Mauzo receives the primary feature card because it is the newly supplied live app.
- Product statuses distinguish live apps from source-code links.
- Icons are inline SVGs; no emoji or icon-font dependency.
- Motion is limited to small entrance and hover transitions and respects `prefers-reduced-motion`.

## Tokens
- Background: `#1b211d` (soft graphite, lifted from near-black)
- Card: `#242c26`
- Text: `#f1f4ef`
- Secondary text: `#b2bdb3`
- Accent: `#b8f36b`
- Open-source accent: `#a3d9ff`
- Building/status accent: `#f4ca80`
- Radius: `20px`
- Max content width: `900px`

## Design process applied
1. Define the primary task: find and open an app.
2. Audit existing page content and retain the established name, role, location, and known projects.
3. Establish a visual hierarchy: identity → featured Mauzo app → other projects → contact.
4. Apply consistent type, spacing, color, and card behavior.
5. Check responsive layouts, focus visibility, contrast, link semantics, and reduced-motion behavior.

## QA before release
- [ ] Verify every app link and project description.
- [ ] Confirm the exact Raspberry Pi Media Server repository URL.
- [ ] Confirm the SlipDrop repo URL.
- [ ] Check desktop and mobile widths.
- [ ] Test keyboard navigation and focus rings.
- [ ] Confirm the Vercel deployment after pushing.


## App catalog update
- Added **Chakula Chetu** as a live app card. The description reflects the public landing page: Kenyan baby-weaning meal planning with local foods and a sensory-friendly feeding guide for autistic children.

## Texture update
- Lifted the canvas and cards to softer graphite tones for a less-black feel.
- Added a very subtle grain overlay, layered ambient color glows, and a slightly clearer technical grid.
- Kept the lime accent, project links, responsive layout, and reduced-motion support.


## App directory update
- Added UremboPro as a live salon-management demo at https://techiemak.pythonanywhere.com/.
- App directory count updated to six entries.
