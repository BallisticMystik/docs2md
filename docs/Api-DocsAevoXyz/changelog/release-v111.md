Title: Release v1.1.1

URL Source: https://api-docs.aevo.xyz/changelog/release-v111

Markdown Content:
Added additional information for orders.

* * *

*   Improved websocket stability.

**/trade-history**

*   `trade_id` field now shows a unique ID instead of order ID. Length of trade\_id is fixed at 44 characters. Eg. `DwmDn5XnEyiqx5AB5CM4W8bgD137ASX4Lz1XWBWDYHn8`
*   Added field order\_id to show the corresponding order for the trade
*   If you are on the taker side of the trade, your trade will no longer be aggregated. Eg. if your order matches with 3 open orders on the book, your trade history will show 3 new trades, instead of a single aggregated trade.
*   Changed `amount` for `settlement` to be an unsigned float string.

**/instrument/{instrument\_name}**

*   Added the `total_volume` field, which is the total volume in USDC traded for the instrument.

**SUBSCRIBE orderbook**

*   Order IV is added to the array.
*   An order on the orderbook would look like this: `[["1", "10", "0.85"]]`.

**SUBSCRIBE fills**

*   Added `trade_id` field to identify the trade.
*   Fixed the `fee` field to be a float string, instead of an integer.

**SUBSCRIBE orders**

*   Added `timestamp` field for create and cancel orders.
*   Added the `system_type` field, which is either `API` or `WEB`.
*   Added the `expiry`, `strike` and `option_type` field
