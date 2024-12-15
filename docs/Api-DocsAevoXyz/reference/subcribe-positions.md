Title: SUBCRIBE Positions

URL Source: https://api-docs.aevo.xyz/reference/subcribe-positions

Markdown Content:
Jump to Content
Log In
v1.0.3-beta
Technical Docs
API Reference
Changelog
Search
SUBCRIBE Positions
SUB wss://ws.aevo.xyz

Returns relevant positions if any changes occur.

REQUEST

op string required
Operation code allowed values: subscribe unsubscribe
data array of strings required
Channel name: positions
Example



RESPONSE

channel string required
Channel name: positions
data.timestamp string required
Update timestamp in UNIX timestamp in nanoseconds. Eg. 1680249600000000000
data.positions array of objects required
Positions in Position object format.

POSITION OBJECT
instrument_id string required
Instrument ID number. Eg. 12
instrument_name string required
Instrument name. Eg. ETH-24DEC22-1250-C
instrument_type string required
Type of instrument. Allowed values: OPTION PERPETUAL
amount string required
Amount of contracts. Negative amount means the position is net short. Eg. 12.23
mark_price string required
Mark price. Eg. 12.23
option object

OPTION OBJECT
strike string required
Option strike price. Eg. 2500
option_type string required
Type of option contract. Allowed values: call put
expiry string required
Option expiry in UNIX timestamp in nanoseconds. Eg. 1680249600000000000
iv string required
Implied volatility. Eg. 0.23
delta string required
Option's Delta. Eg. 0.23
theta string required
Option's Theta. Eg. 0.23
rho string required
Option's Rho. Eg. 0.23
vega string required
Option's Vega. Eg. 0.23

asset string required
Name of underlying asset. Eg. ETH
side string required
Trade side. Allowed values: buy sell
avg_entry_price string required
Average entry price. Eg. 12.23
unrealized_pnl string required
Unrealized PNL. Eg. 12.23
maintenance_margin string required
Maintenance margin. Eg. 12.23
Example
