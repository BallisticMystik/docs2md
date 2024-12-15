Title: Release v1.1.5

URL Source: https://api-docs.aevo.xyz/changelog/release-v115

Markdown Content:
**Summary**

Added support for BTC options in portfolio APIs and miscellaneous bug fixes. Added new order types.

* * *

**GET /portfolio**

*   `greeks` returns an array of greek objects instead of being a single `greeks` object.
*   `greeks` now contains `asset`, which is either `"ETH"` or `"BTC"`.

**GET /order-history**

*   The `start_time` and `end_time` now filters based on order creation time, not last updated time
*   Added a new field `updated_timestamp`: the timestamp when the order status was last updated
*   Orders are now sorted based on `created_timestamp`: the order creation time

**POST /orders**

*   Added a `reduce_only` flag for creating reduce-only orders
*   Added a `stop` field, which is either `STOP_LOSS` or `TAKE_PROFIT`
*   Added a `trigger` field used to indicate stop trigger price.

* * *

**PUBLISH Create Order**

*   Added a `reduce_only` flag for creating reduce-only orders
*   Added a `stop` field, which is either `STOP_LOSS` or `TAKE_PROFIT`
*   Added a `trigger` field used to indicate stop trigger price.
