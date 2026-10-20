---
name: DPG Home Improvement Inc
description: Yuri, your local handyman in River Edge, NJ. Calm paper and navy bands, one yellow thing to do.
colors:
  navy: "#1c4d8c"
  deep-blue: "#0f2543"
  ink: "#0f2543"
  tape-yellow: "#ffc629"
  tape-yellow-light: "#ffd65c"
  tape-yellow-ink: "#8a5a00"
  paper: "#f4f6fb"
  card: "#ffffff"
  body-text: "#2a3a4c"
  soft-text: "#4a5868"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c9d7ea"
  error-red: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(42px, 12vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  headline-phone:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 9vw, 52px)"
    fontWeight: 400
    lineHeight: 1
    fontFeature: "tnum"
  title-card:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(20px, 5.4vw, 24px)"
    fontWeight: 400
    lineHeight: 1.15
  title-step:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: 1.2
  title-step-desktop:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "22px"
    fontWeight: 400
    lineHeight: 1.2
  title-row:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(18px, 5vw, 20px)"
    fontWeight: 400
    lineHeight: 1.2
  numeral:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1
  button:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
  label:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
  phone-header:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1
    fontFeature: "tnum"
  phone-header-desktop:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1
    fontFeature: "tnum"
  promise:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.7vw, 20px)"
    fontWeight: 400
    lineHeight: 1.5
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  who:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(18px, 5vw, 20px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  input:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.4
  note:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.7
  caption:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1
rounded:
  field: "10px"
  link-row: "20px"
  card: "24px"
  pill: "999px"
  circle: "50%"
spacing:
  gutter-phone: "20px"
  gutter-desktop: "40px"
  section-phone: "64px"
  section-desktop: "96px"
  column-gap: "64px"
  tight: "8px"
  control-gap: "10px"
  list-gap: "14px"
  stack: "16px"
  field-gap: "20px"
  item-gap: "24px"
  block-gap: "28px"
components:
  button-primary:
    backgroundColor: "{colors.tape-yellow}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.tape-yellow-light}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  claim-list:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    typography: "{typography.title-card}"
    padding: "16px 0"
  link-row:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    typography: "{typography.title-row}"
    rounded: "{rounded.link-row}"
    padding: "14px 16px 14px 22px"
    height: "72px"
  link-row-arrow-hover:
    backgroundColor: "{colors.tape-yellow}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "44px"
  form-card:
    backgroundColor: "{colors.card}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "clamp(20px, 5vw, 32px)"
  input:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    typography: "{typography.input}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  step-marker:
    backgroundColor: "{colors.tape-yellow}"
    textColor: "{colors.ink}"
    typography: "{typography.numeral}"
    rounded: "{rounded.circle}"
    size: "48px"
  float-text:
    backgroundColor: "{colors.tape-yellow}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "60px"
  header:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    height: "64px"
---

# Design System: DPG Home Improvement Inc

## Overview

**Creative North Star: "The Local Handyman's Calm Front Door"**

The site is Yuri's front door: a one-man handyman in River Edge, NJ, presented as calm, plain and trustworthy rather than loud. The page follows lpmr.co.uk: off-white paper bands alternating with two blues, soft rounded white surfaces, pill buttons, and a rounded display face set at regular weight. Nothing on the page performs; the confidence comes from clear grounds, generous space and one obvious thing to do.

Density is low and the voice is friendly rather than loud. Each band carries one heading, one quieter supporting line and at most two actions. Tape-measure yellow is the only warm colour and is used as a fill for the thing to do (and the step numerals, and the floating text circle); on dark bands a short accent phrase in a heading turns yellow. Proof is a plain divided list on paper. Bands meet with straight edges; the only texture anywhere is the faint 135° line on the blue grounds.

The build rejects the category default (stock-photo hero over a twelve-icon services grid) and any decoration that competes with the words: no illustrations, no divider shapes, no ambient motion beyond the headline's one entrance.

**Key Characteristics:**
- Three grounds: paper, navy, and deep blue; both blues carry a faint 135° line texture.
- Yellow as a fill (buttons, step numerals, float circle); a darker yellow-ink only when yellow must be text or a glyph on light.
- Cal Sans display at weight 400 for every heading, button, label and phone number; system sans body at 16px/1.7.
- Generous rounding: 24px cards, 999px pills, 10px fields, circles for markers.
- Flat DOM with one exception: the floating text circle's soft shadow.
- Straight band edges; the hero is sized to its content, not to the screen.
- Tap targets 44px minimum, buttons 56px, reading text 16px or larger.

## Colors

A cool, calm palette: off-white paper and two saturated blues, warmed by a single tape-measure yellow.

### Primary
- **Navy** (`navy`): ground of the hero (with the line texture) and the closing band (plain). Also the form's hover/focus border and outline colour (the `--focus` role), the caret in fields, the Facebook glyph, and the hover colour of the "didn't open" phone link.
- **Deep Blue** (`deep-blue`): ground of the How-it-works band and the footer, always with the line texture (`repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`). It is the same hex as Ink; the two names mark the ground role and the text role.

### Secondary
- **Tape-Measure Yellow** (`tape-yellow`): fill of the primary button, the step numerals, the floating text circle, the link-row arrow on hover, `::selection`, and the focus ring on dark bands. On dark bands it is also the accent phrase in a heading ("Fixed today.", "works."), the closing phone glyph and link hovers.
- **Tape-Measure Yellow Light** (`tape-yellow-light`): primary button hover fill only.
- **Yellow Ink** (`tape-yellow-ink`): yellow when it has to be a glyph or text on light (5.5:1 on paper): the header phone glyph and its hover text, the claim-list icons.

### Neutral
- **Paper** (`paper`): page ground, header ground, text-field and chip fill (inside the white form card), and the `theme-color`.
- **Card** (`card`): white cards (Facebook row, form) on paper; the hero headline colour; selected-chip text.
- **Ink** (`ink`): headings and labels on light, text on yellow, the selected chip fill.
- **Body Text** (`body-text`): running text on light.
- **Soft Text** (`soft-text`): ledes, "(optional)" markers, placeholders, the note under the submit button, the wordmark subline.
- **On-Dark** (`on-dark`): headings, step titles, ghost-button label and footer links on blue.
- **On-Dark Soft** (`on-dark-soft`): running text, promise line and ledes on blue.
- **Error Red** (`error-red`): field error border and the 15px error message, on the white form card.

Translucent tints are derived, not tokens: the link-row arrow well at rest is ink at 7% (`rgba(15,37,67,.07)`), the ghost border is on-dark at 70%, and the ghost hover wash is white at 10%.

### Named Rules
**The Yellow Is A Fill Rule.** Tape yellow (`#ffc629`) appears as a filled shape or, on blue, as type and glyphs. On paper or white it is never text; use yellow-ink there.

**The Accent On Dark Rule.** An accent phrase inside a heading is yellow, and only on navy or deep bands. Headings on paper stay all ink.

**The Navy Focus Rule.** On light grounds, hover and focus for interactive controls use navy (3px ring with 3px offset; form controls switch their 2px border to navy, the submit button takes a 2px navy outline at 2px offset). On dark bands the ring turns yellow. Yellow is never the outline of a yellow-filled control.

## Typography

**Display Font:** Cal Sans (Google Fonts), falling back to Avenir Next, Segoe UI, system-ui
**Body Font:** system sans stack (-apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Arial, sans-serif)
**Label/Mono Font:** none distinct; phone numbers use tabular figures with -0.12em word spacing

**Character:** A rounded, geometric display face at its single regular weight, set in sentence case with a hair of negative tracking, next to a plain native body face set loose and readable. Friendly, not shouty.

### Hierarchy
- **Display** (`display`): the hero headline only, white, max 12ch; its accent phrase is yellow.
- **Headline** (`headline`): section headings, balanced wrap. The closing phone number runs at `headline-phone`, tabular.
- **Title**: claim-list labels (`title-card`), step titles on deep blue (`title-step`, `title-step-desktop` from 1024px), and the Facebook row label (`title-row`).
- **Button / Label / Phone**: Cal Sans at 18px for buttons, 17px for form labels and legends, 17px (20px from 760px) for the header phone number, 20px for step numerals.
- **Promise / Lede / Who** (system face): the hero promise line (max 30ch on phones), the line under each heading (max 38ch), the closing "who" line.
- **Body** (`body`): everything else; `input` sets field text at 16px/1.4.
- **Note** (`note`, 15px): the line under the submit button and field error messages.
- **Caption** (`caption`, 14px): the "(optional)" marker beside a field label.

### Named Rules
**The One Weight Rule.** Cal Sans is only ever weight 400 and sentence case. Hierarchy comes from size, colour and ground, never from bolding or uppercase. The only bold is a 600-weight phrase inside body copy (the promise's "Yuri, your local handyman.").

**Not part of the system.** The build carries two small pill labels above headings (hero and form). They are a recorded defect, not a pattern: new surfaces open with the heading itself, and the 14px/500 label style and its tinted pill fills are deliberately left off the token set.

**The Sixteen Floor Rule.** Reading text and form inputs are 16px or larger (prevents iOS zoom). The 15px note and 14px caption are the only smaller sizes, and they are never the main message.

## Layout

A single centred column (max 1160px) with 20px gutters on phones and 40px from 760px. Bands are padded 64px top and bottom on phones and 96px from 760px. From 1024px, the trust and form bands become two columns with a 64px gap, aligned top, and the steps become three columns with a 40px gap (the form section is 1fr / 1.2fr, with the heading block sticking 40px from the top). The closing band switches to content plus the big phone number, bottom-aligned with a 48px gap. The footer is padded 48px top and 96px plus the bottom safe area below, clearing the float circle.

Band order: paper header, textured navy hero, paper trust, textured deep How-it-works, paper form, plain navy close, textured deep footer. Bands meet on straight edges with no dividers.

The hero is sized to its content: 64px top and 72px bottom padding on phones, 96px / 112px from 760px, with 20px between headline, promise and actions. On phones the two hero buttons stack full width with a 12px gap; from 760px they sit in a row at 240px minimum each.

Rhythm inside bands: 16px between heading and lede; 28–36px to the list, steps or form; 20px between form fields and 8px from label to field; hairline-divided claim rows; 24px between steps. Below 380px chip padding tightens from 18px to 14px so three chips fit on a line.

### Named Rules
**The Number Top-Right Rule.** On the first screen the phone number appears once, as a tap-to-call link in the header's top-right corner. Under the hero headline there are at most two buttons, and neither is a Call button. The number comes back in the closing band and the footer only.

**The One Circle Rule.** The only fixed element is a single 60px yellow text circle, bottom-right with 16px plus safe-area insets. It appears after the hero leaves view and hides while the form is on screen. Never a sticky bottom bar, never a call button.

**The Clear Zone Rule.** Nothing runs behind text except the faint 135° lines on the navy and deep-blue grounds. No images, shapes or motion sit behind headings or copy, and bands meet with straight edges, never a divider shape.

## Elevation & Depth

The DOM is flat. Cards lift off paper by tone (white on `#f4f6fb`), fields sit back into the white card by tone (paper inside white), and the blue grounds get a whisper of texture from the 135° lines. The one shadow is the floating text circle (`0 10px 28px rgba(8,24,46,.3)`), because it floats over every ground.

### Named Rules
**The Floating Only Rule.** A DOM shadow is reserved for the one element that floats over content. Cards, buttons and fields get tone, never shadow.

## Shapes

Soft and generous. The form card takes 24px corners; the Facebook row is a slightly tighter 20px because it is a single short row. Buttons and chips are full pills (999px). Text fields use 10px corners. Circles mark three roles: step numerals (48px), the link-row arrow well (44px) and the floating text circle (60px). Borders are 2px where they appear (button outlines, field and chip borders, transparent at rest so focus never shifts layout). Focus rings are 3px with a 3px offset (2px/2px on the submit button).

Off-system by design: the focus ring's 6px corner, a browser-outline softening rather than a surface radius.

## Components

### Buttons
Big, round and thumb-sized.
- **Shape:** pill (999px), 56px minimum height, 26px side padding, 2px border, Cal Sans 18px label, optional 20px line icon with a 10px gap.
- **Primary:** tape yellow fill and border, ink label. Full width inside the form.
- **Hover / Focus:** hover (pointer devices only) lightens to yellow-light over 0.2s. Press scales to 0.98 (0.12s). Focus is the yellow ring on dark bands; inside the form the submit button takes a 2px navy outline on hover and focus.
- **Ghost:** transparent with a 2px on-dark border at 70% opacity and an on-dark label. Hover turns the border white and adds a 10% white wash. Used for the hero's second action (Text Yuri) on navy, never filled.

### Claim List
A quiet list straight on the paper: a 40px yellow-ink line icon and a Cal Sans title label per row, 16px vertical padding, hairline dividers (`--line`, 12% ink) between rows. No card, no fill, so it never reads as tappable next to the Facebook row. On phones the Facebook row follows the list; from 1024px the list takes the right column and the Facebook row sits under the intro.

### Link Row (Facebook)
A white row with 20px corners, 72px minimum height, a 28px navy brand glyph, a Cal Sans label and a 44px circular arrow well pushed right.
- **Hover:** only the arrow well changes, from 7% ink to yellow. The row never gets an outline, tint or shadow.
- **Focus:** the row's own ring is suppressed; the arrow well fills yellow and takes a 3px navy ring with a 3px offset.

### Steps
A numbered list on deep blue. Each item has a 48px yellow circle holding a Cal Sans 20px ink numeral, then an on-dark Cal Sans title and an on-dark-soft detail line. Static; no cards, no connectors.

### Inputs / Fields
Inside a white form card (24px corners, 20–32px padding, max 600px).
- **Style:** borderless-looking tinted fields: paper fill, ink 16px text, 2px transparent border, 10px corners, 13px/14px padding, 52px minimum height (textarea 120px, vertical resize). Labels sit above in Cal Sans 17px; "(optional)" is a 14px soft caption.
- **Hover / Focus:** the border turns navy (0.15s). No outline ring on fields; the border is the focus.
- **Error:** border turns error red and a 15px red message appears below. Errors clear as soon as the visitor types.

### Chips (form choices)
Radio choices as 48px pills on paper fill, 18px padding, 16px ink system text, 2px transparent border.
- **Selected:** ink fill, white label.
- **Hover / Focus:** navy border. Chips exist only as real form controls.

### Navigation (Header)
A paper bar, 64px tall (76px from 760px), respecting the top safe area. Left: the DPG wordmark lockup (Cal Sans "DPG" over a small uppercase soft-text company line). The lockup's sizes (21px, 24px from 760px; 11px subline) are drawing values for the wordmark, kept off the type ramp; the uppercase subline is not a label style to reuse. Right: the phone number as a tap-to-call link in Cal Sans with tabular figures and an 18px yellow-ink phone glyph; hover turns it yellow-ink. No menu. The footer repeats the business name, owner line, number and a Facebook link (44px targets, yellow on hover) on textured deep blue.

### Floating Text Circle
A 60px yellow circle with a 26px ink chat glyph, opening a prefilled SMS. It slides up from 120px below the viewport (0.35s, `cubic-bezier(.2,.8,.2,1)`) once the hero is out of view and slides away while the form is visible. Focus ring is navy, circular.

### Fade-Up
The single scroll motion: elements that start below the first screen rise 12px and fade in over 400ms ease-out as they enter. Everything above the fold is visible at rest; reduced motion disables it entirely. Smooth scroll is on, off under reduced motion; there is no other ambient motion.

### Hero Headline Bounce-In
The hero H1 only (after lpmr.co.uk, Ellie's pick): on load, JS splits it into letters inside nowrap word wrappers. Each letter slides in from 50px right and fades from 0 over 1s on `cubic-bezier(.34,1.56,.64,1)` (back-out, a slight overshoot), 20ms apart. The H1 carries an `aria-label` with the full text and the letter spans are `aria-hidden`. When the last letter lands, the plain heading is restored, so kerning and selection come back. No JS or reduced motion: the plain heading shows straight away. Never put it on other headings.

## Do's and Don'ts

### Do:
- **Do** alternate paper with navy or deep-blue bands (the hero and every deep band carry the faint line texture; the closing navy is plain) and let them meet on a straight edge.
- **Do** use tape yellow as a fill for the primary action, step numerals and the float circle, and yellow-ink (`#8a5a00`) when yellow must be a glyph on light.
- **Do** set every heading, button, label and phone number in Cal Sans at weight 400, sentence case.
- **Do** put the form in a white 24px card on paper and the claims in a plain divided list; keep buttons and chips as full pills.
- **Do** show hover and focus in navy on light grounds and in yellow on dark bands, with a 3px ring at a 3px offset.
- **Do** put hover styles inside `@media (hover:hover)` so taps don't leave them stuck.
- **Do** keep tap targets at 44px minimum and buttons at 56px, with reading text at 16px or larger.
- **Do** keep motion to the hero H1 bounce-in, the below-the-fold fade-up and the float circle, all off under reduced motion.

### Don't:
- **Don't** set yellow (`#ffc629`) as text on paper or white.
- **Don't** put a yellow accent phrase in a heading on a paper band.
- **Don't** bold or uppercase Cal Sans.
- **Don't** add a box-shadow to cards, buttons or fields; the floating text circle is the only shadowed element.
- **Don't** show the phone number twice on the first screen, put a Call button under the hero headline, or add a sticky bottom bar.
- **Don't** let any texture other than the blue grounds' faint lines run behind text, or join bands with divider shapes, curves or images.
- **Don't** style non-interactive labels or town names as chips.
- **Don't** add decorative motion or effects (ambient animation, sheens, particles); the hero H1 bounce-in is the one entrance and stays on the H1.
