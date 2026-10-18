# DPG Home Improvement Inc — handoff at ~60%

**Live:** https://10elizabethbell.github.io/dpgHomeImprovement/ · **Repo:** https://github.com/10elizabethbell/dpgHomeImprovement · **Built:** 2026-10-18 from Muse brief of 2026-10-18 (flyer post in "The Contractors Lounge NJ")

## What's built
- One page, `index.html`, single file, phone first. Sections: header (wordmark + tap-to-call number top right), hero, "I treat your home like mine" (three flyer claims + Facebook link), How it works, "Tell me what's broken" form, closing (name, big phone number, area line), footer.
- World: a hardware-store parts tray. Parts-bin blue grounds, galvanized-zinc light sections, tape-measure yellow for the primary button.
- Signature: a canvas pile of shaded zinc/brass/black nuts, washers, screws and bolts under the hero buttons, plus two divider bands. It sways, a part drops in about every 1.5s, mouse or finger pushes parts away, and parts pushed up break loose, fall back and bounce. The hero pile takes drags in every direction on phones (`touch-action:none`); the bands keep vertical scroll (`pan-y`). Tunables are at the top of the first `<script>` (`SWAY`, `DROP_EVERY`, `PUSH_R`, `PUSH`, `GRAVITY`, `LOOSE`…).
- Contact: `tel:+12013428837` (header, form note, close, footer). Hero "Text Yuri" opens SMS with a starter message. The form composes "Hi Yuri, this is <name>. I need help with: … Where: … When: …" into an SMS.
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

## Not verified
- Real-device touch (iPhone Safari, Facebook in-app browser on iOS/Android); tested with simulated touch and mouse sweeps headlessly.
- Real SMS handoff on iOS and Android (`sms:+12013428837?&body=`).
- Frame rate on older phones (phone pile is up to ~760 parts at 1.5x DPR).
