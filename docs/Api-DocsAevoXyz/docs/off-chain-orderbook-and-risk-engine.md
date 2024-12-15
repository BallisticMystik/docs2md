Title: Off-chain Orderbook and Risk Engine

URL Source: https://api-docs.aevo.xyz/docs/off-chain-orderbook-and-risk-engine

Markdown Content:
Off-chain Orderbook and Risk Engine
===============
                                                                                                       

[Jump to Content](https://api-docs.aevo.xyz/docs/off-chain-orderbook-and-risk-engine#content)

[![Image 5: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

* * *

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/docs/off-chain-orderbook-and-risk-engine)[![Image 6: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

Technical Docs

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/docs/off-chain-orderbook-and-risk-engine)

v1.0.3-beta

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

Off-chain Orderbook and Risk Engine

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

Off-chain Orderbook and Risk Engine
===================================

[Suggest Edits](https://api-docs.aevo.xyz/edit/off-chain-orderbook-and-risk-engine)

Aevo operates an off-chain order-book where maker and taker orders are posted and matched. Once a maker and taker order gets matched, only then do they get posted on Aevo’s smart contracts, which are deployed on the L2 roll-up.

Before an order is created and posted to the order-book, it is evaluated through the off-chain risk engine. The risk engine checks margin requirements for that account (either Standard Margin or Portfolio Margin) to determine if it has enough margin to create that order.

![Image 7: 3116](https://files.readme.io/f3d9414-Screenshot_2022-12-13_at_8.35.37_PM.png)

Updated about 2 years ago

* * *
