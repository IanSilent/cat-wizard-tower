# Cat Wizard Tower (Башня кота-волшебника)

**Play in the browser: https://iansilent.github.io/cat-wizard-tower/**

A cozy web prototype: a cat wizard lives in a mage tower and runs a small library of magic folios.

## The loop

1. A raven brings an order.
2. Take the folio of the right school of magic.
3. Trace the magic seal through its dots.
4. Put the folio back on the shelf. Neighbours of the same school give more dust.
5. Three orders make an evening. Dust buys artifacts and new tower levels; each level adds a shelf row and a school.

## Design pillars

- A simple, pleasant routine: drawing seals, writing them into folios, rearranging shelves.
- A calm, cute, cozy look with a "cozy Middle-earth" mood.
- Visible progress: the library grows and artifacts appear.
- A little madness.

## Tech

One `index.html`: canvas and vanilla JavaScript, no build step, no dependencies. Progress is saved in the browser's `localStorage`. The UI is in Russian.
