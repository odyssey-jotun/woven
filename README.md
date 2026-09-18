# Woven

A sustainable blouse designed with women at Dorcas House in Little Rock, Arkansas.
Every design decision came from a survey of the women who will wear it.

**Live site:** https://odyssey-jotun.github.io/woven/

## What this is

A single-page website. There is no build step, no framework and no server: it is
one HTML file and a folder of images. Open `index.html` in any browser and it
works, online or offline.

```
index.html          the whole page: text, layout and styling
assets/             the images
  woven-logo.png            the Woven wordmark
  three-women.jpg           opening photograph
  hemp-blouse-concept.jpg   early concept photography
  colour-options.jpg        the three colourways
  sadie-janes-white.jpg     founder portrait
  sadie-janes-portrait.jpg  founder portrait
```

## Making changes

**Text.** Open `index.html` in any text editor, find the words you want to
change, change them, save. That is the whole process.

**Photographs.** Drop the new picture into `assets/` and change the matching
`src="assets/..."` line in `index.html` to its filename. Keep new photographs at
least 1000 pixels wide.

**Every image needs alt text**, the short description in the `alt="..."` part of
the line. It is what a blind visitor hears and what Google reads. Describe what
is actually in the picture.

## Publishing a change

The live site updates automatically from the `main` branch. Commit a change,
push it, and the new version is live within about a minute.

## Credits

Founded by Sadie Janes. Built in partnership with
[Dorcas House](https://urmissionlr.org/dorcas-house/), a program of Union Rescue
Mission, which serves roughly 50 women in residential recovery programs.

Survey conducted August 2026 with 19 Dorcas House residents. All published
figures are aggregate. No names, raw responses or identifying details appear on
the site.
