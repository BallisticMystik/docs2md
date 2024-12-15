Title: Signing Orders Without Timestamp

URL Source: https://api-docs.aevo.xyz/reference/signing-orders-copy

Markdown Content:
Signing Orders Without Timestamp
===============
                                                                                                        

[Jump to Content](https://api-docs.aevo.xyz/reference/signing-orders-copy#content)

[![Image 3: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

* * *

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/reference/signing-orders-copy)[![Image 4: Aevo Exchange](https://files.readme.io/dbce2d9-Aevo_Logotype_White.svg)](https://api-docs.aevo.xyz/reference)

API Reference

[Log In](https://api-docs.aevo.xyz/login?redirect_uri=/reference/signing-orders-copy)

v1.0.3-beta

[Technical Docs](https://api-docs.aevo.xyz/docs)[API Reference](https://api-docs.aevo.xyz/reference)[Changelog](https://api-docs.aevo.xyz/changelog)

Signing Orders Without Timestamp

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

Signing Orders Without Timestamp
================================

> ❗️This signing method will be deprecated on 21 August 2023 00.00 UTC
> 
> 
> ----------------------------------------------------------------------
> 
> Please refer to the new signing method [https://docs.aevo.xyz/reference/signing-orders](https://docs.aevo.xyz/reference/signing-orders)

To create an order, a signature needs to be generated. This signature allows for the gasless trading experience in Aevo. The signature generation used by Aevo follows the guideline laid out in the EIP-712 ([https://eips.ethereum.org/EIPS/eip-712](https://eips.ethereum.org/EIPS/eip-712)) . This signing method is widely used and supported in most wallets.

> 🚧Important!
> 
> 
> --------------
> 
> The signature generated for order submission is **different** from the signature for authentication.

Method

[](https://api-docs.aevo.xyz/reference/signing-orders-copy#method)
----------------------------------------------------------------------------

* * *

*   Signature is generated by signing the `Order` payload using the account's `Signing Key`
*   `Signing Key` is generated during Enable Trading.

Example

[](https://api-docs.aevo.xyz/reference/signing-orders-copy#example)
------------------------------------------------------------------------------

* * *

PythonJavaScript

```
from random import randint
from eip712_structs import EIP712Struct, Address, Uint, Boolean, make_domain
from web3 import Web3
from eth_account import Account

# Generate Salt
salt = randint(0, 10**6)

# Limit price and amount is in 6 decimal places
decimals = 10**6
limit_price = int(100 * decimals)  # Limit price of $100
amount = int(2 * decimals)  # Size of 2 contracts

# instrument_id from /options-chain
instrument = 1

class Order(EIP712Struct):
    maker = Address()
    isBuy = Boolean()
    limitPrice = Uint(256)
    amount = Uint(256)
    salt = Uint(256)
    instrument = Uint(256)

order_struct = Order(maker="your_address", # The wallet's main address
                    isBuy=True, # True if buy, False if sell
                    limitPrice=limit_price,
                    amount=amount,
                    salt=salt,
                    instrument=instrument)

# Get bytes
domain = make_domain(name="Aevo Mainnet", version="1", chainId=1)
# Testnet Domain
# domain = make_domain(name='Aevo Testnet', version='1', chainId=11155111)
signable_bytes = Web3.keccak(order_struct.signable_bytes(domain=domain))

# Sign with key
key = "your_signing_key"
signature = Account._sign_hash(signable_bytes, key).signature.hex()
```

```
// Get signing keys, and sign message
const signer = new ethers.Wallet(signingKey);

const orderMessage = {
  maker: "your_wallet_address,
  isBuy: true,  // true if buy, false if sell
  instrument: "ETH-24AUG22-1850-C",
  
  // Limit price is in 6 decimal places. 
  // Eg. $10.00 = "10000000"
  limitPrice: ethers.utils.parseUnits(10, 6).toString(),

  // This is the number of contracts
  amount: 10,

  // Random number
  salt: Math.floor(Math.random() * 100000).toString(),
}

// Get the order signature
const orderSignature = await signer._signTypedData(
  {
    name: "Aevo Mainnet",
    version: "1",
    chainId: 1,
  },
  { 
    Order: [
      { name: "maker", type: "address" },
      { name: "isBuy", type: "bool" },
      { name: "limitPrice", type: "uint256" },
      { name: "amount", type: "uint256" },
      { name: "salt", type: "uint256" },
      { name: "instrument", type: "uint256" },
    ]
  },
  orderMessage
);
```
