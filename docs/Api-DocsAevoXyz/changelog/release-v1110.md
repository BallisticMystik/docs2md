Title: Release v1.1.10

URL Source: https://api-docs.aevo.xyz/changelog/release-v1110

Markdown Content:
Release v1.1.10
===============
                                                                                       

[Jump to Content](https://api-docs.aevo.xyz/changelog/release-v1110#content)

[![Image 3: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

* * *

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/changelog/release-v1110)[![Image 4: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

Changelog

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/changelog/release-v1110)

v1.0.3-beta

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

Search

[Back to All](https://api-docs.aevo.xyz/changelog)

Release v1.1.10
===============

10 months ago by Ken

This introduces breaking changes around `limit` and `start_time`.

Breaking Changes

[](https://api-docs.aevo.xyz/changelog/release-v1110#breaking-changes)
==========================================================================================

1\. Max limit set to 50. Default limit set to 10

[](https://api-docs.aevo.xyz/changelog/release-v1110#1-max-limit-set-to-50-default-limit-set-to-10)
-------------------------------------------------------------------------------------------------------------------------------------------------------

Previously, the max `limit` was set to 1000. This is adjusted to max `limit` of 50, and the default `limit` is set to 10 when `limit` is not passed in.

The affected endpoints are listed below:

*   /instrument/:instrument\_name/trade-history
*   /funding-history
*   /index-history
*   /index-histories
*   /mark-history
*   /settlement-history
*   /trade-history
*   /balance-history
*   /order-history
*   /order-history/stops
*   /transaction-history
*   /leaderboard
*   /referral-statistics
*   /block-history
*   /quote-history
*   /block-trade-history

2\. start\_time must be \>\=30 days

[](https://api-docs.aevo.xyz/changelog/release-v1110#2-start_time-must-be-30-days)
-------------------------------------------------------------------------------------------------------------------------

We enforce start\_time to be a nanosecond timestamp \>\=30 days. If `start_time` is not passed in, we default to `now - 30 days`.
