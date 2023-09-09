# Amphora Liquidation Script

## Steps
1. get `tokensToLiquidate()` as `liquidatable`
2. call `simulateLiquidateVault()` with `liquidatable`
3. if there are any tokens that can be liquidated, call `liquidateVault()`
with `liquidatable`.
