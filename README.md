# Page Rebuild

A fixed-price rebuild of the one page your customers land on. **$340, live in 48 hours.** Payment through PayPal; the scope is written down before anything is paid.

- **Live page:** <https://anojndr.github.io/page-rebuild/>
- **Email:** <anojndr@gmail.com>
- **PayPal:** <https://www.paypal.com/paypalme/KiraYoshikage974>
- **Start:** [open an issue](https://github.com/anojndr/page-rebuild/issues/new?title=Page%20inspection%20request&body=Site%20URL%3A%20%0AWhat%20the%20page%20is%20for%3A%20) or email the URL.

## What you get

A measured readout of the page — mobile layout, assets, headings, metadata, response time, stale content — then a hand-written HTML/CSS rebuild of that one page. Real mobile layout, click-to-call, HTTPS, title/description, LocalBusiness markup, and a staging link within 24 hours. Two rounds of changes inside the agreed scope.

The sample readout on the live page was measured on [`demo/broken.html`](demo/broken.html), a page built to fail the checks. It is labeled as a sample; it is not a customer result.

## The two prices

| Scope | Price | Turnaround |
|---|---:|---|
| Full rebuild of the landing page | $340 | 48 hours |
| Patch list for a working layout | $170 | 24 hours |

50% to start and 50% on approval for the rebuild; the fix list is paid on delivery. Extra pages are $100 each.

## Run it locally

No build step. Open `index.html` directly, or serve the directory:

```sh
python3 -m http.server 8000
```

Then open <http://127.0.0.1:8000/>.

## Deploy

This repo is served by GitHub Pages from `main` at the repository root. The `.nojekyll` file keeps the static files as-is.

## Contact

Email <anojndr@gmail.com> or open an issue. No calls, no list, no sequence.
