# Options & Macro Dashboards

**View it: https://spencerdav.github.io/eurodollar-monitor/**

A snapshot of a private research project that reads the options market and the
dollar funding system side by side.

- **Options DB** (`options.html`): intraday option-chain snapshots for SPY, RUT,
  NVDA, MSTR, GLD and TLT, polled every 15–120 minutes by expiry. Every metric
  (30-day ATM IV, RR25, BF25, RR10) is read off one SVI smile per chain, fitted
  to bid/ask mids against its put-call parity forward. Click a ticker for the 3D
  implied-volatility surface for each session of the week (pick the day at the top of the viewer): IV, skew,
  put − call and the greeks, a timeline through the day, pinned contracts, and
  the underlying's price history.
- **Eurodollar System Monitor** (`eurodollar.html`): the Treasury curve, TIPS
  break-evens, dollar funding and collateral spreads and the offshore dollar,
  read together as one regime call that shows its working.
- **Rates & Credit** (`rates.html`): forward rates bootstrapped from the
  Treasury curve, the policy path the bill curve prices, and credit spreads by
  rating.

**Data:** option chains and prices from Yahoo Finance; macro series from
[FRED](https://fred.stlouisfed.org/) (St. Louis Fed) and the
[New York Fed](https://markets.newyorkfed.org/). Panels that stand in for
licensed data (swap spreads, cross-currency basis, OIS) are labelled as proxies
on the page.

**A snapshot, not live:** the time each page was written is in its subtitle.
Every page is a self-contained HTML file with no server behind it; the 3D
viewer needs WebGL.

Not investment advice.
