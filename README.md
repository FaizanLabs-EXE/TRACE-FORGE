# TraceForge OSINT Dashboard

A static, installable, local-first PWA for structured public-source research.

## Run

Do not open from `file://` because PWA/service workers require HTTP(S).

- Local: `python3 -m http.server 8080` then open `http://localhost:8080`
- GitHub Pages: upload all files to the repository root and enable Pages for the branch.
- Android: open the hosted HTTPS site in Chrome and choose **Install app** or use the in-app Install button when available.

## Included

- Local case board, activity trail, evidence records, JSON import/export
- Username pivots, DNS/RDAP lookup, indicator extraction, SHA-256 hashing
- Responsible single-page metadata/link crawler, subject to CORS and site permissions
- OpenRouter model catalog and sequential multi-model analysis
- Offline application shell and installable manifest
- Local consent-based coarse image comparison. This does not identify people.

## OpenRouter key safety

Session storage is the default. Remembering the key writes it to this browser's local storage. A public frontend cannot fully protect a pasted API key. Use a restricted, disposable key with a spending limit and rotate it if exposed.

## Scope and ethics

Use only lawful, public, authorized sources. Do not bypass authentication, robots controls, paywalls, rate limits or technical restrictions. Do not use the image tool for surveillance, identification, sensitive-trait inference, or consequential decisions.

## Notes

A browser-only crawler cannot read websites that disallow cross-origin requests. This is an intentional security boundary, not an error. For broader authorized collection, add a controlled backend proxy that enforces allowlists, rate limits and robots policies.
