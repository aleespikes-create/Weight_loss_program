# SANO Med Spa — "It's Your Turn" GLP-1 Landing Page

Single-file landing page for the $149 GLP-1 introductory offer.
Built to convert paid traffic into booked consultations.

**Live:** https://USERNAME.github.io/sano-glp1-landing/

## Before going live

1. **Calendar** — open `index.html`, find `<div id="calendar-embed">` and replace it
   with your Calendly / GoHighLevel / Cal.com embed. Paste-ready snippets are in the
   HTML comment directly above that block.
2. **Tracking** — paste the Meta Pixel and GA/GTM snippets into the marked block in `<head>`.
   Click-tracking hooks for every CTA are already wired at the bottom of the script.
3. **Results photos** — captions currently read "Actual SANO patient". Add the treatment
   and timeframe to each for a meaningful lift in credibility.
4. **Confirm** — written photo releases on file, and that "medically supervised"
   matches how the program is actually staffed.

## Notes

- Everything is inline: CSS, JS, and the three before/after photos (base64). No build step,
  no dependencies, no asset folder. Total page weight ~255KB.
- Fonts load from Google Fonts (Cormorant Garamond, Mulish, Bodoni Moda, Great Vibes)
  as the closest available substitutes for The Seasons, Avenir Next LT Pro, Didot, and
  Merona Island Bold. Mac visitors fall back to real Avenir Next and Didot.
- Brand colors: `#7D7F70` primary, `#E6DFD3` secondary.
