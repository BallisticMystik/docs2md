Title: Release v1.1.0

URL Source: https://api-docs.aevo.xyz/changelog/release-v110

Markdown Content:
Released improvements for trading as a maker on the exchange.

* * *

**POST /orders**

*   Orders can only be submitted with the use of an API key now.
*   New `post_only` field, which guarantees that a submitted order would be a maker order, or be rejected if not.

**GET /mmp**

*   New `triggered` field, which is `true` when the account goes under MMP.
*   New `amount_change` field returns the amount of contracts filled under the current interval.
*   New `delta_limit` field for the delta limit MMP setting.
*   Renamed `amount` to `amount_limit` for clarity.

**POST /mmp**

*   Renamed `amount` to `amount_limit`.
*   New `delta_limit` field which allows makers to set the maximum change in absolute delta in an interval. It is an unsigned float.

**Other MMP changes**

*   MMP (either with `amount_limit` or `delta_limit`) is only triggered by orders created with the `post_only` setting.

**POST /api-key**

*   API key creation can be done programmatically now.
*   You can whitelist a list of IP addresses (`ip_addresses`) that can use the API key.
*   You can assign `read_only` permission to an API key.

**DELETE /api-key**

*   API keys can be deleted with the use of another API key.

* * *

**SUBSCRIBE Positions**

*   Renamed `greeks` object to `option`
*   Removed `gamma` from the `option` object
*   Added `strike` to the `option` object
*   Added `option_type` to the `option` object
*   Added `expiry` to the `option` object
*   Added `asset` to the `position` object
*   Added `side` to the `position` object
*   Added `avg_entry_price` to the `position` object
*   Added `unrealized_pnl` to the `position` object
*   Added `maintenance_margin` to the `position` object
