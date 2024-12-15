Title: Standard Margin

URL Source: https://api-docs.aevo.xyz/docs/standard-margin

Markdown Content:
Standard Margin
===============
                                                                                                                                 

[Jump to Content](https://api-docs.aevo.xyz/docs/standard-margin#content)

[![Image 3: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

* * *

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/docs/standard-margin)[![Image 4: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

Technical Docs

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/docs/standard-margin)

v1.0.3-beta

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

Standard Margin

Search

Documentation
-------------

*   [Introduction](https://api-docs.aevo.xyz/docs/integrating-with-aevo-testnet)

Technical Architecture
----------------------

*   [Off-chain Orderbook and Risk Engine](https://api-docs.aevo.xyz/docs/off-chain-orderbook-and-risk-engine)
*   [On-chain Settlement](https://api-docs.aevo.xyz/docs/on-chain-settlement)
*   [Layer 2 Architecture](https://api-docs.aevo.xyz/docs/layer-2-architecture)

Contract Specifications
-----------------------

*   [Options Specifications](https://api-docs.aevo.xyz/docs/fees)
    *   [Fees](https://api-docs.aevo.xyz/docs/fees)
    *   [Margin Framework](https://api-docs.aevo.xyz/docs/margin-rules)
    *   [Standard Margin](https://api-docs.aevo.xyz/docs/standard-margin)
    *   [Portfolio Margin](https://docs.google.com/document/d/1Ho-6kpF0e03-i1ApWEtx5aTTujxDUgn17bUNhkRdT0o/edit?usp=sharing)
    *   [ETH Options](https://api-docs.aevo.xyz/docs/eth-options)

AEVO OTC
--------

*   [Introduction](https://api-docs.aevo.xyz/docs/introduction)
*   [Altcoin Volatility Market](https://api-docs.aevo.xyz/docs/altcoin-volatility-market)
*   [On-chain Margining System](https://api-docs.aevo.xyz/docs/on-chain-margining-system)

Standard Margin
===============

[Suggest Edits](https://api-docs.aevo.xyz/edit/standard-margin)

By default, all accounts use Standard Margin. Standard Margin evaluates the margin for every position on a user's portfolio individually, not holistically. For example, it does not take into consideration offsetting or correlated positions.

### 

Initial Margin

[](https://api-docs.aevo.xyz/docs/standard-margin#initial-margin)

Long call/put:  
`Quantity * Limit`

Short call:  
`Maximum (0.15 - OTM Amount/Spot, 0.1) * Spot + Mark Price of the Option`

Short put:  
`Maximum(Maximum (0.15 - OTM Amount/Spot, 0.1) * Spot + Mark Price of the Option, Maintenance Margin)`

### 

Maintenance Margin

[](https://api-docs.aevo.xyz/docs/standard-margin#maintenance-margin)

Long call/put:  
`None`

Short call:  
`0.1 * Spot + Mark Price of the Option`

Short put:  
`Maximum (0.1 * spot, 0.1 * Mark Price of the Option) + Mark Price of the Option`

Updated about 2 years ago

* * *
