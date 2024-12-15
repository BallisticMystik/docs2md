Title: Release v1.1.2

URL Source: https://api-docs.aevo.xyz/changelog/release-v112

Markdown Content:
Release v1.1.2
===============
                                                                                                       

[Jump to Content](https://api-docs.aevo.xyz/changelog/release-v112#content)

[![Image 3: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

* * *

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/changelog/release-v112)[![Image 4: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

Changelog

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/changelog/release-v112)

v1.0.3-beta

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

Search

[Back to All](https://api-docs.aevo.xyz/changelog)

Release v1.1.2
==============

over 1 year ago by Ken

RELEASE DATE: 25-04-2023

[](https://api-docs.aevo.xyz/changelog/release-v112#release-date-25-04-2023)
--------------------------------------------------------------------------------------------------------

Bug fixes for websockets and changes in fills subscription.

* * *

Websocket changelog

[](https://api-docs.aevo.xyz/changelog/release-v112#websocket-changelog)
-----------------------------------------------------------------------------------------------

**SUBSCRIBE fills**

*   Fills that match multiple orders now emit multiple messages. For example, if a taker order matches 2 maker orders, 2 fill messages will be received by the taker.
*   Each of these fill messages will have a unique trade ID.

**SUBSCRIBE orders**

*   Fixed issue where makers subscribing to `orders` do not receive messages
*   Added the `system_type` field.

**SUBSCRIBE positions**

*   Fixed issue where `amount` was returning signed floats.
*   Added the `system_type` field.
