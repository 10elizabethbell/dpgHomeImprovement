# DPG Home Improvement Inc — handoff at ~60%

**Live:** https://10elizabethbell.github.io/dpgHomeImprovement/ · **Repo:** https://github.com/10elizabethbell/dpgHomeImprovement · **Built:** 2026-10-18 from Muse brief of 2026-10-18 (flyer post in "The Contractors Lounge NJ")

## What's built
- One page, `index.html`, single file, phone first. Sections: header (wordmark + tap-to-call number top right), hero, "I treat your home like mine" (three flyer claims + Facebook link), How it works, "Tell me what's broken" form, closing (name, big phone number, area line), footer.
- World: a hardware-store parts tray. Parts-bin blue grounds, galvanized-zinc light sections, tape-measure yellow for the primary button.
- Signature: a canvas pile of shaded zinc/brass/black nuts, washers, screws and bolts under the hero buttons, plus two divider bands. The surface sways, a part drops in about every 1.5s (and jostles its neighbours when it lands), mouse or finger pushes parts away, parts pushed up break loose and bounce back, and a tap flips the nearest part into the air. One fixed light, so every highlight and shadow points the same way. The divider bands are one layer of parts riding a wavy seam into the next section's colour. The hero pile takes drags in every direction on phones (`touch-action:none`); the bands keep vertical scroll (`pan-y`). Tunables are at the top of the first `<script>` (`SWAY`, `DROP_EVERY`, `PUSH_R`, `PUSH`, `GRAVITY`, `LOOSE`…).
- Contact: `tel:+12013428837` in the header (top right) and the closing section; the footer shows the number as plain text so the bottom screen has one tappable copy. If the SMS app doesn't open after the form, a status line offers the call link. Hero "Text Yuri" opens SMS with a starter message. The form composes "Hi Yuri, this is <name>. I need help with: … Where: … When: …" into an SMS.
- Favicon / home-screen icon: "DPG" in the site's lettering, yellow on blue (no logo exists). `og.png` is a 1200×630 capture of the hero.

## Assumptions I made
- **Colors:** none known (flyer image unobtainable), so blue/zinc/yellow come from the hardware world, not his brand. Swap if the flyer or van has colors.
- **Voice:** first person, one man ("I"), because the flyer says "Yuri, your Local Handyman".
- **Copy I wrote for him (approve with Yuri):** "Broken today. Fixed today." (from "Same Day Repair"), "I treat your home like mine.", "I show up when I say I will, fix it properly, and stand behind the work.", "If my work fails, I come back." (from the one-year labor warranty), "at a fair price" (from "affordable prices").
- **Texting:** the brief says texts are unknown. Calling is in the header; texting is the hero's second button and the form's handoff, with a call link under the form button.
- **Audience:** treated as general homeowners, so the motion is on. If Yuri's customers skew 40+, switch to the still version (`older-audience.md`); reduced motion already draws one still frame.

## Placeholders and gaps
- **No photos at all.** The flyer is a Facebook group photo that needs a login; no work photos, logo, van or portrait. No proof section with images yet.
- **No itemized services** (the flyer says "Wide Range Of Services"), so there's no services list. The form invites "ask anyway".
- **License number left off.** "HCB License # 13VH1425300" returned no match on the NJ Division of Consumer Affairs lookup (searched 2026-10-18 by number). The usual format is 13VH + 8 digits (e.g. 13VH01425300); the flyer OCR may have dropped a digit. A full surname search lists Yampolskys, but I couldn't finish filtering it (a permission block stopped the follow-up). Verify, then add it to the claims list.
- "Fully insured and bonded" and "One-year warranty on labor" are shown as his own flyer claims; not verified.
- No email (footer has none, by design until one exists). No hours, no towns beyond River Edge, no reviews, no prices.
- Facebook link goes to his **personal** profile (only one found). A business page would be better if he makes one.

## Questions for the owner
- Can I have the flyer image and photos of recent jobs (before/after especially)?
- What do you fix most? (a short services list: faucets, doors, drywall, assembly…)
- Which towns do you cover besides River Edge?
- Do you take texts? If not, the hero "Text Yuri" button and form become call-first.
- Your exact HIC license number, and do you want it on the site?
- Hours, and whether there's an email to put in the footer.
- Colors or a logo you use anywhere (truck, cards)?

## Ideas not built (yours to pick)
- **Runner-up world: pegboard tool wall.** Hammer, wrench, level, tape measure hung on hooks that swing like pendulums when touched, sent spinning on a hard flick.
- Other candidates: spirit-level bubble vials, carbon-copy work-order pad with a "FIXED" stamp, drywall you spackle smooth.
- When photos arrive: a work gallery under the claims (photos set into parts-tray bins), Facebook link directly under it ("Click to see more of my work.").
- Before/after sliders if he has pairs.
- Splash reward: a small clatter of parts when the form is sent.

## Review trail
- Impeccable, every mode except `live` (and `onboard`, no first-run flow): critique, audit, harden, optimize, adapt, clarify, polish, distill, quieter, bolder, layout, typeset, colorize, animate, delight, overdrive, extract. Their fixes are applied (focus contrast, form error a11y, hover only on hover devices, desktop layout, metal lighting, physics).
- Finish reviewer: first verdict `fix` (8 items), all 8 scored resolved on the second pass. The one regression it found (footer number wrapping at 360) is fixed but wasn't re-reviewed.
- Detector: 0 findings, but only because of value ignores in `.impeccable/config.json`. These cover the one-off values DESIGN.md doesn't list: 6px focus corner, 22px placeholder corner, the 21/11px wordmark, #ffd0a6 error text, the closing heading and "who" line (via their 34px and 18px lower endpoints, which are now allowed site-wide), and the 22px desktop step titles. The detector reports a fluid clamp() by its first endpoint only, so whole-clamp and upper-endpoint (56px) entries never match and were removed, as was `dark-glow #0f2543` (dark-glow findings carry no value, so a value ignore can't match them). A cleaner fix is to add those sizes to DESIGN.md's type scale and drop the ignores.

## Not verified
- Real-device touch (iPhone Safari, Facebook in-app browser on iOS/Android); tested with simulated touch and mouse sweeps headlessly.
- Real SMS handoff on iOS and Android (`sms:+12013428837?&body=`).
- Frame rate on older phones (phone pile is up to ~760 parts at 1.5x DPR).
