# Portfolio — Session Notes

A chronological map of the design iterations explored in this working session, tied to each prompt so any part can be redone. **Note:** the session ended by restoring the original template (`7b5e57d`), so the iteration work below is *not* currently in the files — this is your guide to recreate any step.

---

## Cursor experiments (scratch files, later removed)

1. **"different designs for cursor changes"** — created `cursor-demo.html` with 5 cursor styles + switcher (glowing dot+ring, blend/invert, grow-on-hover, emoji, particle trail).
2. **"none of these, more ideas"** — added 7 more (spotlight, magnetic, snake trail, crosshair reticle, label reveal, elastic stretch, neon rainbow).
3. **"something unique"** — created `cursor-unique.html` (magnetic repel text, gravity text, liquid metaballs, **constellation web**, spotlight reveal, googly eyes, ink brush).
4. **"add Constellation web"** — wired it into the site; discovered a CSS/HTML mismatch.

## Recovery + baseline

5. **"why is my website messed up?"** — diagnosed a half-finished redesign; restored files to last commit.
6. **"I need a redesign… make it mine"** — identified it as the **iPortfolio template**; committed checkpoint `7b5e57d`; began a full redesign.
7. **"keep older colors… iterate on original"** — reverted the big redesign.

## Sidebar iterations

8. **"make the sidebar look different"** — profile photo ring/glow, outlined social icons, rounded nav items, active accent bar, edge hairline.
9. **"make it more useful" (picked 1,2,3,5)** — role tagline, availability status pill, location, scroll progress + "Viewing [section]" label.
10. **"remove Scroll progress"** — removed the progress bar.
11. **"remove Viewing Resume too"** — removed the section label.
12. **"'open to opportunities' — change or remove"** — removed the status pill.
13. **"make icons colorful"** — brand-colored social icons (Teams / GitHub / Discord / LinkedIn).
14. **"make sidebar clear, match hero"** — sidebar background = hero image + dark overlay.
15. **"colors stay fixed while scrolling?"** — explained; offered options.
16. **"Themed gradient"** — navy/cyan themed gradient (no image).
17. **"more translucent"** — frosted-glass sidebar + dark backdrop strip.

## Hero / Home iterations

18. **"improve home, keep image, dislike buttons"** — gave suggestions.
19. **"1,2 (Makhdoom Sahib bg); 3 no 'hello', text = who I am/skills; 4b"** — richer gradient overlay, Makhdoom Sahib location caption, skill/identity typed text, removed buttons, added scroll cue.
20. **"remove location + scroll cue"** — removed both.

## Navigation rework

21. **"left nav looks odd, want subtle" (picked C)** — floating menu button + slide-in panel, full-width content, dimming overlay.
22. **"put title/location/socials in hero, remove navbar, add scroll cue"** — consolidated everything into hero, removed nav entirely.

## Hero richness

23. **"change running text, don't keep hero plain"** — punchier rotating phrases + animated constellation layer + gradient-animated name + glass card.
24. **"revert last 2 changes"** — cleaned up leftover code.

## Reset

25. **"I messed up, checkpoint?"** — only the original-template checkpoint existed.
26. **"restore original template"** — **restored to `7b5e57d`** (current state).

---

## Ideas worth revisiting

- **Sidebar:** colorful brand social icons; frosted-glass panel with a dark backdrop for readability; active-nav accent bar.
- **Hero:** glass card behind text; gradient-animated name + accent line; animated constellation particle layer; skill/identity typed phrases (not job-title billboard); Makhdoom Sahib location caption.
- **Navigation:** minimal floating menu button with slide-in panel + dimming overlay (option C), OR fully nav-less single-scroll page.
- **Palette to preserve:** `#149ddd` / `#37b3ed` cyan accents on `#040b14` dark navy; violet `#a06bff` as a secondary accent.

## Workflow reminder

Going forward, commit a checkpoint after each liked change so exact states can be restored instead of lost:

```powershell
git add -A; git commit -m "Checkpoint: <describe the change>"
```
