# EVM Address Viewer

Single-page tool for deriving the first ten Ethereum addresses from any valid 12- or 24-word BIP39 mnemonic. Everything runs locally in the browser, making it easy to publish as a static site on GitHub Pages or serve straight from the filesystem. Live copy: [eznix86.github.io/evm-address-viewer](https://eznix86.github.io/evm-address-viewer).

## What's Inside
- `index.html` – complete UI and logic with Tailwind CSS, Alpine.js, and `ethers.js` over CDNs.
- Derivation logic – standard `m/44'/60'/0'/0/i` path for indexes `0-9` plus copy-to-clipboard and Blockscan links for each address.
- Visual style – neon glassmorphic layout with animated panels, badges, and CTA button micro-interactions.

That's the whole project: one static HTML file you can drop anywhere to inspect mnemonics safely (prefer throwaway phrases; nothing is ever uploaded).
