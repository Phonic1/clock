# Clockwise – Telling the Time

An installable, offline-ready web app (PWA) for teaching analog clock time:
**o'clock, half past, quarter past, quarter to and five-minute steps.**

## What's inside

**Learn** – a big draggable teaching clock for the interactive screen.
- Drag the long hand (or the short hand); the hands are geared like a real clock.
- Jump to o'clock / quarter past / half past / quarter to, step ±5 min or ±1 hour.
- *Count by 5s* animates the counting round the minute ring (counts on to 12 for "to" times).
- *Past & to* shades the right (past) and left (to) halves and the distance travelled.
- *Ask the class* hides the answer until you tap Reveal. The speaker button reads the time aloud.
- Explanation card changes with the time shown (and explains the "next hour" rule for "to").

**Play** – four activities, each at any focus (O'clock, Half past, Quarter past, Quarter to, All quarters, 5 minutes, Mix it up):
1. *What's the time?* – multiple choice; wrong answers are the real misconceptions (wrong hour on "to" times, past/to swapped, hands swapped) with a matching hint.
2. *Set the clock* – drag the hands to a given time; hints after a wrong try, shows the answer after two.
3. *Memory match* – pair clocks with times in words.
4. *True or false?* – 60-second quick-fire.

Best stars are saved per activity and focus on the device.

**Worksheets** – A4 printables with answer keys:
Read the clock · Draw the hands · Match up · Three ways (clock / digital / words) · Read & draw · Paper clock (cut-out with split pin).
Options: focus, 6/9/12 clocks, what students write, how times are shown, minute numbers on clocks, number words or numerals, 1–4 different versions, answer key.
Every set has a **code** printed in the corner – type the same code back in to reprint the identical sheet and key.

Also: Poppins font (bundled), high-contrast mode, sound toggle, full screen, Australian wording ("quarter to", "half past").

## Put it on GitHub Pages

1. Create a new repository (e.g. `clockwise`) on GitHub.
2. Upload **everything in this folder**, keeping the `fonts/` and `icons/` folders.
3. Repository **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`. Save.
4. After a minute it's live at `https://YOUR-USERNAME.github.io/clockwise/`.

All paths are relative, so it works in any repo name or subfolder.

### Installing on devices
- Chrome / Edge: an **Install** button appears in the top bar (or use the browser menu → Install app).
- iPad / iPhone: Safari → Share → **Add to Home Screen**.
- Once opened online, it works offline.

### Updating later
Edit the files, upload them, then change `VERSION` in `sw.js` (e.g. `clockwise-v2`) so installed copies refresh their cache.

## Files
```
index.html            the whole app
manifest.webmanifest  PWA settings (name, colours, icons)
sw.js                 offline cache
fonts/                Poppins (SIL Open Font License – see OFL.txt)
icons/                app icons (192, 512, maskable, Apple touch, SVG favicon)
```

Printing tip: use **Print / save as PDF** in the Worksheets tab, A4, scale 100%, margins *None* or *Default*.
