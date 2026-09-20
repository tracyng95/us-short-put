# US Short Put Report

Interactive short-put screening report with OHLC candlestick charts (Black–Scholes panel included).

**Report date:** 2026-09-20

## Preview (use these)

**Cache-bust / preferred (commit-pinned):**
- [raw.githack @63c5c97](https://raw.githack.com/tracyng95/us-short-put/63c5c9795683be56208f1f48a0abf092d9ce1ee2/index.html)
- [jsDelivr @63c5c97](https://cdn.jsdelivr.net/gh/tracyng95/us-short-put@63c5c9795683be56208f1f48a0abf092d9ce1ee2/index.html)

**Branch tip (may lag CDN):**
- [raw.githack main](https://raw.githack.com/tracyng95/us-short-put/main/index.html)
- [jsDelivr main](https://cdn.jsdelivr.net/gh/tracyng95/us-short-put@main/index.html)

`index.html` is a tiny loader: it fetches gzip+base64 chunks (`b0.txt`…`b8.txt`), decompresses with `DecompressionStream('gzip')`, and writes the full interactive report (canvas OHLC charts) into the page.

## Integrity

Full report SHA-256: `5e3d21defd394c1933ae89c4cc32372c4019b8604274c0c161d100dfafebba0a` (104111 bytes)

Loader restore commit: `d10c7e67b7114ba9ebc69d129e84bde4bbd44b08`  
HEAD (cleanup): `63c5c9795683be56208f1f48a0abf092d9ce1ee2`
