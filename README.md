# Red Bull: Wiiings concept store

A single-file scroll-story site (HTML/CSS/JS, no build step) by Nexlyr Solutions.

## Structure
- `index.html`: the whole site (styles + scripts inline)
- `assets/can.webp`, `f1.webp`, `wing.webp`: illustrations (swap for your own renders, same filenames)
- `assets/nexlyr-logo.svg`: official Nexlyr mark for the credit strip
- `assets/fonts/`: self-hosted Jost + Inter (woff2)

## Edit prices
Open `index.html` and find `PACKS` near the top of the `<script>`. Prices are PKR.

## Deploy
Push to GitHub and import in Vercel (static, no settings needed).
Open through a server, not by double-clicking the file: fonts are blocked on `file://`.
