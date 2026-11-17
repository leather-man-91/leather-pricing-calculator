# Leather Work Pricing Calculator

A single-page calculator for pricing handmade leather goods. Enter materials, time per step, labor rate, shop overhead and a target margin, and it recommends prices for:

- **Direct / in-shop** — cost ÷ (1 − margin), rounded
- **Etsy** — solved so you keep your margin after transaction, processing, listing and (optionally) Offsite Ads fees
- **Wholesale → MSRP** — separate wholesale margin, with the store's typical 2× retail

It also flags pricing problems (way over/under market, cost above market, wholesale MSRP undercutting your own price) and shows your effective hourly earnings at each price.

## Use it

Open `index.html` in any browser — no install, no build. Or enable GitHub Pages (Settings → Pages → deploy from `main`, root) to get a public link.

Saved items are stored in your browser's localStorage only.

## Notes

Etsy fee defaults (6.5% transaction, 3% + $0.25 processing, $0.20 listing, 15% Offsite Ads) are editable — check them against your own fee statements.
