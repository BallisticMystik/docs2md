Title: On-chain Settlement

URL Source: https://api-docs.aevo.xyz/docs/on-chain-settlement

Markdown Content:
On-chain Settlement
===============
                                                                                                        

[Jump to Content](https://api-docs.aevo.xyz/docs/on-chain-settlement#content)

[![Image 3: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

* * *

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/docs/on-chain-settlement)[![Image 4: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

Technical Docs

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/docs/on-chain-settlement)

v1.0.3-beta

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

On-chain Settlement

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

On-chain Settlement
===================

[Suggest Edits](https://api-docs.aevo.xyz/edit/on-chain-settlement)

Users’ funds and positions remain on-chain at all time, within the Aevo smart contracts. This means that all flow of funds happen within smart contracts, including option settlements, funding payments, and exchanging of option premium.

Let us walk through an example. Alice and Bob are trading an ETH call with strike price $2500. Price of ETH-03062022-2500-C is $2 per contract, and Alice buys 100 contracts from Bob.

**Before the trade:**

|  | USDC | ETH-030622-2500-C |
| --- | --- | --- |
| Alice | 1000 | 0 |
| Bob | 1000 | 100 |

**After the trade:**

|  | USDC | ETH-030622-2500-C |
| --- | --- | --- |
| Alice | 800 | 100 |
| Bob | 1200 | 0 |

Updated about 2 years ago

* * *
