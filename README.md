# Bond Market Divergence Dashboard

A live GitHub Pages dashboard for tracking how global government bond markets are diverging across countries.

## What it does

This tool goes beyond showing raw bond yields.

It highlights:

- current 10-year government bond yields across countries
- recent yield changes
- deviation from the global average
- a live divergence score
- regional pressure differences
- auto-generated macro insights

## Why it matters

Bond markets do not always move in sync.

Some countries face tighter conditions, others are stabilizing, and others are already easing. This dashboard helps visualize that divergence in one place.

## Data source

The dashboard uses the BondStats global yield feed:

`https://botapi33.github.io/bondstats-global-yields/global_yields.json`

This file is built from publicly available official yield series.

## Files

- `index.html`
- `README.md`
- `.nojekyll`


- Some country series update daily, others monthly.
- The chart shows the top 18 countries by current yield for readability.
- The divergence score is a live internal dashboard indicator derived from current yield dispersion and recent move dispersion.
