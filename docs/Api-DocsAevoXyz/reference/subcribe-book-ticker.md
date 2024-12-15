Title: SUBSCRIBE Book Ticker (NEW)

URL Source: https://api-docs.aevo.xyz/reference/subcribe-book-ticker

Markdown Content:
Jump to Content
Log In
v1.0.3-beta
Technical Docs
API Reference
Changelog
Search
SUBSCRIBE Book Ticker (NEW)
SUB wss://ws.aevo.xyz
Returns instrument ticker information when its top of the book changes and returns information such as: instrument data, bid and asks

UPDATE TIME

Real Time

REQUEST

op string required
Operation code allowed values: subscribe unsubscribe
data array of strings required
Channel name in the format book-ticker:ASSET:INSTRUMENT_TYPE or book-ticker:INSTRUMENT_NAME.
Eg. book-ticker:ETH:OPTION or book-ticker:ETH-31MAR23-1350-C.
ASSET allowed values: ETH & BTC
INSTRUMENT_TYPE allowed values : OPTION PERPETUAL
Example
