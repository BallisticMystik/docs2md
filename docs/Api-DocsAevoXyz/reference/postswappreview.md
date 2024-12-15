Title: POST /swap/preview

URL Source: https://api-docs.aevo.xyz/reference/postswappreview

Markdown Content:
POST /swap/preview
=============== 

[Jump to Content](https://api-docs.aevo.xyz/reference/postswappreview#content)

[![Image 3: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

* * *

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/reference/postswappreview)[![Image 4: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

API Reference

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/reference/postswappreview)

v1.0.3-beta

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

POST /swap/preview

Search

CTRL-K

All

Technical Docs

Reference

Changelog

###### Start typing to search…

JUMP TOCTRL-/

Aevo API
--------

*   [Introduction](https://api-docs.aevo.xyz/reference/overview)
*   [API Key Setup](https://api-docs.aevo.xyz/reference/api-key-setup-via-ui)
    *   [Via UI](https://api-docs.aevo.xyz/reference/api-key-setup-via-ui)
    *   [Via API](https://api-docs.aevo.xyz/reference/api-key-setup-api)
*   [Signing Orders](https://api-docs.aevo.xyz/reference/signing-orders)
*   [Signing Orders Without Timestamp](https://api-docs.aevo.xyz/reference/signing-orders-copy)
*   [Rate Limits](https://api-docs.aevo.xyz/reference/rate-limits-1)
*   [Orderbook Checksum](https://api-docs.aevo.xyz/reference/orderbook-checksum)
*   [Errors](https://api-docs.aevo.xyz/reference/errors)

Aevo REST API
-------------

*   [Endpoints](https://api-docs.aevo.xyz/reference/urls)
*   [Public API](https://api-docs.aevo.xyz/reference/getassets)
    *   [GET /assetsget](https://api-docs.aevo.xyz/reference/getassets)
    *   [GET /expiriesget](https://api-docs.aevo.xyz/reference/getexpiries)
    *   [GET /indexget](https://api-docs.aevo.xyz/reference/getindex)
    *   [GET /index-historyget](https://api-docs.aevo.xyz/reference/getindexhistory)
    *   [GET /mark-historyget](https://api-docs.aevo.xyz/reference/getmarkhistory)
    *   [GET /settlement-historyget](https://api-docs.aevo.xyz/reference/getsettlementhistory)
    *   [GET /marketsget](https://api-docs.aevo.xyz/reference/getmarkets)
    *   [GET /statisticsget](https://api-docs.aevo.xyz/reference/getstatistics)
    *   [GET /coingecko-statisticsget](https://api-docs.aevo.xyz/reference/getcoingeckostatistics)
    *   [GET /orderbookget](https://api-docs.aevo.xyz/reference/getorderbook)
    *   [GET /fundingget](https://api-docs.aevo.xyz/reference/getfunding)
    *   [GET /funding-historyget](https://api-docs.aevo.xyz/reference/getfundinghistory)
    *   [GET /instrument/{instrument\_name}get](https://api-docs.aevo.xyz/reference/getinstrumentinstrumentname)
    *   [GET /instrument/{instrument\_name}/trade-historyget](https://api-docs.aevo.xyz/reference/getinstrumentinstrumentnametradehistory)
    *   [GET /check-referralget](https://api-docs.aevo.xyz/reference/getcheckreferral)
    *   [GET /emissionsget](https://api-docs.aevo.xyz/reference/getemissions)
    *   [POST /account/unsubscribepost](https://api-docs.aevo.xyz/reference/postaccountunsubscribe)
    *   [GET /timeget](https://api-docs.aevo.xyz/reference/gettime)
    *   [GET /strategiesget](https://api-docs.aevo.xyz/reference/getstrategies)
    *   [GET /yield-vaultget](https://api-docs.aevo.xyz/reference/getyieldvault)
    *   [POST /swap/previewpost](https://api-docs.aevo.xyz/reference/postswappreview)
    *   [GET /airdrop-incentivized-assetsget](https://api-docs.aevo.xyz/reference/getairdropincentivizedassets)
    *   [GET /options-historyget](https://api-docs.aevo.xyz/reference/getoptionshistory)
    *   [POST /account/email-verifiedpost](https://api-docs.aevo.xyz/reference/postaccountemailverified)
    *   [GET /strategy/{strategy\_address}/positionsget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresspositions)
    *   [GET /strategy/{strategy\_address}/trade-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresstradehistory)
    *   [GET /strategy/{strategy\_address}/portfolioget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddressportfolio)
    *   [GET /strategy/{strategy\_address}/balance-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddressbalancehistory)
    *   [GET /strategy/{strategy\_address}/transaction-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresstransactionhistory)
    *   [GET /strategy/{strategy\_address}/pnl-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresspnlhistory)
*   [Private API](https://api-docs.aevo.xyz/reference/rest-authentication)
    *   [Authentication](https://api-docs.aevo.xyz/reference/rest-authentication)
    *   [POST /registerpost](https://api-docs.aevo.xyz/reference/postregister)
    *   [DELETE /api-keydelete](https://api-docs.aevo.xyz/reference/deleteapikey)
    *   [GET /api-keyget](https://api-docs.aevo.xyz/reference/getapikey)
    *   [POST /api-keypost](https://api-docs.aevo.xyz/reference/postapikey)
    *   [DELETE /signing-keydelete](https://api-docs.aevo.xyz/reference/deletesigningkey)
    *   [GET /authget](https://api-docs.aevo.xyz/reference/getauth)
    *   [GET /accountget](https://api-docs.aevo.xyz/reference/getaccount)
    *   [GET /positionsget](https://api-docs.aevo.xyz/reference/getpositions)
    *   [GET /account/cancel-on-disconnectget](https://api-docs.aevo.xyz/reference/getaccountcancelondisconnect)
    *   [POST /account/cancel-on-disconnectpost](https://api-docs.aevo.xyz/reference/postaccountcancelondisconnect)
    *   [POST /account/portfolio-marginpost](https://api-docs.aevo.xyz/reference/postaccountportfoliomargin)
    *   [GET /account/email-addressget](https://api-docs.aevo.xyz/reference/getaccountemailaddress)
    *   [POST /account/email-addresspost](https://api-docs.aevo.xyz/reference/postaccountemailaddress)
    *   [POST /account/email-preferencepost](https://api-docs.aevo.xyz/reference/postaccountemailpreference)
    *   [GET /account/email-preferencesget](https://api-docs.aevo.xyz/reference/getaccountemailpreferences)
    *   [GET /account/email-verifiedget](https://api-docs.aevo.xyz/reference/getaccountemailverified)
    *   [GET /account/accumulated-fundingsget](https://api-docs.aevo.xyz/reference/getaccountaccumulatedfundings)
    *   [POST /account/update-marginpost](https://api-docs.aevo.xyz/reference/postaccountupdatemargin)
    *   [POST /account/margin-typepost](https://api-docs.aevo.xyz/reference/postaccountmargintype)
    *   [POST /account/leveragepost](https://api-docs.aevo.xyz/reference/postaccountleverage)
    *   [GET /account/trades/csvget](https://api-docs.aevo.xyz/reference/getaccounttradescsv)
    *   [GET /account/transactions/csvget](https://api-docs.aevo.xyz/reference/getaccounttransactionscsv)
    *   [GET /account/statsget](https://api-docs.aevo.xyz/reference/getaccountstats)
    *   [GET /portfolioget](https://api-docs.aevo.xyz/reference/getportfolio)
    *   [POST /withdrawpost](https://api-docs.aevo.xyz/reference/postwithdraw)
    *   [GET /strategies/accountget](https://api-docs.aevo.xyz/reference/getstrategiesaccount)
    *   [GET /strategies/account-historyget](https://api-docs.aevo.xyz/reference/getstrategiesaccounthistory)
    *   [POST /strategy/{strategy\_address}/initiate-withdrawpost](https://api-docs.aevo.xyz/reference/poststrategystrategyaddressinitiatewithdraw)
    *   [POST /transferpost](https://api-docs.aevo.xyz/reference/posttransfer)
    *   [GET /ordersget](https://api-docs.aevo.xyz/reference/getorders)
    *   [POST /orderspost](https://api-docs.aevo.xyz/reference/postorders)
    *   [DELETE /orders/{order\_id}delete](https://api-docs.aevo.xyz/reference/deleteordersorderid)
    *   [GET /orders/{order\_id}get](https://api-docs.aevo.xyz/reference/getordersorderid)
    *   [POST /orders/{order\_id}post](https://api-docs.aevo.xyz/reference/postordersorderid)
    *   [DELETE /orders-alldelete](https://api-docs.aevo.xyz/reference/deleteordersall)
    *   [GET /order-historyget](https://api-docs.aevo.xyz/reference/getorderhistory)
    *   [GET /order-history/stopsget](https://api-docs.aevo.xyz/reference/getorderhistorystops)
    *   [GET /trade-historyget](https://api-docs.aevo.xyz/reference/gettradehistory)
    *   [GET /transaction-historyget](https://api-docs.aevo.xyz/reference/gettransactionhistory)
    *   [GET /referral-rewards-historyget](https://api-docs.aevo.xyz/reference/getreferralrewardshistory)
    *   [GET /referral-historyget](https://api-docs.aevo.xyz/reference/getreferralhistory)
    *   [GET /referral-statisticsget](https://api-docs.aevo.xyz/reference/getreferralstatistics)
    *   [POST /claim-referral-rewardspost](https://api-docs.aevo.xyz/reference/postclaimreferralrewards)
    *   [POST /claim-trade-feespost](https://api-docs.aevo.xyz/reference/postclaimtradefees)
    *   [GET /trade-fees-campaign-statsget](https://api-docs.aevo.xyz/reference/gettradefeescampaignstats)
    *   [GET /mmpget](https://api-docs.aevo.xyz/reference/getmmp)
    *   [POST /mmppost](https://api-docs.aevo.xyz/reference/postmmp)
    *   [POST /reset-mmppost](https://api-docs.aevo.xyz/reference/postresetmmp)
    *   [DELETE /rfqsdelete](https://api-docs.aevo.xyz/reference/deleterfqs)
    *   [GET /rfqsget](https://api-docs.aevo.xyz/reference/getrfqs)
    *   [POST /rfqspost](https://api-docs.aevo.xyz/reference/postrfqs)
    *   [DELETE /rfqs/{block\_id}delete](https://api-docs.aevo.xyz/reference/deleterfqsblockid)
    *   [GET /rfqs/{block\_id}/quotesget](https://api-docs.aevo.xyz/reference/getrfqsblockidquotes)
    *   [DELETE /quotesdelete](https://api-docs.aevo.xyz/reference/deletequotes)
    *   [GET /quotesget](https://api-docs.aevo.xyz/reference/getquotes)
    *   [POST /quotespost](https://api-docs.aevo.xyz/reference/postquotes)
    *   [POST /quotes/previewpost](https://api-docs.aevo.xyz/reference/postquotespreview)
    *   [DELETE /quotes/{quote\_id}delete](https://api-docs.aevo.xyz/reference/deletequotesquoteid)
    *   [PUT /quotes/{quote\_id}put](https://api-docs.aevo.xyz/reference/putquotesquoteid)
    *   [POST /swappost](https://api-docs.aevo.xyz/reference/postswap)
    *   [GET /farm-boostget](https://api-docs.aevo.xyz/reference/getfarmboost)
    *   [POST /farm-boostpost](https://api-docs.aevo.xyz/reference/postfarmboost)
    *   [GET /proof-dataget](https://api-docs.aevo.xyz/reference/getproofdata)
    *   [GET /proofs-dataget](https://api-docs.aevo.xyz/reference/getproofsdata)
    *   [GET /leaderboard/campaignget](https://api-docs.aevo.xyz/reference/getleaderboardcampaign)
    *   [POST /campaign-sign-uppost](https://api-docs.aevo.xyz/reference/postcampaignsignup)

Websocket API
-------------

*   [Endpoints](https://api-docs.aevo.xyz/reference/endpoints)
*   [Operations](https://api-docs.aevo.xyz/reference/operations)
*   [Message Format](https://api-docs.aevo.xyz/reference/messaging-format-1)
*   [Managing Connection](https://api-docs.aevo.xyz/reference/overview-1)
*   [Cancel on Disconnect](https://api-docs.aevo.xyz/reference/cancel-on-disconnect)
*   [Public Operations](https://api-docs.aevo.xyz/reference/publish-channel)
    *   [PUBLISH Channels](https://api-docs.aevo.xyz/reference/publish-channel)
    *   [PUBLISH Ping](https://api-docs.aevo.xyz/reference/publish-ping)
    *   [SUBSCRIBE Orderbook Throttled (NEW)](https://api-docs.aevo.xyz/reference/subscribe-orderbook-throttled)
    *   [SUBSCRIBE Book Ticker (NEW)](https://api-docs.aevo.xyz/reference/subcribe-book-ticker)
    *   [SUBSCRIBE Ticker Throttled (NEW)](https://api-docs.aevo.xyz/reference/subscribe-ticker-throttled)
    *   [SUBSCRIBE Index](https://api-docs.aevo.xyz/reference/subcribe-index)
    *   [SUBSCRIBE Trades](https://api-docs.aevo.xyz/reference/subcribe-trades)
*   [Private Operations](https://api-docs.aevo.xyz/reference/websocket-authentication)
    *   [Authentication](https://api-docs.aevo.xyz/reference/websocket-authentication)
    *   [PUBLISH Status](https://api-docs.aevo.xyz/reference/get-status)
    *   [PUBLISH Create Order](https://api-docs.aevo.xyz/reference/publish-create-order)
    *   [PUBLISH Edit Order](https://api-docs.aevo.xyz/reference/publish-edit-order)
    *   [PUBLISH Cancel Order](https://api-docs.aevo.xyz/reference/publish-cancel-order)
    *   [PUBLISH Cancel All Orders](https://api-docs.aevo.xyz/reference/publish-cancel-all-orders)
    *   [SUBCRIBE Orders](https://api-docs.aevo.xyz/reference/subcribe-orders)
    *   [SUBCRIBE Fills](https://api-docs.aevo.xyz/reference/subcribe-fills)
    *   [SUBCRIBE Positions](https://api-docs.aevo.xyz/reference/subcribe-positions)

JUMP TOCTRL-/

Aevo API
--------

*   [Introduction](https://api-docs.aevo.xyz/reference/overview)
*   [API Key Setup](https://api-docs.aevo.xyz/reference/api-key-setup-via-ui)
    *   [Via UI](https://api-docs.aevo.xyz/reference/api-key-setup-via-ui)
    *   [Via API](https://api-docs.aevo.xyz/reference/api-key-setup-api)
*   [Signing Orders](https://api-docs.aevo.xyz/reference/signing-orders)
*   [Signing Orders Without Timestamp](https://api-docs.aevo.xyz/reference/signing-orders-copy)
*   [Rate Limits](https://api-docs.aevo.xyz/reference/rate-limits-1)
*   [Orderbook Checksum](https://api-docs.aevo.xyz/reference/orderbook-checksum)
*   [Errors](https://api-docs.aevo.xyz/reference/errors)

Aevo REST API
-------------

*   [Endpoints](https://api-docs.aevo.xyz/reference/urls)
*   [Public API](https://api-docs.aevo.xyz/reference/getassets)
    *   [GET /assetsget](https://api-docs.aevo.xyz/reference/getassets)
    *   [GET /expiriesget](https://api-docs.aevo.xyz/reference/getexpiries)
    *   [GET /indexget](https://api-docs.aevo.xyz/reference/getindex)
    *   [GET /index-historyget](https://api-docs.aevo.xyz/reference/getindexhistory)
    *   [GET /mark-historyget](https://api-docs.aevo.xyz/reference/getmarkhistory)
    *   [GET /settlement-historyget](https://api-docs.aevo.xyz/reference/getsettlementhistory)
    *   [GET /marketsget](https://api-docs.aevo.xyz/reference/getmarkets)
    *   [GET /statisticsget](https://api-docs.aevo.xyz/reference/getstatistics)
    *   [GET /coingecko-statisticsget](https://api-docs.aevo.xyz/reference/getcoingeckostatistics)
    *   [GET /orderbookget](https://api-docs.aevo.xyz/reference/getorderbook)
    *   [GET /fundingget](https://api-docs.aevo.xyz/reference/getfunding)
    *   [GET /funding-historyget](https://api-docs.aevo.xyz/reference/getfundinghistory)
    *   [GET /instrument/{instrument\_name}get](https://api-docs.aevo.xyz/reference/getinstrumentinstrumentname)
    *   [GET /instrument/{instrument\_name}/trade-historyget](https://api-docs.aevo.xyz/reference/getinstrumentinstrumentnametradehistory)
    *   [GET /check-referralget](https://api-docs.aevo.xyz/reference/getcheckreferral)
    *   [GET /emissionsget](https://api-docs.aevo.xyz/reference/getemissions)
    *   [POST /account/unsubscribepost](https://api-docs.aevo.xyz/reference/postaccountunsubscribe)
    *   [GET /timeget](https://api-docs.aevo.xyz/reference/gettime)
    *   [GET /strategiesget](https://api-docs.aevo.xyz/reference/getstrategies)
    *   [GET /yield-vaultget](https://api-docs.aevo.xyz/reference/getyieldvault)
    *   [POST /swap/previewpost](https://api-docs.aevo.xyz/reference/postswappreview)
    *   [GET /airdrop-incentivized-assetsget](https://api-docs.aevo.xyz/reference/getairdropincentivizedassets)
    *   [GET /options-historyget](https://api-docs.aevo.xyz/reference/getoptionshistory)
    *   [POST /account/email-verifiedpost](https://api-docs.aevo.xyz/reference/postaccountemailverified)
    *   [GET /strategy/{strategy\_address}/positionsget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresspositions)
    *   [GET /strategy/{strategy\_address}/trade-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresstradehistory)
    *   [GET /strategy/{strategy\_address}/portfolioget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddressportfolio)
    *   [GET /strategy/{strategy\_address}/balance-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddressbalancehistory)
    *   [GET /strategy/{strategy\_address}/transaction-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresstransactionhistory)
    *   [GET /strategy/{strategy\_address}/pnl-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresspnlhistory)
*   [Private API](https://api-docs.aevo.xyz/reference/rest-authentication)
    *   [Authentication](https://api-docs.aevo.xyz/reference/rest-authentication)
    *   [POST /registerpost](https://api-docs.aevo.xyz/reference/postregister)
    *   [DELETE /api-keydelete](https://api-docs.aevo.xyz/reference/deleteapikey)
    *   [GET /api-keyget](https://api-docs.aevo.xyz/reference/getapikey)
    *   [POST /api-keypost](https://api-docs.aevo.xyz/reference/postapikey)
    *   [DELETE /signing-keydelete](https://api-docs.aevo.xyz/reference/deletesigningkey)
    *   [GET /authget](https://api-docs.aevo.xyz/reference/getauth)
    *   [GET /accountget](https://api-docs.aevo.xyz/reference/getaccount)
    *   [GET /positionsget](https://api-docs.aevo.xyz/reference/getpositions)
    *   [GET /account/cancel-on-disconnectget](https://api-docs.aevo.xyz/reference/getaccountcancelondisconnect)
    *   [POST /account/cancel-on-disconnectpost](https://api-docs.aevo.xyz/reference/postaccountcancelondisconnect)
    *   [POST /account/portfolio-marginpost](https://api-docs.aevo.xyz/reference/postaccountportfoliomargin)
    *   [GET /account/email-addressget](https://api-docs.aevo.xyz/reference/getaccountemailaddress)
    *   [POST /account/email-addresspost](https://api-docs.aevo.xyz/reference/postaccountemailaddress)
    *   [POST /account/email-preferencepost](https://api-docs.aevo.xyz/reference/postaccountemailpreference)
    *   [GET /account/email-preferencesget](https://api-docs.aevo.xyz/reference/getaccountemailpreferences)
    *   [GET /account/email-verifiedget](https://api-docs.aevo.xyz/reference/getaccountemailverified)
    *   [GET /account/accumulated-fundingsget](https://api-docs.aevo.xyz/reference/getaccountaccumulatedfundings)
    *   [POST /account/update-marginpost](https://api-docs.aevo.xyz/reference/postaccountupdatemargin)
    *   [POST /account/margin-typepost](https://api-docs.aevo.xyz/reference/postaccountmargintype)
    *   [POST /account/leveragepost](https://api-docs.aevo.xyz/reference/postaccountleverage)
    *   [GET /account/trades/csvget](https://api-docs.aevo.xyz/reference/getaccounttradescsv)
    *   [GET /account/transactions/csvget](https://api-docs.aevo.xyz/reference/getaccounttransactionscsv)
    *   [GET /account/statsget](https://api-docs.aevo.xyz/reference/getaccountstats)
    *   [GET /portfolioget](https://api-docs.aevo.xyz/reference/getportfolio)
    *   [POST /withdrawpost](https://api-docs.aevo.xyz/reference/postwithdraw)
    *   [GET /strategies/accountget](https://api-docs.aevo.xyz/reference/getstrategiesaccount)
    *   [GET /strategies/account-historyget](https://api-docs.aevo.xyz/reference/getstrategiesaccounthistory)
    *   [POST /strategy/{strategy\_address}/initiate-withdrawpost](https://api-docs.aevo.xyz/reference/poststrategystrategyaddressinitiatewithdraw)
    *   [POST /transferpost](https://api-docs.aevo.xyz/reference/posttransfer)
    *   [GET /ordersget](https://api-docs.aevo.xyz/reference/getorders)
    *   [POST /orderspost](https://api-docs.aevo.xyz/reference/postorders)
    *   [DELETE /orders/{order\_id}delete](https://api-docs.aevo.xyz/reference/deleteordersorderid)
    *   [GET /orders/{order\_id}get](https://api-docs.aevo.xyz/reference/getordersorderid)
    *   [POST /orders/{order\_id}post](https://api-docs.aevo.xyz/reference/postordersorderid)
    *   [DELETE /orders-alldelete](https://api-docs.aevo.xyz/reference/deleteordersall)
    *   [GET /order-historyget](https://api-docs.aevo.xyz/reference/getorderhistory)
    *   [GET /order-history/stopsget](https://api-docs.aevo.xyz/reference/getorderhistorystops)
    *   [GET /trade-historyget](https://api-docs.aevo.xyz/reference/gettradehistory)
    *   [GET /transaction-historyget](https://api-docs.aevo.xyz/reference/gettransactionhistory)
    *   [GET /referral-rewards-historyget](https://api-docs.aevo.xyz/reference/getreferralrewardshistory)
    *   [GET /referral-historyget](https://api-docs.aevo.xyz/reference/getreferralhistory)
    *   [GET /referral-statisticsget](https://api-docs.aevo.xyz/reference/getreferralstatistics)
    *   [POST /claim-referral-rewardspost](https://api-docs.aevo.xyz/reference/postclaimreferralrewards)
    *   [POST /claim-trade-feespost](https://api-docs.aevo.xyz/reference/postclaimtradefees)
    *   [GET /trade-fees-campaign-statsget](https://api-docs.aevo.xyz/reference/gettradefeescampaignstats)
    *   [GET /mmpget](https://api-docs.aevo.xyz/reference/getmmp)
    *   [POST /mmppost](https://api-docs.aevo.xyz/reference/postmmp)
    *   [POST /reset-mmppost](https://api-docs.aevo.xyz/reference/postresetmmp)
    *   [DELETE /rfqsdelete](https://api-docs.aevo.xyz/reference/deleterfqs)
    *   [GET /rfqsget](https://api-docs.aevo.xyz/reference/getrfqs)
    *   [POST /rfqspost](https://api-docs.aevo.xyz/reference/postrfqs)
    *   [DELETE /rfqs/{block\_id}delete](https://api-docs.aevo.xyz/reference/deleterfqsblockid)
    *   [GET /rfqs/{block\_id}/quotesget](https://api-docs.aevo.xyz/reference/getrfqsblockidquotes)
    *   [DELETE /quotesdelete](https://api-docs.aevo.xyz/reference/deletequotes)
    *   [GET /quotesget](https://api-docs.aevo.xyz/reference/getquotes)
    *   [POST /quotespost](https://api-docs.aevo.xyz/reference/postquotes)
    *   [POST /quotes/previewpost](https://api-docs.aevo.xyz/reference/postquotespreview)
    *   [DELETE /quotes/{quote\_id}delete](https://api-docs.aevo.xyz/reference/deletequotesquoteid)
    *   [PUT /quotes/{quote\_id}put](https://api-docs.aevo.xyz/reference/putquotesquoteid)
    *   [POST /swappost](https://api-docs.aevo.xyz/reference/postswap)
    *   [GET /farm-boostget](https://api-docs.aevo.xyz/reference/getfarmboost)
    *   [POST /farm-boostpost](https://api-docs.aevo.xyz/reference/postfarmboost)
    *   [GET /proof-dataget](https://api-docs.aevo.xyz/reference/getproofdata)
    *   [GET /proofs-dataget](https://api-docs.aevo.xyz/reference/getproofsdata)
    *   [GET /leaderboard/campaignget](https://api-docs.aevo.xyz/reference/getleaderboardcampaign)
    *   [POST /campaign-sign-uppost](https://api-docs.aevo.xyz/reference/postcampaignsignup)

Websocket API
-------------

*   [Endpoints](https://api-docs.aevo.xyz/reference/endpoints)
*   [Operations](https://api-docs.aevo.xyz/reference/operations)
*   [Message Format](https://api-docs.aevo.xyz/reference/messaging-format-1)
*   [Managing Connection](https://api-docs.aevo.xyz/reference/overview-1)
*   [Cancel on Disconnect](https://api-docs.aevo.xyz/reference/cancel-on-disconnect)
*   [Public Operations](https://api-docs.aevo.xyz/reference/publish-channel)
    *   [PUBLISH Channels](https://api-docs.aevo.xyz/reference/publish-channel)
    *   [PUBLISH Ping](https://api-docs.aevo.xyz/reference/publish-ping)
    *   [SUBSCRIBE Orderbook Throttled (NEW)](https://api-docs.aevo.xyz/reference/subscribe-orderbook-throttled)
    *   [SUBSCRIBE Book Ticker (NEW)](https://api-docs.aevo.xyz/reference/subcribe-book-ticker)
    *   [SUBSCRIBE Ticker Throttled (NEW)](https://api-docs.aevo.xyz/reference/subscribe-ticker-throttled)
    *   [SUBSCRIBE Index](https://api-docs.aevo.xyz/reference/subcribe-index)
    *   [SUBSCRIBE Trades](https://api-docs.aevo.xyz/reference/subcribe-trades)
*   [Private Operations](https://api-docs.aevo.xyz/reference/websocket-authentication)
    *   [Authentication](https://api-docs.aevo.xyz/reference/websocket-authentication)
    *   [PUBLISH Status](https://api-docs.aevo.xyz/reference/get-status)
    *   [PUBLISH Create Order](https://api-docs.aevo.xyz/reference/publish-create-order)
    *   [PUBLISH Edit Order](https://api-docs.aevo.xyz/reference/publish-edit-order)
    *   [PUBLISH Cancel Order](https://api-docs.aevo.xyz/reference/publish-cancel-order)
    *   [PUBLISH Cancel All Orders](https://api-docs.aevo.xyz/reference/publish-cancel-all-orders)
    *   [SUBCRIBE Orders](https://api-docs.aevo.xyz/reference/subcribe-orders)
    *   [SUBCRIBE Fills](https://api-docs.aevo.xyz/reference/subcribe-fills)
    *   [SUBCRIBE Positions](https://api-docs.aevo.xyz/reference/subcribe-positions)

POST /swap/preview


====================

post https://api.aevo.xyz/swap/preview

Previews a collateral swap

Log in to see full request history

#### URL Expired

The URL for this request expired after 30 days.

Close

Body Params

collateral\_asset

string

required

Name of the collateral asset.

is\_buy

boolean

True for long order, false for short order.

base\_amount

string

The collateral amount. In 6 decimals fixed number for USDT, 18 decimals for WETH, and 8 decimals for WBTC.

quote\_amount

string

Amount of USDC. In 6 decimals fixed number.

Responses

 200

Swap details.
===================

Response body

object

quote\_amount

string

required

Amount of USDC. In 6 decimals fixed number. Eg. `1000000`

fees

string

required

Fees paid for the trade. Eg. `12.23`

fee\_rate

string

required

Funding fee rate in decimals. Only applies to funding trade type. Eg. `0.000065`

base\_balance

string

required

The collateral balance. Eg. `12.23`

quote\_balance

string

required

The USDC balance. Eg. `12.23`

base\_capacity

string

required

The collateral swap capacity balance. Eg. `12.23`

quote\_capacity

string

required

The USDC swap capacity balance. Eg. `12.23`

amount

string

required

The base amount Eg. `1`

price

string

required

The price Eg. `1982`

 400

Bad request.
==================

Response body

object

error

string

required

Error message. Eg. `ERR_MALFORMED_REQUEST`

 401

Unauthorized.
===================

Response body

object

error

string

required

Error message. Eg. `UNAUTHORIZED`

 429

Rate limit exceeded.
==========================

Response body

object

error

string

required

Error message. Eg. `RATE_LIMIT_EXCEEDED`

 500

Internal server error.
============================

Response body

object

error

string

required

Error message. Eg. `INTERNAL_ERROR`

Updated 8 months ago

* * *

[GET /strategies](https://api-docs.aevo.xyz/reference/getstrategies)[GET /airdrop-incentivized-assets](https://api-docs.aevo.xyz/reference/getairdropincentivizedassets)

Did this page help you?

Yes

No

Language

ShellNodeRubyPHPPython

Credentials

Header +1

cURL Request

Examples

xxxxxxxxxx

1

curl \--request POST \\

2

     \--url https://api.aevo.xyz/swap/preview \\

3

     \--header 'accept: application/json' \\

4

     \--header 'content-type: application/json' \\

5

     \--data '

6

{

7

  "collateral\_asset": "USDC"

8

}

9

'

Try It!

RESPONSE

Examples

Click `Try It!` to start a request and see the response here! Or choose an example:

application/json

200400401429500

Updated 8 months ago

* * *

[GET /strategies](https://api-docs.aevo.xyz/reference/getstrategies)[GET /airdrop-incentivized-assets](https://api-docs.aevo.xyz/reference/getairdropincentivizedassets)

Did this page help you?

Yes

No

1.  Aevo API
2.  [Introduction](https://api-docs.aevo.xyz/reference/overview)
3.  [API Key Setup](https://api-docs.aevo.xyz/reference/api-key-setup)
4.  [Via API](https://api-docs.aevo.xyz/reference/api-key-setup-api)
5.  [Via UI](https://api-docs.aevo.xyz/reference/api-key-setup-via-ui)
6.  [Signing Orders](https://api-docs.aevo.xyz/reference/signing-orders)
7.  [Signing Orders Without Timestamp](https://api-docs.aevo.xyz/reference/signing-orders-copy)
8.  [Rate Limits](https://api-docs.aevo.xyz/reference/rate-limits-1)
9.  [Orderbook Checksum](https://api-docs.aevo.xyz/reference/orderbook-checksum)
10.  [Errors](https://api-docs.aevo.xyz/reference/errors)

1.  Aevo REST API
2.  [Endpoints](https://api-docs.aevo.xyz/reference/urls)
3.  [Public API](https://api-docs.aevo.xyz/reference/public-api)
4.  [GET /strategy/{strategy\_address}/pnl-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresspnlhistory)
5.  [GET /strategy/{strategy\_address}/transaction-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresstransactionhistory)
6.  [GET /strategy/{strategy\_address}/balance-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddressbalancehistory)
7.  [GET /strategy/{strategy\_address}/portfolioget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddressportfolio)
8.  [GET /strategy/{strategy\_address}/trade-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresstradehistory)
9.  [GET /strategy/{strategy\_address}/positionsget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresspositions)
10.  [POST /account/email-verifiedpost](https://api-docs.aevo.xyz/reference/postaccountemailverified)
11.  [GET /options-historyget](https://api-docs.aevo.xyz/reference/getoptionshistory)
12.  [GET /airdrop-incentivized-assetsget](https://api-docs.aevo.xyz/reference/getairdropincentivizedassets)
13.  [POST /swap/previewpost](https://api-docs.aevo.xyz/reference/postswappreview)
14.  [GET /yield-vaultget](https://api-docs.aevo.xyz/reference/getyieldvault)
15.  [GET /strategiesget](https://api-docs.aevo.xyz/reference/getstrategies)
16.  [GET /timeget](https://api-docs.aevo.xyz/reference/gettime)
17.  [POST /account/unsubscribepost](https://api-docs.aevo.xyz/reference/postaccountunsubscribe)
18.  [GET /emissionsget](https://api-docs.aevo.xyz/reference/getemissions)
19.  [GET /check-referralget](https://api-docs.aevo.xyz/reference/getcheckreferral)
20.  [GET /instrument/{instrument\_name}/trade-historyget](https://api-docs.aevo.xyz/reference/getinstrumentinstrumentnametradehistory)
21.  [GET /instrument/{instrument\_name}get](https://api-docs.aevo.xyz/reference/getinstrumentinstrumentname)
22.  [GET /funding-historyget](https://api-docs.aevo.xyz/reference/getfundinghistory)
23.  [GET /fundingget](https://api-docs.aevo.xyz/reference/getfunding)
24.  [GET /orderbookget](https://api-docs.aevo.xyz/reference/getorderbook)
25.  [GET /coingecko-statisticsget](https://api-docs.aevo.xyz/reference/getcoingeckostatistics)
26.  [GET /statisticsget](https://api-docs.aevo.xyz/reference/getstatistics)
27.  [GET /marketsget](https://api-docs.aevo.xyz/reference/getmarkets)
28.  [GET /settlement-historyget](https://api-docs.aevo.xyz/reference/getsettlementhistory)
29.  [GET /mark-historyget](https://api-docs.aevo.xyz/reference/getmarkhistory)
30.  [GET /index-historyget](https://api-docs.aevo.xyz/reference/getindexhistory)
31.  [GET /indexget](https://api-docs.aevo.xyz/reference/getindex)
32.  [GET /expiriesget](https://api-docs.aevo.xyz/reference/getexpiries)
33.  [GET /assetsget](https://api-docs.aevo.xyz/reference/getassets)
34.  [Private API](https://api-docs.aevo.xyz/reference/private-api)
35.  [POST /campaign-sign-uppost](https://api-docs.aevo.xyz/reference/postcampaignsignup)
36.  [GET /leaderboard/campaignget](https://api-docs.aevo.xyz/reference/getleaderboardcampaign)
37.  [GET /proofs-dataget](https://api-docs.aevo.xyz/reference/getproofsdata)
38.  [GET /proof-dataget](https://api-docs.aevo.xyz/reference/getproofdata)
39.  [POST /farm-boostpost](https://api-docs.aevo.xyz/reference/postfarmboost)
40.  [GET /farm-boostget](https://api-docs.aevo.xyz/reference/getfarmboost)
41.  [POST /swappost](https://api-docs.aevo.xyz/reference/postswap)
42.  [PUT /quotes/{quote\_id}put](https://api-docs.aevo.xyz/reference/putquotesquoteid)
43.  [DELETE /quotes/{quote\_id}delete](https://api-docs.aevo.xyz/reference/deletequotesquoteid)
44.  [POST /quotes/previewpost](https://api-docs.aevo.xyz/reference/postquotespreview)
45.  [POST /quotespost](https://api-docs.aevo.xyz/reference/postquotes)
46.  [GET /quotesget](https://api-docs.aevo.xyz/reference/getquotes)
47.  [DELETE /quotesdelete](https://api-docs.aevo.xyz/reference/deletequotes)
48.  [GET /rfqs/{block\_id}/quotesget](https://api-docs.aevo.xyz/reference/getrfqsblockidquotes)
49.  [DELETE /rfqs/{block\_id}delete](https://api-docs.aevo.xyz/reference/deleterfqsblockid)
50.  [POST /rfqspost](https://api-docs.aevo.xyz/reference/postrfqs)
51.  [GET /rfqsget](https://api-docs.aevo.xyz/reference/getrfqs)
52.  [DELETE /rfqsdelete](https://api-docs.aevo.xyz/reference/deleterfqs)
53.  [POST /reset-mmppost](https://api-docs.aevo.xyz/reference/postresetmmp)
54.  [POST /mmppost](https://api-docs.aevo.xyz/reference/postmmp)
55.  [GET /mmpget](https://api-docs.aevo.xyz/reference/getmmp)
56.  [GET /trade-fees-campaign-statsget](https://api-docs.aevo.xyz/reference/gettradefeescampaignstats)
57.  [POST /claim-trade-feespost](https://api-docs.aevo.xyz/reference/postclaimtradefees)
58.  [POST /claim-referral-rewardspost](https://api-docs.aevo.xyz/reference/postclaimreferralrewards)
59.  [GET /referral-statisticsget](https://api-docs.aevo.xyz/reference/getreferralstatistics)
60.  [GET /referral-historyget](https://api-docs.aevo.xyz/reference/getreferralhistory)
61.  [GET /referral-rewards-historyget](https://api-docs.aevo.xyz/reference/getreferralrewardshistory)
62.  [GET /transaction-historyget](https://api-docs.aevo.xyz/reference/gettransactionhistory)
63.  [GET /trade-historyget](https://api-docs.aevo.xyz/reference/gettradehistory)
64.  [GET /order-history/stopsget](https://api-docs.aevo.xyz/reference/getorderhistorystops)
65.  [GET /order-historyget](https://api-docs.aevo.xyz/reference/getorderhistory)
66.  [DELETE /orders-alldelete](https://api-docs.aevo.xyz/reference/deleteordersall)
67.  [POST /orders/{order\_id}post](https://api-docs.aevo.xyz/reference/postordersorderid)
68.  [GET /orders/{order\_id}get](https://api-docs.aevo.xyz/reference/getordersorderid)
69.  [DELETE /orders/{order\_id}delete](https://api-docs.aevo.xyz/reference/deleteordersorderid)
70.  [POST /orderspost](https://api-docs.aevo.xyz/reference/postorders)
71.  [GET /ordersget](https://api-docs.aevo.xyz/reference/getorders)
72.  [POST /transferpost](https://api-docs.aevo.xyz/reference/posttransfer)
73.  [POST /strategy/{strategy\_address}/initiate-withdrawpost](https://api-docs.aevo.xyz/reference/poststrategystrategyaddressinitiatewithdraw)
74.  [GET /strategies/account-historyget](https://api-docs.aevo.xyz/reference/getstrategiesaccounthistory)
75.  [GET /strategies/accountget](https://api-docs.aevo.xyz/reference/getstrategiesaccount)
76.  [POST /withdrawpost](https://api-docs.aevo.xyz/reference/postwithdraw)
77.  [GET /portfolioget](https://api-docs.aevo.xyz/reference/getportfolio)
78.  [GET /account/statsget](https://api-docs.aevo.xyz/reference/getaccountstats)
79.  [GET /account/transactions/csvget](https://api-docs.aevo.xyz/reference/getaccounttransactionscsv)
80.  [GET /account/trades/csvget](https://api-docs.aevo.xyz/reference/getaccounttradescsv)
81.  [POST /account/leveragepost](https://api-docs.aevo.xyz/reference/postaccountleverage)
82.  [POST /account/margin-typepost](https://api-docs.aevo.xyz/reference/postaccountmargintype)
83.  [POST /account/update-marginpost](https://api-docs.aevo.xyz/reference/postaccountupdatemargin)
84.  [GET /account/accumulated-fundingsget](https://api-docs.aevo.xyz/reference/getaccountaccumulatedfundings)
85.  [GET /account/email-verifiedget](https://api-docs.aevo.xyz/reference/getaccountemailverified)
86.  [GET /account/email-preferencesget](https://api-docs.aevo.xyz/reference/getaccountemailpreferences)
87.  [POST /account/email-preferencepost](https://api-docs.aevo.xyz/reference/postaccountemailpreference)
88.  [POST /account/email-addresspost](https://api-docs.aevo.xyz/reference/postaccountemailaddress)
89.  [GET /account/email-addressget](https://api-docs.aevo.xyz/reference/getaccountemailaddress)
90.  [POST /account/portfolio-marginpost](https://api-docs.aevo.xyz/reference/postaccountportfoliomargin)
91.  [POST /account/cancel-on-disconnectpost](https://api-docs.aevo.xyz/reference/postaccountcancelondisconnect)
92.  [GET /account/cancel-on-disconnectget](https://api-docs.aevo.xyz/reference/getaccountcancelondisconnect)
93.  [GET /positionsget](https://api-docs.aevo.xyz/reference/getpositions)
94.  [GET /accountget](https://api-docs.aevo.xyz/reference/getaccount)
95.  [GET /authget](https://api-docs.aevo.xyz/reference/getauth)
96.  [DELETE /signing-keydelete](https://api-docs.aevo.xyz/reference/deletesigningkey)
97.  [POST /api-keypost](https://api-docs.aevo.xyz/reference/postapikey)
98.  [GET /api-keyget](https://api-docs.aevo.xyz/reference/getapikey)
99.  [DELETE /api-keydelete](https://api-docs.aevo.xyz/reference/deleteapikey)
100.  [POST /registerpost](https://api-docs.aevo.xyz/reference/postregister)
101.  [Authentication](https://api-docs.aevo.xyz/reference/rest-authentication)

1.  Websocket API
2.  [Endpoints](https://api-docs.aevo.xyz/reference/endpoints)
3.  [Operations](https://api-docs.aevo.xyz/reference/operations)
4.  [Message Format](https://api-docs.aevo.xyz/reference/messaging-format-1)
5.  [Managing Connection](https://api-docs.aevo.xyz/reference/overview-1)
6.  [Cancel on Disconnect](https://api-docs.aevo.xyz/reference/cancel-on-disconnect)
7.  [Public Operations](https://api-docs.aevo.xyz/reference/public-operation)
8.  [SUBSCRIBE Trades](https://api-docs.aevo.xyz/reference/subcribe-trades)
9.  [SUBSCRIBE Index](https://api-docs.aevo.xyz/reference/subcribe-index)
10.  [SUBSCRIBE Ticker Throttled (NEW)](https://api-docs.aevo.xyz/reference/subscribe-ticker-throttled)
11.  [SUBSCRIBE Book Ticker (NEW)](https://api-docs.aevo.xyz/reference/subcribe-book-ticker)
12.  [SUBSCRIBE Orderbook Throttled (NEW)](https://api-docs.aevo.xyz/reference/subscribe-orderbook-throttled)
13.  [PUBLISH Ping](https://api-docs.aevo.xyz/reference/publish-ping)
14.  [PUBLISH Channels](https://api-docs.aevo.xyz/reference/publish-channel)
15.  [Private Operations](https://api-docs.aevo.xyz/reference/private-operations)
16.  [SUBCRIBE Positions](https://api-docs.aevo.xyz/reference/subcribe-positions)
17.  [SUBCRIBE Fills](https://api-docs.aevo.xyz/reference/subcribe-fills)
18.  [SUBCRIBE Orders](https://api-docs.aevo.xyz/reference/subcribe-orders)
19.  [PUBLISH Cancel All Orders](https://api-docs.aevo.xyz/reference/publish-cancel-all-orders)
20.  [PUBLISH Cancel Order](https://api-docs.aevo.xyz/reference/publish-cancel-order)
21.  [PUBLISH Edit Order](https://api-docs.aevo.xyz/reference/publish-edit-order)
22.  [PUBLISH Create Order](https://api-docs.aevo.xyz/reference/publish-create-order)
23.  [PUBLISH Status](https://api-docs.aevo.xyz/reference/get-status)
24.  [Authentication](https://api-docs.aevo.xyz/reference/websocket-authentication)

1.  Aevo API
2.  [Introduction](https://api-docs.aevo.xyz/reference/overview)
3.  [API Key Setup](https://api-docs.aevo.xyz/reference/api-key-setup)
4.  [Via API](https://api-docs.aevo.xyz/reference/api-key-setup-api)
5.  [Via UI](https://api-docs.aevo.xyz/reference/api-key-setup-via-ui)
6.  [Signing Orders](https://api-docs.aevo.xyz/reference/signing-orders)
7.  [Signing Orders Without Timestamp](https://api-docs.aevo.xyz/reference/signing-orders-copy)
8.  [Rate Limits](https://api-docs.aevo.xyz/reference/rate-limits-1)
9.  [Orderbook Checksum](https://api-docs.aevo.xyz/reference/orderbook-checksum)
10.  [Errors](https://api-docs.aevo.xyz/reference/errors)

1.  Aevo REST API
2.  [Endpoints](https://api-docs.aevo.xyz/reference/urls)
3.  [Public API](https://api-docs.aevo.xyz/reference/public-api)
4.  [GET /strategy/{strategy\_address}/pnl-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresspnlhistory)
5.  [GET /strategy/{strategy\_address}/transaction-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresstransactionhistory)
6.  [GET /strategy/{strategy\_address}/balance-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddressbalancehistory)
7.  [GET /strategy/{strategy\_address}/portfolioget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddressportfolio)
8.  [GET /strategy/{strategy\_address}/trade-historyget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresstradehistory)
9.  [GET /strategy/{strategy\_address}/positionsget](https://api-docs.aevo.xyz/reference/getstrategystrategyaddresspositions)
10.  [POST /account/email-verifiedpost](https://api-docs.aevo.xyz/reference/postaccountemailverified)
11.  [GET /options-historyget](https://api-docs.aevo.xyz/reference/getoptionshistory)
12.  [GET /airdrop-incentivized-assetsget](https://api-docs.aevo.xyz/reference/getairdropincentivizedassets)
13.  [POST /swap/previewpost](https://api-docs.aevo.xyz/reference/postswappreview)
14.  [GET /yield-vaultget](https://api-docs.aevo.xyz/reference/getyieldvault)
15.  [GET /strategiesget](https://api-docs.aevo.xyz/reference/getstrategies)
16.  [GET /timeget](https://api-docs.aevo.xyz/reference/gettime)
17.  [POST /account/unsubscribepost](https://api-docs.aevo.xyz/reference/postaccountunsubscribe)
18.  [GET /emissionsget](https://api-docs.aevo.xyz/reference/getemissions)
19.  [GET /check-referralget](https://api-docs.aevo.xyz/reference/getcheckreferral)
20.  [GET /instrument/{instrument\_name}/trade-historyget](https://api-docs.aevo.xyz/reference/getinstrumentinstrumentnametradehistory)
21.  [GET /instrument/{instrument\_name}get](https://api-docs.aevo.xyz/reference/getinstrumentinstrumentname)
22.  [GET /funding-historyget](https://api-docs.aevo.xyz/reference/getfundinghistory)
23.  [GET /fundingget](https://api-docs.aevo.xyz/reference/getfunding)
24.  [GET /orderbookget](https://api-docs.aevo.xyz/reference/getorderbook)
25.  [GET /coingecko-statisticsget](https://api-docs.aevo.xyz/reference/getcoingeckostatistics)
26.  [GET /statisticsget](https://api-docs.aevo.xyz/reference/getstatistics)
27.  [GET /marketsget](https://api-docs.aevo.xyz/reference/getmarkets)
28.  [GET /settlement-historyget](https://api-docs.aevo.xyz/reference/getsettlementhistory)
29.  [GET /mark-historyget](https://api-docs.aevo.xyz/reference/getmarkhistory)
30.  [GET /index-historyget](https://api-docs.aevo.xyz/reference/getindexhistory)
31.  [GET /indexget](https://api-docs.aevo.xyz/reference/getindex)
32.  [GET /expiriesget](https://api-docs.aevo.xyz/reference/getexpiries)
33.  [GET /assetsget](https://api-docs.aevo.xyz/reference/getassets)
34.  [Private API](https://api-docs.aevo.xyz/reference/private-api)
35.  [POST /campaign-sign-uppost](https://api-docs.aevo.xyz/reference/postcampaignsignup)
36.  [GET /leaderboard/campaignget](https://api-docs.aevo.xyz/reference/getleaderboardcampaign)
37.  [GET /proofs-dataget](https://api-docs.aevo.xyz/reference/getproofsdata)
38.  [GET /proof-dataget](https://api-docs.aevo.xyz/reference/getproofdata)
39.  [POST /farm-boostpost](https://api-docs.aevo.xyz/reference/postfarmboost)
40.  [GET /farm-boostget](https://api-docs.aevo.xyz/reference/getfarmboost)
41.  [POST /swappost](https://api-docs.aevo.xyz/reference/postswap)
42.  [PUT /quotes/{quote\_id}put](https://api-docs.aevo.xyz/reference/putquotesquoteid)
43.  [DELETE /quotes/{quote\_id}delete](https://api-docs.aevo.xyz/reference/deletequotesquoteid)
44.  [POST /quotes/previewpost](https://api-docs.aevo.xyz/reference/postquotespreview)
45.  [POST /quotespost](https://api-docs.aevo.xyz/reference/postquotes)
46.  [GET /quotesget](https://api-docs.aevo.xyz/reference/getquotes)
47.  [DELETE /quotesdelete](https://api-docs.aevo.xyz/reference/deletequotes)
48.  [GET /rfqs/{block\_id}/quotesget](https://api-docs.aevo.xyz/reference/getrfqsblockidquotes)
49.  [DELETE /rfqs/{block\_id}delete](https://api-docs.aevo.xyz/reference/deleterfqsblockid)
50.  [POST /rfqspost](https://api-docs.aevo.xyz/reference/postrfqs)
51.  [GET /rfqsget](https://api-docs.aevo.xyz/reference/getrfqs)
52.  [DELETE /rfqsdelete](https://api-docs.aevo.xyz/reference/deleterfqs)
53.  [POST /reset-mmppost](https://api-docs.aevo.xyz/reference/postresetmmp)
54.  [POST /mmppost](https://api-docs.aevo.xyz/reference/postmmp)
55.  [GET /mmpget](https://api-docs.aevo.xyz/reference/getmmp)
56.  [GET /trade-fees-campaign-statsget](https://api-docs.aevo.xyz/reference/gettradefeescampaignstats)
57.  [POST /claim-trade-feespost](https://api-docs.aevo.xyz/reference/postclaimtradefees)
58.  [POST /claim-referral-rewardspost](https://api-docs.aevo.xyz/reference/postclaimreferralrewards)
59.  [GET /referral-statisticsget](https://api-docs.aevo.xyz/reference/getreferralstatistics)
60.  [GET /referral-historyget](https://api-docs.aevo.xyz/reference/getreferralhistory)
61.  [GET /referral-rewards-historyget](https://api-docs.aevo.xyz/reference/getreferralrewardshistory)
62.  [GET /transaction-historyget](https://api-docs.aevo.xyz/reference/gettransactionhistory)
63.  [GET /trade-historyget](https://api-docs.aevo.xyz/reference/gettradehistory)
64.  [GET /order-history/stopsget](https://api-docs.aevo.xyz/reference/getorderhistorystops)
65.  [GET /order-historyget](https://api-docs.aevo.xyz/reference/getorderhistory)
66.  [DELETE /orders-alldelete](https://api-docs.aevo.xyz/reference/deleteordersall)
67.  [POST /orders/{order\_id}post](https://api-docs.aevo.xyz/reference/postordersorderid)
68.  [GET /orders/{order\_id}get](https://api-docs.aevo.xyz/reference/getordersorderid)
69.  [DELETE /orders/{order\_id}delete](https://api-docs.aevo.xyz/reference/deleteordersorderid)
70.  [POST /orderspost](https://api-docs.aevo.xyz/reference/postorders)
71.  [GET /ordersget](https://api-docs.aevo.xyz/reference/getorders)
72.  [POST /transferpost](https://api-docs.aevo.xyz/reference/posttransfer)
73.  [POST /strategy/{strategy\_address}/initiate-withdrawpost](https://api-docs.aevo.xyz/reference/poststrategystrategyaddressinitiatewithdraw)
74.  [GET /strategies/account-historyget](https://api-docs.aevo.xyz/reference/getstrategiesaccounthistory)
75.  [GET /strategies/accountget](https://api-docs.aevo.xyz/reference/getstrategiesaccount)
76.  [POST /withdrawpost](https://api-docs.aevo.xyz/reference/postwithdraw)
77.  [GET /portfolioget](https://api-docs.aevo.xyz/reference/getportfolio)
78.  [GET /account/statsget](https://api-docs.aevo.xyz/reference/getaccountstats)
79.  [GET /account/transactions/csvget](https://api-docs.aevo.xyz/reference/getaccounttransactionscsv)
80.  [GET /account/trades/csvget](https://api-docs.aevo.xyz/reference/getaccounttradescsv)
81.  [POST /account/leveragepost](https://api-docs.aevo.xyz/reference/postaccountleverage)
82.  [POST /account/margin-typepost](https://api-docs.aevo.xyz/reference/postaccountmargintype)
83.  [POST /account/update-marginpost](https://api-docs.aevo.xyz/reference/postaccountupdatemargin)
84.  [GET /account/accumulated-fundingsget](https://api-docs.aevo.xyz/reference/getaccountaccumulatedfundings)
85.  [GET /account/email-verifiedget](https://api-docs.aevo.xyz/reference/getaccountemailverified)
86.  [GET /account/email-preferencesget](https://api-docs.aevo.xyz/reference/getaccountemailpreferences)
87.  [POST /account/email-preferencepost](https://api-docs.aevo.xyz/reference/postaccountemailpreference)
88.  [POST /account/email-addresspost](https://api-docs.aevo.xyz/reference/postaccountemailaddress)
89.  [GET /account/email-addressget](https://api-docs.aevo.xyz/reference/getaccountemailaddress)
90.  [POST /account/portfolio-marginpost](https://api-docs.aevo.xyz/reference/postaccountportfoliomargin)
91.  [POST /account/cancel-on-disconnectpost](https://api-docs.aevo.xyz/reference/postaccountcancelondisconnect)
92.  [GET /account/cancel-on-disconnectget](https://api-docs.aevo.xyz/reference/getaccountcancelondisconnect)
93.  [GET /positionsget](https://api-docs.aevo.xyz/reference/getpositions)
94.  [GET /accountget](https://api-docs.aevo.xyz/reference/getaccount)
95.  [GET /authget](https://api-docs.aevo.xyz/reference/getauth)
96.  [DELETE /signing-keydelete](https://api-docs.aevo.xyz/reference/deletesigningkey)
97.  [POST /api-keypost](https://api-docs.aevo.xyz/reference/postapikey)
98.  [GET /api-keyget](https://api-docs.aevo.xyz/reference/getapikey)
99.  [DELETE /api-keydelete](https://api-docs.aevo.xyz/reference/deleteapikey)
100.  [POST /registerpost](https://api-docs.aevo.xyz/reference/postregister)
101.  [Authentication](https://api-docs.aevo.xyz/reference/rest-authentication)

1.  Websocket API
2.  [Endpoints](https://api-docs.aevo.xyz/reference/endpoints)
3.  [Operations](https://api-docs.aevo.xyz/reference/operations)
4.  [Message Format](https://api-docs.aevo.xyz/reference/messaging-format-1)
5.  [Managing Connection](https://api-docs.aevo.xyz/reference/overview-1)
6.  [Cancel on Disconnect](https://api-docs.aevo.xyz/reference/cancel-on-disconnect)
7.  [Public Operations](https://api-docs.aevo.xyz/reference/public-operation)
8.  [SUBSCRIBE Trades](https://api-docs.aevo.xyz/reference/subcribe-trades)
9.  [SUBSCRIBE Index](https://api-docs.aevo.xyz/reference/subcribe-index)
10.  [SUBSCRIBE Ticker Throttled (NEW)](https://api-docs.aevo.xyz/reference/subscribe-ticker-throttled)
11.  [SUBSCRIBE Book Ticker (NEW)](https://api-docs.aevo.xyz/reference/subcribe-book-ticker)
12.  [SUBSCRIBE Orderbook Throttled (NEW)](https://api-docs.aevo.xyz/reference/subscribe-orderbook-throttled)
13.  [PUBLISH Ping](https://api-docs.aevo.xyz/reference/publish-ping)
14.  [PUBLISH Channels](https://api-docs.aevo.xyz/reference/publish-channel)
15.  [Private Operations](https://api-docs.aevo.xyz/reference/private-operations)
16.  [SUBCRIBE Positions](https://api-docs.aevo.xyz/reference/subcribe-positions)
17.  [SUBCRIBE Fills](https://api-docs.aevo.xyz/reference/subcribe-fills)
18.  [SUBCRIBE Orders](https://api-docs.aevo.xyz/reference/subcribe-orders)
19.  [PUBLISH Cancel All Orders](https://api-docs.aevo.xyz/reference/publish-cancel-all-orders)
20.  [PUBLISH Cancel Order](https://api-docs.aevo.xyz/reference/publish-cancel-order)
21.  [PUBLISH Edit Order](https://api-docs.aevo.xyz/reference/publish-edit-order)
22.  [PUBLISH Create Order](https://api-docs.aevo.xyz/reference/publish-create-order)
23.  [PUBLISH Status](https://api-docs.aevo.xyz/reference/get-status)
24.  [Authentication](https://api-docs.aevo.xyz/reference/websocket-authentication)
