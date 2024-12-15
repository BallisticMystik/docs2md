Title: Release v1.0.0

URL Source: https://api-docs.aevo.xyz/changelog/release-v100

Markdown Content:
Authentication can be now done by signing with your API secret. The API secrets are identical to API key for existing API keys. Newly-generated API keys create new API secrets.

You can find your API keys and secrets on the [Settings page](https://testnet.aevo.xyz/settings). The copied value looks like `API_KEY:API_SECRET`.

* * *

*   [Updated authentication](https://docs.aevo.xyz/reference/rest-authentication) to two methods - authenticating with secret and authenticating with signatures

* * *

*   Unified the websocket URLs into 1 single URL: ws.aevo.xyz and ws-testnet.aevo.xyz.
*   Improved performance for websocket endpoints
*   Added rate limits for websocket messages
*   Subscriptions now take in a list of channels instead
*   New positions channel

*   [Updated authentication](https://docs.aevo.xyz/reference/websocket-authentication) to two methods - authenticating per-connection and authenticating per-message with signatures

*   Ticker channel changed to return all option tickers instead of per-instrument, e.g. `ticker:ETH:OPTION`
*   `iv` property is now under `data.[bids|ask|mark].greeks.iv`

*   Does not return an array of orders anymore
*   Returns the order ID
