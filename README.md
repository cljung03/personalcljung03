# Connor Jung — Personal Portfolio

A single-page personal site built as a Settlers of Catan board. Each hex tile opens
a section; the centre tile opens a photo journal of every image on the site.

**Live site:** https://YOURUSERNAME.github.io

## What's here

| File | Purpose |
|---|---|
| `index.html` | The entire site — HTML, CSS, JS, and hand-written SVG artwork in one file |
| `Connor_Jung_Resume.pdf` | Résumé, linked from the Connect tile |
| `*.jpg` | 49 photos, loaded automatically by filename |
| `_headers` | Security headers (Netlify / Cloudflare Pages only; GitHub Pages ignores this) |

## Features

- Animated box-open intro with a photo flurry that rotates through the library
- Hex-board navigation; clicking a tile expands its terrain full-screen before the section opens
- Photo journal slideshow with captions, thumbnails, and keyboard navigation
- Optional ambient audio with a mute control
- Responsive to mobile, and respects `prefers-reduced-motion`

## Adding or changing photos

Photos load by filename, so no code changes are needed. Drop a file into this
folder using the matching name and it appears:

- About: `about-1` … `about-5`
- Experience: `exp-accenture-1…4`, `exp-rsm-1…2`, `exp-gt-1…3`
- Travel: `travel-nus-1…7`, `travel-ntu-1…6`
- Hobbies: `hobby-boardgames-`, `hobby-basketball-`, `hobby-piano-`, `hobby-food-`, `hobby-hiking-`
- Community: `comm-akpsi-1…4`, `comm-absa-1…3`, `comm-aaiv-1…4`

Formats: `.jpg`, `.jpeg`, `.png`, `.webp`. Aim for ~1600px on the long edge and
under ~500KB. Strip EXIF before uploading, since phone photos carry GPS coordinates.

## Adding background music

Save a licensed track as `ambient.mp3` in this folder and the player uses it
instead of the built-in generative score. Music never autoplays; visitors turn it
on with the button in the top right.
