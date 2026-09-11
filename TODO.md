# Open items

- **Name the mascots.** Técnico (teal/gold mask, red cape) and rudo
  (unmasked, long hair, discreet goatee, black/silver) both still
  unnamed.
- **Alt text / accessible descriptions for each background image.**
  These are CSS `background-image`s on slide `<div>`s, not `<img>`
  tags, so there's no native `alt` attribute — screen readers skip
  them by default. Need a deliberate mechanism (e.g. visually-hidden
  text per slide, or `aria-label` on the `.slide-background` /
  section) with a plain-English description per asset in `assets/`,
  not an assumption that it's handled already.
