Title: Release v1.1.8

URL Source: https://api-docs.aevo.xyz/changelog/release-v118

Markdown Content:
Introduces pagination on all history endpoints. In the previous version, history endpoints returns an array of history objects. In the current version, the response has been updated to include a `count` field along with the array of history objects. The history object fields for each endpoints remain the same.

* * *

`GET /order-history`

*   response is now an object with 2 fields: `count` and `order_history`
*   `order_history` contains the order history array
*   added `offset` field for pagination

`GET /trade-history`

*   response is now an object with 2 fields: `count` and trade\_history\`
*   `trade_history` contains the trade history array
*   added `limit` and `offset` fields for pagination

`GET /transaction-history`

*   response is now an object with 2 fields: `count` and `transaction_history`
*   `transaction_history` contains the transaction history array
*   added `limit` and `offset` fields for pagination

`GET /referral-rewards-history`

*   response is now an object with 2 fields: `count` and `referral_rewards_history`
*   `referral_rewards_history` contains the referral rewards history array
*   added `limit` and `offset` fields for pagination

`GET /referral-history`

*   response is now an object with 2 fields: `count` and `referral_history`
*   `referral_history` contains the referral history array
*   added `limit` and `offset` fields for pagination
