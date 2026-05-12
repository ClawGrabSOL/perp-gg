# perp.gg

Permissionless leveraged perp market launchpad.

Launch a market on any token — there's no buying supply, no AMM curve. Just longs and shorts.

## Run locally

It's a single static file. Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
# or
python3 -m http.server 8000
```

## Stack

- Single-file HTML/CSS/JS (no build step)
- Solana wallet connect: Phantom, Solflare, Backpack
- Markets persist to `localStorage` (`perp.gg.markets.v1`)
- Deploy step is currently simulated — on-chain wiring TBD

## Roadmap

- [ ] Real Solana program / on-chain market registry
- [ ] perps.gg backend integration
- [ ] Trade modal (open/close long/short positions on a market)
- [ ] Indexer + price feed
- [ ] Mainnet
