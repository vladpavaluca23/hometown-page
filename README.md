# Hometown Homepage – Cluj-Napoca

My solo project for the HTML & CSS module of the Scrimba Fullstack Path.
A small homepage about Cluj-Napoca, the city where I study.

**Live:** https://vladpavaluca23.github.io/hometown-page/

## Built with

HTML, CSS and Google Fonts (Poppins, Inter)

## Decisions I made

- The activity cards always have the same height. I didn't set a fixed
  height, flexbox stretches them to match the tallest card.
- Photos are cropped with `object-fit: cover` (cards) and
  `background-size: cover` (hero), so they don't get squashed.
- The page is desktop only for now. On small screens the cards get too
  narrow and the guide card doesn't fit. I'll fix this when I learn
  responsive design.

## What I learned

- Flexbox only aligns the direct children. To center the guide card I used
  `margin: 0 auto` on the card itself.
- `object-fit: cover` stops images from getting stretched. It's like
  `background-size: cover`, but for `<img>`.

## Credits

- Project brief: Scrimba
- Design: made in Figma with help from AI
- Photos: Tamas Pap, Val Vesa, Lucas Sandor and Marian Muraru on Unsplash
