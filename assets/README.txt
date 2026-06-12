ASSETS — where your screenshots and PDFs go
============================================
Each project has its own folder. Per project, you'll add:

  cover.png        — hero screenshot (1600x900 recommended, <400KB)
  before.png       — before state
  after.png        — after state (match before's aspect ratio)
  case-study.pdf   — your long-form case study

Then in the project HTML:
  1. Delete the <div class="placeholder"> block
  2. Uncomment the <div class="frame"> block below it
  3. Fill the alt text — describe what's actually visible
  4. Update the og:image meta in <head> for nice link previews

Tip: compress screenshots with tinypng.com or `squoosh.app` before
uploading — keeps the site fast on GitHub Pages.
