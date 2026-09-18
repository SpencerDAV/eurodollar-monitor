# Eurodollar System Monitor

**View it: https://spencerdav.github.io/eurodollar-monitor/**

A snapshot of a dashboard that reads the Treasury curve, TIPS break-evens,
dollar funding and collateral spreads and the offshore dollar together, as one
signal about money and growth. It opens with a one-paragraph summary of every
panel, then a regime classification that shows its working.

- **Data:** public series from [FRED](https://fred.stlouisfed.org/) (St. Louis
  Fed) and the [New York Fed](https://markets.newyorkfed.org/), daily history
  since September 2016. Two panels stand in for licensed data (swap spreads,
  cross-currency basis) and say so on the page.
- **A snapshot, not live:** the date is in the page subtitle. It is
  regenerated from a private project by `options-db site --pages eurodollar`.
- The page is one self-contained HTML file with no server behind it.

Not investment advice.
