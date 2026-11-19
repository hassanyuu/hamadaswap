# Hamada Swap

A lightweight Telegram Mini App / TON Connect interface for viewing indicative token conversion prices.

## Files
- `index.html` — application interface.
- `tonconnect-manifest.json` — TON Connect application manifest.
- `icon.png` — application icon.

## Important functionality note
The current code supports wallet connection and indicative price previews. It does **not** execute on-chain swaps. A DEX integration and transaction flow are still required for real swaps.

## Deploying
This is a static web app. It can be hosted with GitHub Pages or Cloudflare Pages.

The manifest currently points to `https://hamadaswap.pages.dev`. If you deploy to a different domain, update the `url` and `iconUrl` values in `tonconnect-manifest.json` to match the deployed site.

## Security
Do not add wallet seed phrases, private keys, API secrets, or other credentials to this repository.
