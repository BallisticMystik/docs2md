Title: Release v1.0.1

URL Source: https://api-docs.aevo.xyz/changelog/release-v101

Markdown Content:
* * *

Stable version for REST API and Websockets. Includes changes to the request and response fields across endpoints.

* * *

`GET /expiries`

*   Returns an array of UNIX timestamps in **nanos** in string format.

`GET /index`

*   Reformatted timestamp to UNIX timestamp in **nanos** in string format.

`GET /index-history`

*   Reformatted timestamp to UNIX timestamp in **nanos** in string format.

`GET /markets`

*   Renamed `type` to `instrument_type`
*   Renamed `underlying` to `underlying_asset`
*   Renamed `size_step` to `amount_step`
*   Reformatted `instrument_id` to to string format
*   Reformatted timestamp to UNIX timestamp in **nanos** in string format.

`GET /statistics`

*   Renamed `price` to `index_price`

`GET /orderbook`

*   Renamed argument `symbol` to `instrument_name`
*   Added `instrument_id` in the response
*   Reformatted timestamp to UNIX timestamp in **nanos** in string format.

`GET /instrument/{instrument_name}/trade-history`

*   Removed `account` from the response
*   Removed `agg_order_id` from the response
*   Removed `total_matched_amount` from the response
*   Removed `event_type` from the response
*   Removed `option_type` from the response
*   Removed `expiry` from the response
*   Removed `strike` from the response
*   Removed `order_type` from the response
*   Removed `trade_status` from the response
*   Removed `fees` from the response
*   Renamed `avg_price` to `price`
*   Added `instrument_id` in the response
*   Reformatted timestamp to UNIX timestamp in **nanos** in string format.

`POST /register`

*   Added `success` in the response
*   Renamed `signingKeys` to `signing_key`
*   Renamed `registered_at` to `created_timestamp`
*   Reformatted timestamp to UNIX timestamp in **nanos** in string format.

`DELETE /api-key`

*   Renamed `status` to `success`
*   Reformatted timestamp to UNIX timestamp in **nanos** in string format.

`POST /api-key`

*   Reformatted timestamp to UNIX timestamp in **nanos** in string format.

`DELETE /signing-key`

*   Renamed `status` to `success`
*   Reformatted timestamp to UNIX timestamp in **nanos** in string format.

`GET /account`

*   Renamed `account_id` to `account`
*   Renamed `registered_at` to `created_timestamp`
*   Renamed `average_entry_price` to `avg_entry_price`
*   Renamed `fee` to `fees`
*   Removed `last_updated_timestamp` from the response
*   Reformatted `account_type` to string

`POST /withdraw`

*   Renamed `status` to `success`

`GET /orders`

*   Renamed `id` to `order_id`
*   Renamed `account_id` to `account`
*   Renamed `size` to `amount`
*   Renamed `type` to `option_type`
*   Added `order_status` in the response
*   Changed allowed values for `side` to `buy` and `sell` only
*   Reformatted `instrument_id` to to string format
*   Reformatted expiry to UNIX timestamp in **nanos** in string format.
*   Reformatted timestamp to UNIX timestamp in **nanos** in string format.

`POST /orders`

*   Renamed `fill_amount` to `filled`

`POST /orders/{order_id}`

*   Renamed `fill_amount` to `filled`

`DELETE /orders-all`

*   Renamed `status` to `success`

`GET /order-history`

*   Renamed `id` to `order_id`
*   Renamed `account_id` to `account`
*   Renamed `direction` to `side`
*   Renamed `size` to `amount`
*   Renamed `type` to `option_type`
*   Renamed `status` to `order_status`
*   Removed `event_type` from the response
*   Reformatted timestamp to UNIX timestamp in **nanos** in string format.

`GET /trade-history`

*   Renamed `id` to `trade_id`
*   Renamed `type` to `trade_type`
*   Renamed `account_id` to `account`
*   Renamed `direction` to `side`
*   Renamed `size` to `amount`
*   Renamed `status` to `order_status`
*   Renamed `aggressing_order_id` to `agg_order_id`
*   Reformatted timestamp to UNIX timestamp in **nanos** in string format.

`GET /transaction-history`

*   Renamed `id` to `account`
*   Reformatted timestamp to UNIX timestamp in **nanos** in string format.

`GET /mmp`

*   Renamed `limit` to `amount_limit`
*   Reformatted `interval` to string in the response
*   Reformatted `frozen` to string in the response

* * *

`PUBLISH Ping`

*   Simplified response to include only `success` and `timestamp`

`SUBSCRIBE Orderbook`

*   Renamed `instrument` to `instrument_name`
*   Renamed `timestamp` to `last_updated`

`SUBSCRIBE Trades`

*   Newly added

`PUBLISH Create Order`

*   Renamed argument `isBuy` to `is_buy`
*   Renamed argument `limitPrice` to `limit_price`
*   Renamed `fill_amount` to `filled` in the response

`PUBLISH Cancel Order`

*   Renamed argument `id` to `order_id`

`PUBLISH Edit Order`

*   Renamed argument `id` to `order_id`
*   Renamed argument `isBuy` to `is_buy`
*   Renamed argument `limitPrice` to `limit_price`

`SUBSCRIBE Ticker`

*   Renamed `instrument` to `instrument_name`
*   Renamed `size` to `amount`

`SUBSCRIBE Order`

*   Renamed `maker` to `account`
*   Renamed `instrument` to `instrument_name`
*   Renamed `direction` to `side`
*   Renamed `limit_price` to `price`
*   Renamed `fill_amount` to `filled`
*   Renamed `timestamp` to `created_timestamp`
*   Removed `avg_price`

`SUBSCRIBE Positions`

*   Removed `last_updated_timestamp` from the response
*   Renamed `position` to `amount`
*   Added `instrument_name` in the response
*   Added `mark_price` in the response
*   Added `greeks` in the response which include option's Greeks and IV

`SUBSCRIBE Fills`

*   Newly added
