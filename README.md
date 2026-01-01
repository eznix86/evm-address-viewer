# EVM Address Viewer

Simple webpage to view your ten Ethereum addresses from any valid 12- or 24-word BIP39 mnemonic. Everything runs locally in the browser.

Live example: [eznix86.github.io/evm-address-viewer](https://eznix86.github.io/evm-address-viewer).

## What's Inside
- Uses Tailwind CSS, Alpine.js, and `ethers.js` over CDNs.
- Derivation logic
  – standard `m/44'/60'/0'/0/i` path for indexes `0-9` plus copy-to-clipboard and Blockscan links for each address.

That's the whole project: one static HTML file you can drop anywhere to inspect mnemonics safely.

You can clone it and make it your own! (I use it to see what leftover pennies i have in sub accounts)
