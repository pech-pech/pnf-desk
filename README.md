# DSE - Point and Figure Desk

Learn to read Point and Figure charts for Dhaka Stock Exchange stocks, in two designs of the same site:

- **Site A**, light, newspaper style: `/a/`
- **Site B**, dark, field guide: `/b/`

Every stock in the archive has its own chart page. The sites are static pages that load their data from `data/`
(`data/index.json` for the Charts list, `data/s/<TICKER>.json` for one stock). No tracking, no build step to view.
The pages load fonts from Google Fonts.

**Educational only, not investment advice.** A Point and Figure chart describes what price has done; it does not predict what comes next.

**Data:** end-of-day Dhaka Stock Exchange prices via [AmarStock](https://www.amarstock.com). Charts, signals, patterns and Bullish Percent figures are derived from those prices.

Bengali text is a draft and has not yet been reviewed by a native editor.
