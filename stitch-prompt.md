# Stitch prompt — same edit list as the local build (for side-by-side comparison)

Open the Stitch project **Sourire COD Landing Page**, select the screen
**"SOURIRE · Crème Déodorante Sweet Shop (1440px Desktop)"** (and/or the mobile
"Interactive & Motion" screen), and paste the prompt below into *Edit*.
Stitch cannot read your local PNGs, so the photo slots are described as placeholders;
swap the real files in after export.

---

Apply ALL of the following edits to this screen. Keep the existing structure, copy,
colors, tokens (Sweet Shop Nostalgia design system), order form logic and every
existing animation (ribbon marquees, spinning stamps, scent crossfade). Do not
restructure sections that are not mentioned.

1. LOGO: replace the "S" circle + text in the header and footer with a round logo:
   a hot-pink circle (#FF2BA8), 48px, containing the word "Sourire" in white in the
   display font (Bagel Fat One style), with the wordmark "Sourire / Beauty Face"
   next to it in the header.

2. HERO PHOTO BANNER: above the hero panel add a full-width photo slot
   (id="photo-hero-banner", natural ratio 2.4:1, never cropped, scales with the
   container, rounded-3xl) for the campaign banner. Overlay four animated vector
   stickers on it: a "NEW" round peel sticker (top-left, slow wobble), a lime "WoW"
   blob (top-center, pulsing), a pink four-petal flower (right, twirling) and a pink
   flower with googly eyes (left-center, bobbing, pupils drifting, blinking every few
   seconds). Add a slow 14s zoom-and-drift (Ken Burns) on the photo.

3. HERO PACKSHOT: the scent switcher shows a square white photo card
   (id="hero-packshot-img") with the selected scent's clean jar+box packshot; the
   card floats gently (4s loop). Add a per-scent sticker overlay on the card
   (flower / cucumber slice + smiley / watermelon slice + WoW / ice-cream cone +
   blue asterisk) that swaps with the scent.

4. FLAVOR CARDS: each of the four cards gets a square lifestyle photo on top
   (ids photo-card-sweet-love, photo-card-cucumber, photo-card-watermelon,
   photo-card-ice-cream, rounded-2xl, object-cover). On mobile the four cards become
   a horizontal snap scroller (78vw cards) with a "swipe" hint; on desktop keep the
   4-column grid. Each photo has 1–2 animated vector stickers matching its flavor.

5. NEW MANIFESTO BAND after the flavor cards: blush background, two columns:
   left a 16:10 photo (id="photo-manifesto") with animated stickers (googly-eye
   flower, pixel heart beating, lightning bolt flickering); right the headline
   "More than beauty. It's a feeling 🌸", a short Arabic paragraph and a row of four
   64px round scent thumbnails that switch the hero scent when clicked.

6. WHY SOURIRE: next to the benefit cards place a 4:5 portrait photo slot
   (id="photo-why") with a bobbing "Hi, Love" speech-bubble sticker; move the
   comparison card below the grid, full width (max-w 3xl).

7. LIMITED EDITION BOX: replace the box render with a square photo slot
   (id="photo-box-model") inside the magenta panel, keep the two crossing ribbon
   marquees over it, add a smaller overlapping square photo (id="photo-box-hand",
   42% width, rotated -5°, white 4px border) at the bottom-left, and animated
   stickers ("Limited Edition" ticket swaying, WoW, blue asterisk spinning,
   "Oh, Fresh" oval wiggling, NEW, green smiley).

8. REVIEWS: add a full-width 16:10 photo (id="photo-hand-jar", uncropped) above the
   three review cards with animated stickers (purple WoW, "Hi, Love" bubble,
   googly-eye flower).

9. 0% CLUB: shrink the section to a compact strip under 260px tall: ONE white
   rounded-3xl card with a hairline border and a lime "★ 100% CLEAN" pill on the
   corner; inside, three small circular stamps (max 92px; blush / cucumber-lid /
   ice-cream-lid backgrounds) with "0%" + one-word label and a thin rotating text
   ring, each followed by ONE short line of copy; three columns on desktop, stacked
   on mobile.

10. ORDER FORM:
    - Scent choice is NOT a dropdown: four ROUND radio tokens (64px, lid-colored,
      white 3px border) each showing the flavor ICON (strawberry milkshake cup,
      cucumber slice, watermelon slice, ice-cream cone), label underneath; the
      selected token scales up with a berry border, a check badge pops in and the
      icon wiggles. One group per jar for the 2-jar offer.
    - Delivery mode toggles get Material icons inside: "home" for home delivery,
      "storefront" for Stop Desk; min height 56px.
    - All text inputs and selects are larger: 56px tall on mobile, 64px on desktop,
      18px text, 24px horizontal padding, labels 13px bold.
    - Above the offer cards show a row of the four clean packshots as reassurance.

11. BEGGING ROSE CHARACTER: a small full-body cartoon character (pink rose head with
    big glossy pleading eyes, pink torso with a green leaf collar, arms, legs) that
    KNEELS next to the always-visible order CTA — the "اطلبي الآن" button in the
    sticky header on desktop, and the mobile sticky bottom bar's CTA on phones. It
    rocks on its knees, clasps its hands and shakes them (begging), every few
    seconds extends one arm to POINT at the button, blinks, lets a tear roll, and
    when the form is filled or the button is hovered it smiles, bounces faster and
    pops a little heart. No text, emotions only.

12. MOBILE: packshot card first in the hero, a sticky bottom bar (thumbnail of the
    selected scent, live total, "اطلبي الآن") that slides in after the hero and
    hides over the order section, scroll-reveal on every section, glowing shimmer
    on the primary CTA, breathing WhatsApp button lifted above the bar. Respect
    prefers-reduced-motion everywhere.

Use neutral grey placeholders for every photo slot; real files will be dropped in.
