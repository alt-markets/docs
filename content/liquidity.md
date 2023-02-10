---
title: Liquidity
---

# Liquidity
Liquidity on Alt Markets is based on a novel mechanism and supports all decentralized markets on Alt Markets. Like Uniswap, the Alt Markets protocol uses an Automated Market Maker (AMM) function (modified to support bidirectional trades).
Alt Markets uses the XYK model to support long and short positions (compared to Uniswap, which currently supports only long positions).
Furthermore, Alt Markets uses a combination of virtual and real liquidity to improve the user-experience for traders.

## New Markets
When a user creates a new market, it is initialized with a static base liquidity ranging from hundreds to thousands of Dollars. This is dependent on the current system configuration.

## Continuous Liquidity
Once trades are executed, each trade adds a reserve percentage to liquidity. When a trade is closed, the temporary liquidity reserve is removed and returned to the owner.

The flexible liquidity approach is used to preserve volatility, independent of how much volume is traded.
A benefit of continuous liquidity is that markets won't stop trading if a large trader (e.g., the market creator) removes their share of liquidity.

A market without flexible reserve liquidity would be either too volatile if there is too little base liquidity or too stable if there is too much base liquidity.
The Alt Markets liquidity mechanism (combining base liquidity with dynamic reserve liquidities) presents a good trade-off between volatility and price stability to support large trades.
Virtual liquidity solves the cold start problem for early markets, and makes any newly launched market instantly tradable.

## Benefits
### Infinite Markets
Markets on Alt Markets cannot rug or close due to the base liquidity. Since every open trade contributes to the liquidity of a market, markets trade indefinitely and are not stopped when a significant position exits.

### Dynamic Liquidity
Liquidity for markets is dynamic and flexible. This allows markets to start small, with small positions (e.g., $100) making a noticeable price difference. When markets grow to a larger open interest (e.g., $10,000 or $100,000), markets remain liquid and provide good volatility/trade absorption.
