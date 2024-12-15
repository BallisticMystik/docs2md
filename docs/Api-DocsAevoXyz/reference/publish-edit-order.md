Title: PUBLISH Edit Order

URL Source: https://api-docs.aevo.xyz/reference/publish-edit-order

Markdown Content:
PUBLISH Edit Order
===============
                                                                                                       

[Jump to Content](https://api-docs.aevo.xyz/reference/publish-edit-order#content)

[![Image 3: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

* * *

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/reference/publish-edit-order)[![Image 4: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

API Reference

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/reference/publish-edit-order)

v1.0.3-beta

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

PUBLISH Edit Order

Search

JUMP TO

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

JUMP TO

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

PUBLISH Edit Order
==================

PUB wss://ws.aevo.xyz

Edit an existing order

**REQUEST**

|  |
| --- |
| **id** integer  
Request ID, an arbitrary integer to link requests with responses. Eg. `1` |
| **op** string required  
Operation code: `edit_order` |
| data.**order\_id** string required  
Order ID to be edited. Eg. `0x4c43e0ab72a4edb72dfe4b129148899815d816837b9a7e22d964b884834639f8` |
| data.**instrument** string required  
Instrument ID number. Eg. `12` |
| data.**maker** string required  
Account's Ethereum address.. Eg. `0xE9b3a48d15BE316A8e34FAd53fFDFDddf0C3D24b` |
| data.**is\_buy** boolean required  
True for long order, false for short order. Eg. `12` |
| data.**amount** string required  
Number of contracts. In 6 decimals fixed number. Eg. `1000000` |
| data.**limit\_price** string required  
Order limit price. In 6 decimals fixed number. Eg. `1000000` |
| data.**salt** string required  
A randomly generated number to guarantee transaction uniqueness. Eg. `12345678` |
| data.**timestamp** string  
Timestamp used in order signing in UNIX timestamp in seconds.. Eg. `1680249600` |
| data.**signature** string required  
Hash of order payload signature signed by the account. |
| data.**post\_only** boolean  
Flag to indicate that the order is a maker order, or is immediately rejected if it is a taker order. |
| data.**time\_in\_force** string  
Can be set to GTC or IOC (GTC is set by default) |
| data.**mmp** boolean  
Flag to include the order into MMP (false by default) |

Example

JSON

```
{
  "id": 1,
  "op": "edit_order",
  "data": {
    "order_id": "0xa907d8c3037289f5b38c94760c06ae436566e600884d09cbeee2ef2c64b2695d",
    "instrument": "11235",
    "maker": "0xaaaD4c0fa8287Ca5bCcFf0E71Bf93044De0A3f13",
    "is_buy": true,
    "amount": "10000000",
    "limit_price": "10000000",
    "salt": "1",
    "signature": "0x8aecd6e002780a08dc623233c4bf26f217d13483bf5d75dba49eb4eda865630631505f3dda0294c4f0b8d6b2357f2c2dc5d3c2106aed6e77e88785a6daf602701b"
  }
}
```
  
**RESPONSE**

|  |
| --- |
| **id** integer  
Response ID, an arbitrary integer to link requests with responses. Eg. `1` |
| data.**order\_id** string required  
Order ID is the hash of the order payload. Eg. `0x4c43e0ab72a4edb72dfe4b129148899815d816837b9a7e22d964b884834639f8` |
| data.**account** string required  
Account's Ethereum address. Eg. `0xE9b3a48d15BE316A8e34FAd53fFDFDddf0C3D24b` |
| data.**instrument\_id** string required  
Instrument ID number. Eg. `12` |
| data.**instrument\_name** string required  
Instrument name. Eg. `ETH-24DEC22-1250-C` |
| data.**instrument\_type** string required  
Type of instrument. Allowed values: `OPTION` `PERPETUAL` |
| data.**expiry** string  
Option expiry in UNIX timestamp in nanoseconds. Eg. `1680249600000000000` |
| data.**strike** string  
Option strike price. Eg. `2500` |
| data.**option\_type** string  
Type of option contract. Allowed values: `call` `put` |
| data.**order\_type** string required  
Order type. Allowed values: `limit` `market` |
| data.**order\_status** string required  
Order status. Allowed values: `opened` `cancelled` `partial` `filled` |
| data.**side** string required  
Trade side. Allowed values: `buy` `sell` |
| data.**amount** string required  
Amount of contracts. Eg. `12.23` |
| data.**price** string required  
Price in USD. Eg. `12.23` |
| data.**filled** string required  
Amount filled. Eg. `10.4` |
| data.**initial\_margin** string required  
Margin required to keep an open order. Eg. `12.23` |
| data.**avg\_price** string  
Average execution price in USD. Eg. `12.23` |
| data.**created\_timestamp** string required  
Created timestamp in UNIX timestamp in nanoseconds. Eg. `1680249600000000000` |
| data.**timestamp** string required  
Response timestamp in UNIX timestamp in nanoseconds. Eg. `1680249600000000000` |
| data.**system\_type** string required  
System type where the order is created. Orders created via websocket will default to `API`. |

Example

JSON

```
{
  "id": 1,
  "data": {
    "order_id": "0x4c43e0ab72a4edb72dfe4b129148899815d816837b9a7e22d964b884834639f8",
    "account": "0xE9b3a48d15BE316A8e34FAd53fFDFDddf0C3D24b",
    "instrument_id": "12",
    "instrument_name": "ETH-30JUN23-1600-C",
    "instrument_type": "OPTION",
    "option_type": "put",
    "expiry": "1680249600000000000",
    "strike": "2500",
    "order_type": "limit",
    "order_status": "filled",
    "side": "buy",
    "amount": "12.23",
    "price": "12.34",
    "filled": "12.23",
    "initial_margin": "12.23",
    "avg_price":"12.23",
    "created_timestamp": "1680249600000000000",
    "timestamp": "1680249600000000000",
    "system_type": "API"
  }
}
```
