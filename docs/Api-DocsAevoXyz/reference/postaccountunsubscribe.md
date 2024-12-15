Title: POST /account/unsubscribe

URL Source: https://api-docs.aevo.xyz/reference/postaccountunsubscribe

Markdown Content:
POST /account/unsubscribe
===============
                                                                                   

[Jump to Content](https://api-docs.aevo.xyz/reference/postaccountunsubscribe#content)

[![Image 3: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

* * *

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/reference/postaccountunsubscribe)[![Image 4: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

API Reference

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/reference/postaccountunsubscribe)

v1.0.3-beta

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

POST /account/unsubscribe

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

POST /account/unsubscribe


===========================

post https://api.aevo.xyz/account/unsubscribe

Unsubscribe from all email preferences

Language

ShellNodeRubyPHPPython

RESPONSE

Click `Try It!` to start a request and see the response here!
