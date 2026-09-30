# Legible: the live page

This branch is the site at <https://baw-dev.github.io/legible-typora-theme/>. The theme itself
is on [`main`](https://github.com/baw-dev/legible-typora-theme).

`index.html` is Typora's HTML export of `sample.md`, made with Legible Dark active. It was
then edited in four ways:
- it loads the fonts in `legible/`, a copy of `main`'s, instead of a font service;
- a switch changes between Legible and Legible Dark;
- the title is "Legible";
- its theme rules come from `main`'s `legible.css`.

To update it, export `sample.md` from Typora again and repeat those edits.
