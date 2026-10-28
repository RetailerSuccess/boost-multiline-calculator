# Boost Multi-Line Calculator

A single-page calculator that estimates the monthly cost of a Boost Mobile account across up to 10 phone lines, tablets, and watches.

## Features
- Mix and match plans per line: $25 Unlimited, $40 Global Connection, $50 Unlimited+, $60 Unlimited Premium
- Multi-line savings for $50/$60 lines (up to 10 lines)
- New-customer intro price: $10/mo for the first 6 months on up to 3 $25 Unlimited lines
- Connected devices: tablet ($20/mo) and watch ($10/mo) with an active phone line
- Average cost per phone line (phone service only)
- Responsive layout, keyboard and screen-reader friendly

## Run it
No build step or dependencies. Open `index.html` in any browser.

## Publish with GitHub Pages
1. Create a new repository and upload `index.html` and `README.md` to the root.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick `main` and `/ (root)`, then **Save**.
4. After a minute or two your calculator is live at `https://<your-username>.github.io/<repo-name>/`.

## Updating prices
All pricing lives at the top of the `<script>` block in `index.html`:
- `PLANS` - plan prices, intro price, and multi-line eligibility
- `DEVICE_PRICES` - tablet and watch prices
- `MULTILINE_DISCOUNTS` - total account savings by number of eligible lines
- `PROMO_LINE_LIMIT` - max lines that get the intro price

## Disclaimer
Estimate only. Prices include AutoPay and exclude taxes, fees, device financing, insurance, and activation fees. Check current offers with Boost Mobile; this project is not affiliated with Boost Mobile.
