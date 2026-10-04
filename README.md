# US Short Put Report

Interactive short-put screening report with OHLC candlestick charts (Black–Scholes panel included).

**Report date:** 2026-10-04 (prices / chains as of 2026-10-02 US close)

**Target expiry:** 2026-11-06 (33 DTE) — note: holds through FOMC 2026-10-27/28; next FOMC 2026-12-08/09

**Alt expiry:** 2026-10-30 (26 DTE)

## Preview

- [raw.githack](https://raw.githack.com/tracyng95/us-short-put/main/index.html)
- [jsDelivr](https://cdn.jsdelivr.net/gh/tracyng95/us-short-put@main/index.html)

`index.html` is a tiny loader: it fetches gzip+base64 chunks (`b0.txt`…`b8.txt`), decompresses with `DecompressionStream('gzip')`, and writes the full interactive report into the page.

## Picks

| Ticker | Rating | Strike | Approx Δ | Premium (Yahoo mid) |
|--------|--------|--------|----------|---------------------|
| CRM | A | 215 | -0.216 | $3.83 |
| XOM | A | 155 | -0.258 | $2.35 |
| AMZN | B | 230 | -0.200 | $3.65 |
| QCOM | B | 165 | -0.209 | $3.93 |
| CVX | B | 195 | -0.243 | $2.57 |

## Integrity

Full report SHA-256: `7cb94f9575c19bb6f793e4e9348619225fa750245dc2490650f6fd1007094c52` (104886 bytes)

⚠️ 權利金與 Delta 須以即時期權鏈核實。
