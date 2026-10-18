---
name: DPG Home Improvement Inc
description: Yuri, your local handyman in River Edge, NJ. A parts tray, not a services grid.
colors:
  parts-bin-blue: "#1c4d8c"
  parts-bin-blue-deep: "#123766"
  blue-ink: "#0f2543"
  galvanized-zinc: "#eef2f6"
  zinc-seam: "#dfe6ee"
  steel: "#5d6b7c"
  paper: "#f7f9fb"
  on-blue: "#f4f7fb"
  on-blue-quiet: "#c9d7ea"
  tape-yellow: "#ffc629"
  tape-yellow-light: "#ffd65c"
  form-orange: "#ff8a1f"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(46px, 14.6vw, 96px)"
    fontWeight: 900
    lineHeight: 0.9
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(30px, 8.4vw, 52px)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(19px, 5.4vw, 24px)"
    fontWeight: 800
    lineHeight: 1.1
    letterSpacing: "-0.01em"
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 20px)"
    fontWeight: 400
    lineHeight: 1.5
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 800
    lineHeight: 1.2
rounded:
  control: "12px"
  button: "14px"
  round: "50%"
spacing:
  gutter-phone: "20px"
  gutter-desktop: "40px"
  section-phone: "64px"
  section-desktop: "96px"
  column-gap: "64px"
  stack: "28px"
components:
  button-primary:
    backgroundColor: "{colors.tape-yellow}"
    textColor: "{colors.blue-ink}"
    typography: "{typography.label}"
    rounded: "{rounded.button}"
    padding: "0 24px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.tape-yellow-light}"
    textColor: "{colors.blue-ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-blue}"
    typography: "{typography.label}"
    rounded: "{rounded.button}"
    padding: "0 24px"
    height: "56px"
  button-ghost-hover:
    textColor: "{colors.tape-yellow}"
  input:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.blue-ink}"
    typography: "{typography.body}"
    rounded: "{rounded.control}"
    padding: "14px 16px"
    height: "54px"
  chip:
    backgroundColor: "transparent"
    textColor: "{colors.on-blue}"
    rounded: "{rounded.control}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.on-blue}"
    textColor: "{colors.blue-ink}"
  link-row:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.blue-ink}"
    rounded: "{rounded.button}"
    padding: "12px 20px"
    height: "64px"
  link-row-arrow:
    backgroundColor: "{colors.zinc-seam}"
    textColor: "{colors.blue-ink}"
    rounded: "{rounded.round}"
    size: "36px"
  link-row-arrow-hover:
    backgroundColor: "{colors.tape-yellow}"
  step-marker:
    backgroundColor: "{colors.parts-bin-blue}"
    textColor: "{colors.on-blue}"
    rounded: "{rounded.round}"
    size: "48px"
  header:
    backgroundColor: "{colors.parts-bin-blue}"
    textColor: "{colors.on-blue}"
    height: "64px"
---

# Design System: DPG Home Improvement Inc

## Overview

**Creative North Star: "The Parts Tray"**

The site is a hardware-store parts tray: a flat field of parts-bin blue and galvanized zinc, set in heavy uppercase type, with a real pile of zinc, brass and black-oxide nuts, washers, screws and bolts that the visitor can stir. All the depth and material lives in that pile. The page around it stays flat, firm and plain, like the painted bin the parts sit in.

Density is low and the voice is loud. Each screen carries one claim in very heavy uppercase, one supporting line in a quieter tone, and at most two actions. Tape-measure yellow marks the single thing to do. Proof is a plain list with hairline seams, not a grid of cards. The pile comes back between sections as a thin band riding the seam where blue meets zinc, so the tray holds the whole page together.

The build rejects the category default (stock-photo hero over a twelve-icon services grid) and any effect that doesn't read as a real object. The parts are drawn as hardware, lit from one side.

**Key Characteristics:**
- Two grounds only: parts-bin blue and galvanized zinc, alternating by section, with deep blue for the footer.
- One yellow action per view; orange appears only inside the form.
- Heavy 900-weight uppercase headings with tight negative tracking, on the house system font stack.
- Flat DOM surfaces. Depth comes only from the canvas parts, lit from the upper left.
- Live parts pile in the hero (drops, pushes, taps) and as seam bands between sections.
- Tap targets 44px minimum, buttons 56px, body never below 16px.

## Colors

A two-ground workshop palette: a saturated mid blue and a cool galvanized grey, with one hot yellow for action and one orange held back for the form.

### Primary
- **Parts-Bin Blue** (`parts-bin-blue`): ground of the header, hero, form section and the seam bands. Also the `theme-color`, the step markers, claim icons, the Facebook row's border and the closing phone number on zinc.
- **Parts-Bin Blue Deep** (`parts-bin-blue-deep`): the footer ground and the closing phone number's hover color. It reads as the bottom of the bin.

### Secondary
- **Tape-Measure Yellow** (`tape-yellow`): fill of the primary button, the second line of the hero headline ("Fixed today."), the header phone glyph, link hover text on blue, the link-row arrow on hover, `::selection`, and the default focus ring on blue.
- **Tape-Measure Yellow Light** (`tape-yellow-light`): primary button hover fill only.

### Tertiary
- **Form Orange** (`form-orange`): hover outline, focus outline and error border for every control inside the form (text fields, chips, the submit button). Nowhere else.

### Neutral
- **Blue Ink** (`blue-ink`): text on all light grounds, text on yellow and on paper fields.
- **Galvanized Zinc** (`galvanized-zinc`): ground of the light sections.
- **Zinc Seam** (`zinc-seam`): the 1px hairlines between claim rows and the resting fill of the arrow circle.
- **Steel** (`steel`): secondary text on zinc (ledes, step details, service-area line). Also the placeholder color in form fields.
- **Paper** (`paper`): text field fill and the Facebook row's fill. A hair lighter than zinc, so controls lift off the ground by tone, not shadow.
- **On-Blue** (`on-blue`): primary text on blue and the selected chip's fill.
- **On-Blue Quiet** (`on-blue-quiet`): secondary text on blue (promise line, ledes, optional markers, footer copy, the wordmark subline).

### Named Rules
**The Two Grounds Rule.** Every section sits on parts-bin blue or galvanized zinc; the footer alone is deep blue. Consecutive sections on different grounds are joined by a parts band whose pile fills down into the next section's color, never by a straight hard edge.

**The One Yellow Rule.** Yellow fill belongs to the primary action. Everywhere else yellow is a stroke, glyph, type or hover state, and only one yellow-filled button is visible at a time.

**The Orange Stays In The Form Rule.** Orange is the form's hover/focus/error accent and appears on no other surface. It exists because yellow is already the submit button's fill and can't also be its outline.

## Typography

**Display Font:** System UI stack (-apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", Arial, sans-serif)
**Body Font:** the same stack
**Label/Mono Font:** none distinct; phone numbers use `tabular-nums`

**Character:** One family pushed to its extremes. Headings are black-weight, uppercase and tightly tracked so they read like stencilled bin labels. Body copy is plain and roomy. The system stack is a deliberate house choice for these sites (fast, native on the phones visitors use, nothing to load) and is part of the system, not a placeholder.

### Hierarchy
- **Display** (900, clamp 46–96px, line-height 0.9, -0.035em, uppercase): the hero headline only. Its second phrase breaks onto its own line in tape yellow.
- **Headline** (900, clamp 30–52px, line-height 1, -0.02em, uppercase, balanced wrap): section headings. The closing heading runs one step larger (clamp 34–56px, line-height 0.95). The closing phone number is set at this weight and size (clamp 30–52px, 900, tabular).
- **Title** (800, clamp 19–24px, 30px at 1024px+, line-height 1.1, -0.01em, uppercase): claim rows. Step titles use the same weight in sentence case (20px, 22px desktop, line-height 1.2).
- **Lede** (400, clamp 17–20px, line-height 1.4–1.5, max 30–36ch): the promise line under the hero and the line under each section heading, in the quiet tone of its ground.
- **Body** (400, 16px, line-height 1.55): everything else. Max 40ch for short notes.
- **Label** (800, 16px): buttons, form labels, the header phone number (20px on desktop), footer links (700).

### Named Rules
**The Heavy Caps Rule.** Headings and claim rows are 800–900 weight, uppercase, with negative tracking and line-height at or below 1.1. Body, ledes, step text, form copy and buttons are never uppercase.

**The Sixteen Floor Rule.** No reading text below 16px, form inputs included (prevents iOS zoom). Hierarchy comes from weight and case, not tiny sizes.

## Layout

A single centered column (max 1160px) with side gutters of 20px on phones and 40px from 760px. Sections are padded 64px top and bottom on phones and 96px from 760px. From 1024px, content sections become two equal columns with a 64px gap, aligned top: heading and lede on the left, the list, steps or form on the right. In the form section the left column sticks 40px from the top while the form scrolls. The closing section switches to content plus a right-aligned phone number, aligned to the bottom.

The hero fills the first screen (`min(100svh, 860px)` minus the header on phones, 900px cap on desktop). Copy sits at the top in its own zone; the parts pile fills all remaining height below it (190px minimum on phones, 320px on desktop), so the pile never runs behind text. On phones the two hero buttons stack full width; from 760px they sit in a row at 240px minimum each, and the promise line stays on one line.

Parts bands are 120px tall (150px desktop) and full bleed. Vertical rhythm inside sections: 16px from heading to lede, 28–32px to the list or form, 20px between form fields, 22px between steps. Below 380px, chip padding tightens from 18px to 13px so the three chips fit on one line.

### Named Rules
**The Number Top-Right Rule.** On the first screen the phone number appears once, as a tap-to-call link in the header's top-right corner. Under the hero headline there are at most two buttons, and neither is a Call button. The number comes back in the closing section and the footer only. No sticky bottom bar, ever.

**The Clear Zone Rule.** Text never sits over the pile. The hero copy has its own band above the tray, and bands sit between sections, never behind headings.

## Elevation & Depth

The DOM is flat: no box-shadows on any surface or control. Controls lift off their ground by tone (paper on zinc, paper on blue) and by 2px borders. All depth belongs to the canvas parts. Each part is a pre-baked sprite with a soft drop shadow falling straight down (`rgba(8,20,40,.42)`, blur 0.22× and offset 0.1× the part's size), a single upper-left light wash, a soft specular spot on the same side of every part, and up to two steps of darkening for parts buried deeper in the pile. The pile's body below its loose top layer is a slate gradient (`#4a5665` to `#232b36`) on the hero, or the next section's ground color on bands.

### Named Rules
**The One Light Rule.** Every part on the page is lit from the upper left and casts its shadow downward, whatever its rotation. Sprites are baked at eight fixed turns so the light never rotates with the part.

**The Flat Bin Rule.** Shadows are for hardware, not for interface. A DOM element that needs emphasis gets a border, a tone shift or yellow, never a shadow.

## Shapes

Firmly rounded rectangles, never pills. Buttons and the link row use 14px corners; text fields and chips use slightly tighter 12px corners. Circles are reserved for two roles: the numbered step markers (48px) and the arrow well at the end of a link row (36px). Borders are 2px everywhere they appear (button outlines, chip outlines, link-row border, field borders), 3px for error fields, and 1px only for the hairlines between claim rows. Focus rings are 3px with a 3px offset (2px/2px inside the form), with a 6px radius. The hardware itself supplies the organic silhouette: hex nuts, washers, slotted screws and bolts with threads.

## Components

### Buttons
Big, blunt and thumb-sized.
- **Shape:** 14px corners, 56px minimum height, 24px side padding, 2px border, 16px/800 label, optional 20px line icon with a 10px gap.
- **Primary:** tape yellow fill and border, blue-ink label. Full width inside the form.
- **Hover / Focus:** hover (pointer devices only) lightens to yellow-light over 0.18s. Press nudges down 1px (0.12s). Focus shows the 3px yellow ring on blue. Inside the form the submit button takes the orange 2px outline on hover and focus instead.
- **Ghost:** transparent with a 2px on-blue border at 70% opacity and an on-blue label. Hover turns border and label yellow. Used for the hero's second action (Text Yuri), never filled.

### Link Row (Facebook)
A paper row with a 2px blue border, 14px corners, 64px minimum height, a 28px brand glyph, a 16–20px/800 label and a 36px circular arrow well pushed to the right.
- **Hover:** only the arrow well changes, from zinc-seam to yellow. The row itself never gets an outline, tint or ring.
- **Focus:** the row's own ring is suppressed; the arrow well fills yellow and takes a 3px blue ring with a 3px offset.

### Claim List
Not cards. A plain list of rows (14px vertical padding, 20px on desktop) with a 40px (48px desktop) blue line icon and a Title-style uppercase label, separated by 1px zinc-seam hairlines. Rows are not interactive and must not look interactive.

### Steps
A numbered list. Each item has a 48px blue circle holding a 900-weight 20px numeral, then a 20–22px/800 title and a steel detail line. Static; no cards, no connectors.

### Inputs / Fields
- **Style:** paper fill, blue-ink 16px text, 2px transparent border, 12px corners, 14px/16px padding, 54px minimum height (textarea 120px, vertical resize). Labels sit above in 16px/800; "(optional)" is a quieter 600-weight small in the on-blue-quiet tone.
- **Hover / Focus:** hover turns the border orange. Focus adds a 2px orange outline at a 2px offset plus the orange border. Transition 0.15s.
- **Error:** border goes orange at 3px, and a 16px/700 message appears below in a pale orange (`#ffd0a6`) for contrast on blue. Errors clear as soon as the visitor types.

### Chips (form choices)
Radio choices styled as 48px-tall chips with 12px corners and 18px padding, on blue.
- **Unselected:** transparent with a 2px on-blue border at 55% opacity, 700-weight on-blue label.
- **Selected:** on-blue fill, blue-ink label.
- **Hover / Focus:** orange border on hover (selected or not); keyboard focus adds the orange 2px outline. Chips exist only as real form controls; non-interactive labels and service-area towns are never chips.

### Navigation (Header)
A blue bar, 64px tall (76px desktop), respecting the top safe area. Left: the DPG wordmark (900, 21px/24px, uppercase) over the company name in a small on-blue-quiet subline. Right: the phone number as a tap-to-call link, 16px/800 (20px desktop) tabular figures with an 18px yellow phone glyph; hover turns it yellow. No menu. The footer repeats the business line and a Facebook link (44px targets, yellow on hover) on deep blue.

### Parts Tray (signature)
A canvas pile of nuts, washers, screws and bolts in zinc (most), brass and black oxide, drawn from seeded random positions along a wavy surface. One shared animation loop runs every tray on the page and pauses trays that are off screen.
- **Ambient:** only the top layer sways and rocks (3.4px rise, 0.14rad tilt); buried parts sit still. In the hero a surface part pops up and drops back in about every 1.5s.
- **Interaction:** pointer or finger pushes parts within a 70px reach (91px on desktop), carrying some of the pointer's speed; parts pushed 18px above home break loose and fall under gravity, bounce, and jostle their neighbors. A tap flips the nearest top part into the air. The hero canvas takes all touch directions (`touch-action: none`); bands allow vertical page scroll.
- **Bands:** a single layer of parts on the seam, with the pile body filled in the next section's ground color.
- **Reduced motion:** the pile is drawn once as a still and redrawn only on resize. Before the script runs, a CSS gradient mound stands in.

## Do's and Don'ts

### Do:
- **Do** alternate parts-bin blue and galvanized zinc grounds, and join them with a parts band that fills into the next ground.
- **Do** keep one yellow-filled action in view; secondary actions on blue are ghost-outlined (2px, 14px corners).
- **Do** outline every form control in form orange on hover and on focus (2px outline, 2px offset), and use orange only there.
- **Do** change only the arrow well on hover for tappable rows with an arrow (zinc-seam to yellow), and put their focus ring on the arrow.
- **Do** put hover styles inside `@media (hover:hover)` so taps don't leave them stuck.
- **Do** set headings at 900 weight, uppercase, tracked -0.02em to -0.035em, line-height 1 or below, on the system font stack.
- **Do** keep tap targets at 44px minimum and buttons at 56px, with text at 16px or larger.
- **Do** light every part from the upper left with its shadow falling down, and give the pile a still frame under reduced motion.

### Don't:
- **Don't** put a box-shadow on any DOM surface or control; depth is tone, border, and the canvas parts.
- **Don't** show the phone number twice on the first screen, put a Call button under the hero headline, or add a sticky bottom bar.
- **Don't** turn proof or claims into cards; they are a plain list with 1px hairlines.
- **Don't** style non-interactive labels or town names as chips or pills; chips are for real form choices only.
- **Don't** let the pile, or any pattern, run behind text.
- **Don't** use pill (fully rounded) buttons; corners are 12–14px.
- **Don't** add effects that don't read as real hardware (sheens, glints, abstract particles).
