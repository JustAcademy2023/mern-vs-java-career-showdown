# MERN vs Java Career Showdown

A single page, no build step landing page comparing the MERN stack and full stack Java career paths for 2026, built for JustAcademy's Pune audience. The page is themed as a visual "duel" between the two stacks, with a split hero, contrasting card shapes for each track, a course grid, and a blog reading list, all fully linked to real JustAcademy pages.

## Live preview

Open `index.html` directly in a browser, or enable GitHub Pages on this repository (Settings, Pages, Deploy from branch, root) to get a shareable link.

## Design notes

The page deliberately gives each stack its own visual language instead of treating them as interchangeable list items.

- MERN is represented with soft emerald green, generously rounded corners, and a glowing radial gradient, mirroring how fast and flexible the ecosystem feels to build in.
- Java is represented with a burnt amber accent, sharper angular corners, and a firmer border, mirroring the structured, enterprise grade nature of the stack.
- Typography pairs Space Grotesk for headings with IBM Plex Sans for body copy and IBM Plex Mono for small labels, a combination chosen for a developer facing, code editor feel rather than a generic marketing look.
- The hero uses a single soft reveal animation on load. Everything else responds only to hover or focus, respecting `prefers-reduced-motion`.

## Structure

```
.
├── index.html   # complete page, styles included, no external JS framework
└── README.md
```

## Links included on the page

Course and bootcamp links:
- JavaScript Training in Pune
- Python Training in Pune
- MERN Stack Developer Bootcamp, Pune
- Full Stack Java Developer Bootcamp, Pune

Further reading links:
- MERN Stack vs Full Stack Java: Which Career Path is Better in 2026
- MERN Stack Developer Skills Companies Look For in 2026
- Full Stack Java Interview Questions for Freshers and Experienced Developers
- MERN Stack Developer Roadmap 2026

## Tech

Plain HTML and CSS, one small CSS keyframe animation, zero dependencies beyond two Google Fonts. Fully responsive down to small mobile widths, with visible keyboard focus states throughout.

## License

Content and copy belong to JustAcademy. Feel free to fork the layout for your own comparison style landing pages.
