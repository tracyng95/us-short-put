# US Short Put Report

Interactive short-put screening report with OHLC candlestick charts (Black–Scholes panel included).

**Report date:** 2026-10-11 (prices / chains as of 2026-10-09 US close)

**Target expiry:** 2026-11-13 (33 DTE) — holds through FOMC 2026-10-27/28; next FOMC 2026-12-08/09

**Alt expiry (pre-FOMC):** 2026-10-23 (12 DTE)

## Preview

- [raw.githack](https://raw.githack.com/tracyng95/us-short-put/main/index.html)
- [jsDelivr](https://cdn.jsdelivr.net/gh/tracyng95/us-short-put@main/index.html)

`index.html` is a tiny loader: it fetches gzip+base64 chunks (`b0.txt`…), decompresses with `DecompressionStream('gzip')`, and writes the full interactive report into the page.

## Picks

| Ticker | Rating | Strike | Approx Δ | Premium (Yahoo mid) |
|--------|--------|--------|----------|---------------------|
| CRM | A | 210 | -0.207 | $3.35 |
| AMZN | A | 240 | -0.198 | $3.83 |
| NVDA | B | 215 | -0.223 | $3.13 |
| JNJ | B | 245 | -0.196 | $2.36 |
| GOOGL | 高價例外 | 325 | -0.209 | $4.88 |

## Integrity

Full report SHA-256: `bdad17c1fa06b479d76e13e234315ba0a432154d9ae991088d03146bb8638858` (102038 bytes)

⚠️ 權利金與 Delta 須以即時期權鏈核實。
