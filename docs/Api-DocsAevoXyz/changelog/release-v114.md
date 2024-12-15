Title: Release v1.1.4

URL Source: https://api-docs.aevo.xyz/changelog/release-v114

Markdown Content:
Added support for manually flagging orders for MMP. Miscellaneous changes around adding multi-asset support.

* * *

Currently, all post-only orders are included as MMP triggers by default. Starting from 13th June, **only** orders tagged with `mmp: true` are considered for MMP.

Market making participants are encouraged to pass in the `mmp` parameter when quoting.

* * *

**GET /account**

*   Renamed `fee_structure` to `fee_structures`
*   Modify the response format for fee\_structures to array of objects. It will now indicate the maker/taker fee of each asset and instrument type.

**POST /orders**

*   Added the `mmp` parameter

**POST /order/**

*   Added the `mmp` parameter

**GET /mmp**

*   Added the `asset` query parameter, which defaults to `"ETH"`

**POST /mmp**

*   Added the `asset` parameter, which defaults to `"ETH"`

**POST /reset-mmp**

*   Added the `asset` parameter, which defaults to `"ETH"`

* * *

**PUBLISH Create Order**

*   Added `mmp` parameter

**PUBLISH Edit Order**

*   Added `mmp` parameter
