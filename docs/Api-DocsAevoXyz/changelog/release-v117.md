Title: Release v1.1.7

URL Source: https://api-docs.aevo.xyz/changelog/release-v117

Markdown Content:
TO BE RELEASED: 29-07-2023

[](https://api-docs.aevo.xyz/changelog/release-v117#to-be-released-29-07-2023)
------------------------------------------------------------------------------------------------------------

* * *

Introduces the `timestamp` field in order signing to prevent replay attacks and guarantee order uniqueness. The `timestamp` field is in UNIX seconds format.

Order Signing Changelog

[](https://api-docs.aevo.xyz/changelog/release-v117#order-signing-changelog)
-------------------------------------------------------------------------------------------------------

* * *

Order is optionally signed with the `timestamp` field included.

REST API Changelog

[](https://api-docs.aevo.xyz/changelog/release-v117#rest-api-changelog)
---------------------------------------------------------------------------------------------

* * *

`POST /order`

*   added `timestamp` as an optional parameter

`POST /orders/{order_id}`

*   added `timestamp` as an optional parameter

Websockets Changelog

[](https://api-docs.aevo.xyz/changelog/release-v117#websockets-changelog)
-------------------------------------------------------------------------------------------------

* * *

`PUBLISH Create Order`

*   added `timestamp` as an optional parameter

`PUBLISH Edit Order`

*   added `timestamp` as an optional parameter
