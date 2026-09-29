# Megaminx 4LLL Trainer

A free web-based trainer for learning the **4 Look Last Layer (4LLL)** algorithm set for the Megaminx — built because no equivalent trainer existed for this puzzle, unlike the many available for the 3x3 Rubik's Cube.

**[Try it live →](https://megaminx-4lll.vercel.app)**

## Why this exists

Trainers for common last-layer algorithm sets (OLL/PLL, etc.) are widely available for the 3x3. They organize algorithms clearly and let you drill each case as much as you want. Nothing like that existed for the Megaminx's 4LLL set, so this project fills that gap.

## Features

- **Full 4LLL algorithm set** organized and ready to drill, case by case
- **Learn Status mode** — track which algorithms you've mastered vs. which still need practice
- **Group Moves mode** — chunks algorithms into more memorable move groupings, making them easier to internalize
- Runs entirely in the browser, no install required

## Tech Stack

- HTML / CSS / JavaScript (no frameworks or build step)
- Deployed on [Vercel](https://vercel.com)

## Getting Started (local development)

This is a static single-page site, so there's no build process:

```bash
git clone https://github.com/justinlin3451/megaminx-4lll.git
cd megaminx-4lll
```

Then just open `index.html` in your browser, or serve it locally:

```bash
npx serve .
```

## Roadmap / Ideas

- [ ] Add less predictable scramble generation for each case
- [ ] Mobile-friendly layout improvements

## Contributing

This started as a personal tool to solve my own learning problem, but if you're also learning 4LLL and have ideas or find bugs, feel free to open an issue or PR.
