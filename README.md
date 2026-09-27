# US Short Put Report

Interactive short-put screening report with OHLC candlestick charts (Black–Scholes panel included).

**Report date:** 2026-09-27 (prices / chains as of 2026-09-25 US close)

**Target expiry:** 2026-10-30 (33 DTE) — note: expires after FOMC 2026-10-27/28

## Preview

- [raw.githack](https://raw.githack.com/tracyng95/us-short-put/main/index.html)
- [jsDelivr](https://cdn.jsdelivr.net/gh/tracyng95/us-short-put@main/index.html)

`index.html` is a tiny loader: it fetches gzip+base64 chunks (`b0.txt`…`b7.txt`), decompresses with `DecompressionStream('gzip')`, and writes the full interactive report into the page.

## Picks

| Ticker | Rating | Strike | Approx Δ | Premium (Yahoo mid) |
|--------|--------|--------|----------|---------------------|
| XOM | A | 150 | -0.215 | $1.80 |
| NVDA | A | 210 | -0.215 | $3.03 |
| CRM | B | 215 | -0.216 | $3.78 |
| CVX | B | 190 | -0.198 | $1.98 |
| MRK | 條件式 | 140 | -0.275 | $2.83 |

## Integrity

Full report SHA-256: `3437ef94473f7df017b2884b319e07c4561f462fe757cf1abe6a7ffb28018f4e` (96967 bytes)

⚠️ 權利金與 Delta 須以即時期權鏈核實。
