# About
This repository holds an open-source trading strategy maintained by the [Superalgos Community](https://t.me/superalgoscommunity). The strategy conforms to the Superalgos Protocol, therefore, it may function as a fully automated trading system within the [Superalgos Desktop App](https://superalgos.org/tools-superalgos-desktop-app.shtml). 

People not interested in trading automation may still obtain the strategy's rules (situations, conditions, and formulas) from the app's Designer interface, and use the set of rules as they see fit. The app may also be used for testing ideas, for backtesting and paper-trading (to obtain live signals!).

# Weak-hands Buster - BTC - 1hr

## Specifications

JSON file compatible with the Superalgos Desktop App v.0.0.2

### Current Performance in Backtests (Poloniex)

| Details | 2019 | 2018 |
| :--- | :---: | :---: |
| Trades: | 8 | 19 |
| Hits: | 7 | 12 |
| Fails: | 1 | 7 |
| ROI*: | 63% | 549% |

[ * ] The strategy starts with an *initial capital* and reinvests accumulated profits in every trade. ROI is calculated over the *initial capital*.

### Market

USDT-BTC, with **BTC as the base asset**.

### Strategy Goal

Accumulate bitcoin during bear markets and / or consolidation periods, with a conservative approach to minimize risk.

### Approach

We split the goal in two:

1. We focus on potentially big market moves, therefore, the strategy is optimized for major trend reversals resulting in long bear markets. Significant consolidations during bull markets are targetted as well.

2. We take the clearest and most promising opportunities only. We pass on everything else.

### Trading idea

Identify breakouts of the Bollinger Bands (price going below the lower deviation band). Use %Bandwidth indicator to assess momentum and Bollinger Bands moving average to optimize the *take position event*, and filter out late entries.

# Disclaimer

> THIS IS NOT FINANCIAL ADVICE. ALTHOUGH THE STRATEGIES IN THIS REPOSITORY MAY BE FULLY FUNCTIONAL, WE DO NOT MAKE ANY EXPRESS OR IMPLIED RECOMMENDATION AS OF HOW YOU SHOULD USE THEM. WE SHARE STRATEGIES FOR EDUCATIONAL PURPOSES ONLY. TRADE AT YOUR OWN RISK.
