# daytrade

SPY 15-min entry/exit signal model.

## What it does
- 15-min simulated SPY price chart with EMA 7/21/50/200
- TSI (True Strength Index) with signal line
- RSI with configurable midline
- Entry/exit signal detection with adjustable parameters via sliders

## Entry logic (all required)
- EMA 7 above EMA 21
- Price above EMA 21
- TSI crosses above signal line
- RSI at or above midline – 5

## Exit logic (any one fires)
- TSI crosses below signal line
- Price closes below EMA 21
- RSI drops below midline + 5
- EMA 7 crosses below EMA 21

## Usage
Open `index.html` in a browser. No build step needed.

> Note: rename the GitHub repo at https://github.com/sspam1189-stack/Pok-mon → Settings → rename to `daytrade` to match.
