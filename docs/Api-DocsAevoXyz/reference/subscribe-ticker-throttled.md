Title: SUBSCRIBE Ticker Throttled (NEW)

URL Source: https://api-docs.aevo.xyz/reference/subscribe-ticker-throttled

Markdown Content:
Jump to Content
Log In
v1.0.3-beta
Technical Docs
API Reference
Changelog
Search
SUBSCRIBE Ticker Throttled (NEW)
SUB wss://ws.aevo.xyz
Returns instrument ticker information when its top of the book changes and returns information such as: instrument data, funding rates, bid, asks and mark information.

UPDATE TIME

500ms

REQUEST

op string required
Operation code allowed values: subscribe unsubscribe
data array of strings required
Channel name in the format ticker-500ms:ASSET:INSTRUMENT_TYPE or ticker-500ms:INSTRUMENT_NAME.
Eg. ticker-500ms:ETH:OPTION or ticker-500ms:ETH-31MAR23-1350-C.
ASSET allowed values: ETH
INSTRUMENT_TYPE allowed values : OPTION PERPETUAL
Example
