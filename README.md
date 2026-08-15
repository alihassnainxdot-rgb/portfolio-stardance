# Ali — Personal Site

My personal site, built for the Hack Club Stardance "Personal Site" mission.

## What it is
A "helix" style index-of-work page: a numbered project index on the left,
and a stack of overlapping project cards on the right that you can click
through or auto-rotate. Covers VoxWeb Agency and other things I've built
or am building.

## Stack
Plain HTML + CSS + vanilla JS, no frameworks. One file, no build step.

## Design
- Cream/black/red editorial palette with a bold serif display face
  (Fraunces) for my name, IBM Plex Mono for labels and UI chrome, Inter
  for body text — loaded from Google Fonts.
- Each project card has its own generated pattern (checkerboard, bar
  chart, dot grid, concentric rings, halftone, terminal readout) tied to
  what that project actually is — e.g. the bar pattern on the Call Cost
  Calculator, a terminal readout on the Linux rice setup.
- The "Helix Controls" panel is functional: the speed slider and
  play/pause buttons actually control an auto-rotating highlight through
  the project cards.

## AI usage disclosure
I used Claude to help design and write the HTML/CSS for this site
(layout, color palette, and copy), based on details about myself and
VoxWeb that I provided. I reviewed and can explain every part of it.

## Running it locally
Just open `index.html` in a browser — no dependencies, no server needed.
