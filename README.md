# My Childhood 🧸

A single-page personal memory/scrapbook website built with plain HTML and CSS, sharing reflections on favorite childhood hobbies and toys.

## Overview

This is a simple, story-style personal page organized into two sections — **Hobbies** and **Toys** — each broken into sub-topics with a short reflective paragraph and an accompanying image. It's a static, single-file page with a warm, journal-like visual theme (cream background, mustard highlights, and rust-colored accents).

## Content Sections

- **Hobbies**
  - Playing Netball
  - Dancing
- **Toys**
  - Barbie Dolls
  - Puzzles

Each sub-section includes one or two descriptive paragraphs (with emphasized/bolded words for feeling and tone) and a relevant image.

## Features

- Warm, scrapbook-inspired color palette (cream background, honey-yellow headers, rust-orange section markers)
- Distinct styling for `<em>` (red-brown italics) and `<b>` (green bold) text to highlight emotional emphasis
- Framed, rounded images centered beneath each paragraph
- Clean, readable typography using the Verdana/Geneva font stack
- Fully static — no scripts, frameworks, or build tools

## Tech Stack

- **HTML5**
- **Custom CSS** (embedded in a `<style>` block — no external stylesheets or frameworks)
- No JavaScript

## Getting Started

No installation or build tools required.

1. Download or clone the file.
2. Open `index.html` directly in any modern web browser.

An internet connection is needed for the images to load, since they're hotlinked from external sources rather than stored locally.

## File Structure

```
.
└── index.html   # Entire page: markup and embedded styles
```

## Known Issues / Notes

- All images are hotlinked from third-party sources (a retailer's product catalog, a cached Google thumbnail service, and a news site's CDN). These links could break or be removed at any time — consider downloading and self-hosting the images for a more permanent page.
- The page has no navigation, headings hierarchy beyond `<h1>`/`<h2>`, or metadata (e.g., author, date) — fine for a personal one-off page, but worth adding if this grows into a multi-page site.

## Possible Next Steps

- Self-host all images
- Add more sections/memories (e.g., School, Friends, Family)
- Add simple navigation if the page is split across multiple sections or pages
- Add alt-text refinements and basic accessibility improvements (e.g., skip links, semantic landmarks)

## License

No license specified. This is personal content — add a license only if you intend to share or reuse it more broadly.
