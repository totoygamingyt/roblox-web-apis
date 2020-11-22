forked from [matthewdean/roblox-web-apis](https://github.com/matthewdean/roblox-web-apis)<br />

## Table of Contents
* [Roblox API Subdomains](#roblox-api-subdomains)
* [oAuth2 APIs](#oauth2-apis)
* [Roblox Web APIs](#web-apis)
  * [Universe APIs](#universe-apis)
  * [Place APIs](#place-apis)
  * [User APIs](#user-apis)
  * [Group APis](#group-apis)
  * [Marketplace APIs](#marketplace-apis)
    * [Search APIs](#search-apis)
    * [Asset APIs](#asset-apis)
    * [Product APIs](#product-apis)
    * [Game Pass APIs](#game-pass-apis)
    * [Badge APis](#badge-apis)
  * [Image APIs](#image-apis)
* [Clients](#clients)
  * [Windows](#windows)
  * [macOS](#macos)

## Roblox API Subdomains
*click a link to be directed to the public documentation, for a complete documentation of all APIs in one webpage, visit [here](https://api.roblox.com/docs?useConsolidatedPage=true)*
| Site | Description |
| -: | :- |
| [abtesting.roblox.com](https://abtesting.roblox.com/docs) \[ [v1](https://abtesting.roblox.com/docs#!/v1) \] | Endpoints for the A/B Testing framework |
| [accountinformation.roblox.com](https://accountinformation.roblox.com/docs) \[ [v1](https://accountinformation.roblox.com/docs#!/v1) \] | All endpoints for accessing/modifying account information |
| [accountsettings.roblox.com](https://accountsettings.roblox.com/docs) \[ [v1](https://accountsettings.roblox.com/docs#!/v1) \] | All endpoints for account/user settings. |
| [adconfiguration.roblox.com](https://adconfiguration.roblox.com/docs) \[ [v2](https://adconfiguration.roblox.com/docs#!/v2) \| [v1](https://adconfiguration.roblox.com/docs#!/v1) \] | Roblox Ad Configuration related endpoints. |
| [ads.roblox.com](https://ads.roblox.com/docs) \[ [v1](https://ads.roblox.com/docs#!/v1) \] | Ads configuration endpoints. |
| [api.roblox.com](https://api.roblox.com/docs) \[ [v1](https://api.roblox.com/docs#!/v1) \] | Roblox Legacy Api Endpoints |
| [assetdelivery.roblox.com](https://assetdelivery.roblox.com/docs) \[ [v1](https://assetdelivery.roblox.com/docs#!/v1) \] | Serves asset content. |
| [auth.roblox.com](https://auth.roblox.com/docs) \[ [v3](https://auth.roblox.com/docs#!/v3) \| [v2](https://auth.roblox.com/docs#!/v2) \| [v1](https://auth.roblox.com/docs#!/v1) \] | All endpoints that tamper with authentication sessions. |
| [avatar.roblox.com](https://avatar.roblox.com/docs) \[ [v1](https://avatar.roblox.com/docs#!/v1) \] | Endpoints relating to the customization of player avatars. |
| [badges.roblox.com](https://badges.roblox.com/docs) \[ [v2](https://badges.roblox.com/docs#!/v2) \| [v1](https://badges.roblox.com/docs#!/v1) \] | Endpoints for badges and badge awards management. |
| [billing.roblox.com](https://billing.roblox.com/docs) \[ [v1](https://billing.roblox.com/docs#!/v1) \] | Real money transactions and interaction. |
| [captcha.roblox.com](https://captcha.roblox.com/docs) \[ [v1](https://captcha.roblox.com/docs#!/v1) \] | Captcha Api Site |
| [catalog.roblox.com](https://catalog.roblox.com/docs) \[ [v2](https://catalog.roblox.com/docs#!/v2) \| [v1](https://catalog.roblox.com/docs#!/v1) \] | Catalog items browsing and searching. Content and user based catalog items recommendations. |
| [cdnproviders.roblox.com](https://cdnproviders.roblox.com/docs) \[ [v1](https://cdnproviders.roblox.com/docs#!/v1) \] | Purpose of Api here. |
| [chat.roblox.com](https://chat.roblox.com/docs) \[ [v2](https://chat.roblox.com/docs#!/v2) \| [v1.0](https://chat.roblox.com/docs#!/v1.0) \] | All chat and party related endpoints. |
| [clientsettings.roblox.com](https://clientsettings.roblox.com/docs) \[ [v2](https://clientsettings.roblox.com/docs#!/v2) \| [v1](https://clientsettings.roblox.com/docs#!/v1) \] | Used by various Roblox clients to retrieve configuration information. |
| [clientsettingscdn.roblox.com](https://clientsettingscdn.roblox.com/docs) \[ [v2](https://clientsettingscdn.roblox.com/docs#!/v2) \| [v1](https://clientsettingscdn.roblox.com/docs#!/v1) \] | Used by various Roblox clients to retrieve configuration information. |
| [contacts.roblox.com](https://contacts.roblox.com/docs) \[ [v1](https://contacts.roblox.com/docs#!/v1) \] | Contacts and userTag management. |
| [contentstore.roblox.com](https://contentstore.roblox.com/docs) \[ [v1](https://contentstore.roblox.com/docs#!/v1) \] | ApiSite to front the TemporaryStore for files before uploading to S3 |
| [develop.roblox.com](https://develop.roblox.com/docs) \[ [v2](https://develop.roblox.com/docs#!/v2) \| [v1](https://develop.roblox.com/docs#!/v1) \] | Game development configuration endpoints. |
| [economy.roblox.com](https://economy.roblox.com/docs) \[ [v2](https://economy.roblox.com/docs#!/v2) \| [v1](https://economy.roblox.com/docs#!/v1) \] | Endpoints related to transactions and currency. |
| [economycreatorstats.roblox.com](https://economycreatorstats.roblox.com/docs) \[ [v1](https://economycreatorstats.roblox.com/docs#!/v1) \] | Roblox.EconomyCreatorStats.Api endpoints. |
| [engagementpayouts.roblox.com](https://engagementpayouts.roblox.com/docs) \[ [v1](https://engagementpayouts.roblox.com/docs#!/v1) \] | For engagement-based payout information |
| [followings.roblox.com](https://followings.roblox.com/docs) \[ [v2](https://followings.roblox.com/docs#!/v2) \| [v1](https://followings.roblox.com/docs#!/v1) \] | Establishes follow relationship between subscriber entities (users, groups, etc) and source entities (games, groups, assets, etc.) |
| [friends.roblox.com](https://friends.roblox.com/docs) \[ [v1](https://friends.roblox.com/docs#!/v1) \] | Friends, followers, and contacts management. |
| [gameinternationalization.roblox.com](https://gameinternationalization.roblox.com/docs) \[ [v2](https://gameinternationalization.roblox.com/docs#!/v2) \| [v1](https://gameinternationalization.roblox.com/docs#!/v1) \] | Manages internationalization of games such as translating in game content. |
| [gamejoin.roblox.com](https://gamejoin.roblox.com/docs) \[ [v1](https://gamejoin.roblox.com/docs#!/v1) \] | All endpoints around launching a game. |
| [gamepersistence.roblox.com](https://gamepersistence.roblox.com/docs) \[ [v2](https://gamepersistence.roblox.com/docs#!/v2) \| [v1](https://gamepersistence.roblox.com/docs#!/v1) \| [v0](https://gamepersistence.roblox.com/docs#!/v0) \] | Endpoints for the in-game datastore system for storing data for games. |
| [games.roblox.com](https://games.roblox.com/docs) \[ [v2](https://games.roblox.com/docs#!/v2) \| [v1](https://games.roblox.com/docs#!/v1) \] | All endpoints for game discovery, and details. |
| [groups.roblox.com](https://groups.roblox.com/docs) \[ [v2](https://groups.roblox.com/docs#!/v2) \| [v1](https://groups.roblox.com/docs#!/v1) \| [v0](https://groups.roblox.com/docs#!/v0) \] | Groups management. |
| [inventory.roblox.com](https://inventory.roblox.com/docs) \[ [v2](https://inventory.roblox.com/docs#!/v2) \| [v1](https://inventory.roblox.com/docs#!/v1) \] | All endpoints for viewing (but not granting) ownership of items. |
| [itemconfiguration.roblox.com](https://itemconfiguration.roblox.com/docs) \[ [v1](https://itemconfiguration.roblox.com/docs#!/v1) \] | Configure Items (bundles and avatar assets). |
| [locale.roblox.com](https://locale.roblox.com/docs) \[ [v1](https://locale.roblox.com/docs#!/v1) \] | User locale management. |
| [localizationtables.roblox.com](https://localizationtables.roblox.com/docs) \[ [v1](https://localizationtables.roblox.com/docs#!/v1) \] | Handles managing of localization tables. |
| [metrics.roblox.com](https://metrics.roblox.com/docs) \[ [v1](https://metrics.roblox.com/docs#!/v1) \] | Record metrics across Roblox. |
| [midas.roblox.com](https://midas.roblox.com/docs) \[ [v1](https://midas.roblox.com/docs#!/v1) \] | Handle requests around making purchases using Midas |
| [notifications.roblox.com](https://notifications.roblox.com/docs) \[ [v2](https://notifications.roblox.com/docs#!/v2) \] | All notification stream endpoints. |
| [points.roblox.com](https://points.roblox.com/docs) \[ [v1](https://points.roblox.com/docs#!/v1) \] | The web Api for the in-game PointsService. |
| [premiumfeatures.roblox.com](https://premiumfeatures.roblox.com/docs) \[ [v1](https://premiumfeatures.roblox.com/docs#!/v1) \] | This API is for premium features and anything pertaining to account add ons |
| [presence.roblox.com](https://presence.roblox.com/docs) \[ [v1](https://presence.roblox.com/docs#!/v1) \] | All endpoints for managing presence. |
| [privatemessages.roblox.com](https://privatemessages.roblox.com/docs) \[ [v1](https://privatemessages.roblox.com/docs#!/v1) \] | All messages page endpoints. |
| [publish.roblox.com](https://publish.roblox.com/docs) \[ [v1](https://publish.roblox.com/docs#!/v1) \] | All endpoints handling file uploads. |
| [share.roblox.com](https://share.roblox.com/docs) \[ [v1](https://share.roblox.com/docs#!/v1) \] | Purpose of Api here. |
| [textfilter.roblox.com](https://textfilter.roblox.com/docs) \[ [v2](https://textfilter.roblox.com/docs#!/v2) \] | High volume text filtering. |
| [thumbnails.roblox.com](https://thumbnails.roblox.com/docs) \[ [v1](https://thumbnails.roblox.com/docs#!/v1) \] | Endpoints for requesting thumbnails. |
| [thumbnailsresizer.roblox.com](https://thumbnailsresizer.roblox.com/docs) \[ [v1](https://thumbnailsresizer.roblox.com/docs#!/v1) \] | Validate and resize thumbnails to requested dimensions |
| [trades.roblox.com](https://trades.roblox.com/docs) \[ [v1](https://trades.roblox.com/docs#!/v1) \] | Endpoints for trading collectible items. |
| [translationroles.roblox.com](https://translationroles.roblox.com/docs) \[ [v1](https://translationroles.roblox.com/docs#!/v1) \] | Manages translation roles of developers in game localization. |
| [translations.roblox.com](https://translations.roblox.com/docs) \[ [v1](https://translations.roblox.com/docs#!/v1) \] | Endpoints for requesting translations. |
| [twostepverification.roblox.com](https://twostepverification.roblox.com/docs) \[ [v1](https://twostepverification.roblox.com/docs#!/v1) \] | Platform interface for the two step verification system. |
| [users.roblox.com](https://users.roblox.com/docs) \[ [v1](https://users.roblox.com/docs#!/v1) \] | For direct Roblox user information. |
| [voice.roblox.com](https://voice.roblox.com/docs) \[ [v1](https://voice.roblox.com/docs#!/v1) \] | APIs for Voice calls. |

<!-- TODO:
Complete (duh..)
Add proper responses and requests (wish GithHub's Markdown allowed showing the content of files in the repo)
Make this relevant
-->
## oAuth2 APIs
*Earlier in 2020, Roblox implemented oAuth2 into the Creator Dashboard, and now has been used on **3 applications**. It's unsure if Roblox developers will be able to take advantage of it in the future.*
* oAuth2 Configuration
  * https://apis.roblox.com/application-authorization/.well-known/openid-configuration
* Authorization
  * https://apis.roblox.com/application-authorization/v1/authorize?client_id=CLIENT_ID&scope=SCOPE&response_type=RESPONSE_TYPE&redirect_uri=URI
* Visual Authorization
  * https://www.roblox.com/permission-request?client_id=CLIENT_ID&scope=SCOPE&response_type=RESPONSE_TYPE&redirect_uri=URI
* Client Information
  * https://apis.roblox.com/application-authorization/v1/clients/CLIENT_ID
* Known Client IDs
  * **e3a58e71-5993-4070-a0e1-9c757f6b8748** Creator Dashboard
  * **b03b1542-931c-4f68-a5c3-3311eeba9ac2** BevyLabs
  * **e7eec6fe-31bd-4b83-be99-f1fd2cabfafb** DevForum
* Examples
  * [Visual Auth (Creator Dashboard)](https://www.roblox.com/permission-request?client_id=e3a58e71-5993-4070-a0e1-9c757f6b8748&scope=openId%20profile&response_type=code&redirect_uri=https://create.roblox.com/home)
  * [Visual Auth (BevyLabs)](https://www.roblox.com/permission-request?client_id=b03b1542-931c-4f68-a5c3-3311eeba9ac2&scope=openId%20profile&response_type=code&redirect_uri=https://events.rbx.com/accounts/oidc/callback/)
  * [Visual Auth (DevForum)](https://www.roblox.com/permission-request?client_id=e7eec6fe-31bd-4b83-be99-f1fd2cabfafb&scope=openid%20profile%20email&response_type=code&redirect_uri=https://devforum.roblox.com/auth/oidc/callback)
  * [Direct Auth (Creator Dashboard)](https://apis.roblox.com/application-authorization/v1/authorize?client_id=e3a58e71-5993-4070-a0e1-9c757f6b8748&scope=openId%20profile&response_type=code&redirect_uri=https://create.roblox.com/home)
  * [Direct Auth (BevyLabs)](https://apis.roblox.com/application-authorization/v1/authorize?client_id=b03b1542-931c-4f68-a5c3-3311eeba9ac2&scope=openId%20profile&response_type=code&redirect_uri=https://events.rbx.com/accounts/oidc/callback/)
  * [Direct Auth (DevForum)](https://apis.roblox.com/application-authorization/v1/authorize?client_id=e7eec6fe-31bd-4b83-be99-f1fd2cabfafb&scope=openid%20profile%20email&response_type=code&redirect_uri=https://devforum.roblox.com/auth/oidc/callback)
  * [Client Info (Creator Dashboard)](https://apis.roblox.com/application-authorization/v1/clients/e3a58e71-5993-4070-a0e1-9c757f6b8748)
  * [Client Info (BevyLabs)](https://apis.roblox.com/application-authorization/v1/clients/b03b1542-931c-4f68-a5c3-3311eeba9ac2)
  * [Client Info (DevForum)](https://apis.roblox.com/application-authorization/v1/clients/e7eec6fe-31bd-4b83-be99-f1fd2cabfafb)
* Other Information
  * Roblox's oAuth2 response codes are around 1604 characters long
  

## Web APIs
*Endpoints on the www, assetgame, and api subdomains are most likely deprecated, and could be removed by Roblox at any time.*

### Universe APIs
<details><summary>Get the private server instances of a universe that the authenticated user can access</summary>
 
* https://www.roblox.com/private-server/instance-list-json?universeId=130580&page=1
</details>

<details><summary>Get start informatioin about a universe</summary>
 
* https://api.roblox.com/v1.1/game-start-info?universeId=13058
</details>

<details><summary>Get information about a universe</summary>

* api
  * https://api.roblox.com/universes/get-info?universeId=13058
* develop
  * https://develop.roblox.com/v1/universes/multiget?ids=13058
    * [Example request](https://develop.roblox.com/docs#!/Universes/get_v1_universes_multiget)
  * https://develop.roblox.com/v1/universes/13058
    * [Example request](https://develop.roblox.com/docs#!/Universes/get_v1_universes_universeId)
* games
  * https://games.roblox.com/v1/games?universeIds=13058
    * [Example request](https://games.roblox.com/docs#!/Games/get_v1_games)
     
</details>

<details><summary>Get gamepasses of a universe</summary>
 
* https://games.roblox.com/v1/games/13058/game-passes
  * [Example request](https://games.roblox.com/docs#!/GamePasses/get_v1_games_universeId_game_passes)
</details>

<details><summary>Get places of a universe</summary>
 
* api
  * https://api.roblox.com/universes/get-universe-places?universeId=13058&page=1
* develop
  * https://develop.roblox.com/v1/universes/13058/places
    * [Example request](https://develop.roblox.com/docs#!/Universes/get_v1_universes_universeId_places)
  * https://develop.roblox.com/v2/universes/13058/places
</details>

<details><summary>Get assets in a universe</summary>
 
* https://api.roblox.com/universes/get-aliases?universeId=13058&page=1
</details>

<details><summary>Get symbolic links of a universe</summary>

* https://develop.roblox.com/v1/universes/13058/symbolic-links
</details>

<details><summary>Get if cloud editing is enabled in a universe</summary>
 
* https://api.roblox.com/universes/13058/cloudeditenabled
</details>

<details><summary>Get the social links of a universe</summary>
 
* https://games.roblox.com/v1/games/1/social-links/list
</details>

<details><summary>Get badges of a universe</summary>
 
* https://badges.roblox.com/v1/universes/13058/badges
  * [Example request](https://badges.roblox.com/docs#!/Badges/get_v1_universes_universeId_badges)
</details>

<details><summary>Get developer products of a universe</summary>
 
* https://api.roblox.com/developerproducts/list?universeId=13058&page=1
</details>



### Place APIs
<details><summary>Get information about a place</summary>

* www 
  * https://www.roblox.com/places/api-get-details?assetId=1818
* games
  * https://games.roblox.com/v1/games/multiget-place-details?placeIds=1818
    * [Example request](https://games.roblox.com/docs#!/Games/get_v1_games_multiget_place_details)
</details>

<details><summary>Get configuration of a place</summary>

* www
  * https://www.roblox.com/places/1818/settings
* develop
  * https://develop.roblox.com/v2/places/1818
    * [Example request](https://develop.roblox.com/docs#!/Places/get_v2_places_placeId)
</details>

<details><summary>Get server instances of a place</summary>

* www
  * https://www.roblox.com/games/getgameinstancesjson?placeId=1818&startindex=0
  * https://www.roblox.com/games/getfriendsgameinstances?placeId=1818&startindex=0
* games
  * https://games.roblox.com/v1/games/1818/servers/Public
    * [Example request](https://games.roblox.com/docs#!/Games/get_v1_games_placeId_servers_serverType)
  * https://games.roblox.com/v1/games/1818/servers/Friend
    * [Example request](https://games.roblox.com/docs#!/Games/get_v1_games_placeId_servers_serverType)
  * https://games.roblox.com/v1/games/1818/servers/VIP
    * [Example request](https://games.roblox.com/docs#!/Games/get_v1_games_placeId_servers_serverType)
</details>

<details><summary>Get information about a user's avatar in a place</summary>

* https://api.roblox.com/v1.1/avatar-fetch?placeId=1818&userId=306209
</details>

<details><summary>Get the universe that a place is assigned to</summary>

* https://api.roblox.com/universes/get-universe-containing-place?placeId=13058
</details>

<details><summary>Get developer products of a place</summary>
 
* https://api.roblox.com/developerproducts/list?placeId=1818&page=1
</details>

<details><summary>Get a place's allowed experimental features</summary>

* https://api.roblox.com/Game/GetAllowedExperimentalFeatures?placeId=1818
</details>

### User APIs
<details><summary>Get the authenticated user</summary>

* www
  * https://www.roblox.com/Game/GetCurrentUser.ashx
* users
  * https://users.roblox.com/v1/users/authenticated
    * [Example request](https://users.roblox.com/docs#!/Users/get_v1_users_authenticated)
</details>

<details><summary>Get information about a user</summary>

* api
  * https://api.roblox.com/users/get-by-username?username=vCaffy
    * [Example request](https://api.roblox.com/docs)
  * https://api.roblox.com/users/306209
    * [Example request](https://api.roblox.com/docs)
* users
  * https://users.roblox.com/v1/users/306209
    * [Example request](https://users.roblox.com/docs#!/Users/get_v1_users_userId)
</details>

<details><summary>Get information and settings about the authenticated user</summary>
 
* www
  * https://www.roblox.com/my/account/json
  * https://www.roblox.com/my/settings/json
  * https://www.roblox.com/my/profile
  * https://www.roblox.com/mobileapi/userinfo
* api
  * https://api.roblox.com/users/account-info
  * https://api.roblox.com/reference/deviceinfo
  * https://api.roblox.com/xboxlive/get-roblox-userInfo
    * last used on the Xbox platform
</details>

<details><summary>Get number of friend requests and unread messages for the authenticated user</summary>
 
* https://api.roblox.com/incoming-items/counts
  * [Example request](https://api.roblox.com/docs)
</details>

<details><summary>Get the balance of the authenticated user</summary>
 
* api
  * https://api.roblox.com/my/balance
  * https://api.roblox.com/my/platform-currency-budget
    * last used on the Xbox platform
  * http://api.roblox.com/currency/balance
* economy
  * https://economy.roblox.com/v1/users/306209/currency
    * [Example request](https://economy.roblox.com/docs#!/Currency/get_v1_users_userId_currency)
* billing
  * https://billing.roblox.com/v1/credit
</details>

<details><summary>Get restrictions and other settings of the authenticated user</summary>

* www
  * https://www.roblox.com/account/settings/private-message-privacy
  * https://www.roblox.com/account/settings/game-chat-privacy
  * https://www.roblox.com/account/settings/app-chat-privacy
  * https://www.roblox.com/account/settings/follow-me-privacy
  * https://www.roblox.com/account/settings/private-server-invite-privacy
  * https://www.roblox.com/account/settings/account-restrictions
  * https://www.roblox.com/account/settings/account-country
  * https://www.roblox.com/account/settings/settings-groups
* accountsettings
  * https://accountsettings.roblox.com/v1/content-restriction
    * [Example request](https://accountsettings.roblox.com/docs#!/ContentRestriction/get_v1_content_restriction)
  * https://accountsettings.roblox.com/v1/privacy
    * [Example request](https://accountsettings.roblox.com/docs#!/PrivacySettings/get_v1_privacy)
  * https://accountsettings.roblox.com/v1/privacy/info
    * [Example request](https://accountsettings.roblox.com/docs#!/PrivacySettings/get_v1_privacy_info)
  * https://accountsettings.roblox.com/v1/inventory-privacy
    * [Example request](https://accountsettings.roblox.com/docs#!/PrivacySettings/get_v1_inventory_privacy)
  * https://accountsettings.roblox.com/v1/trade-privacy
    * [Example request](https://accountsettings.roblox.com/docs#!/TradeSettings/get_v1_trade_privacy)
  * https://accountsettings.roblox.com/v1/trade-value
    * [Example request](https://accountsettings.roblox.com/docs#!/TradeSettings/get_v1_trade_value)
  * https://accountsettings.roblox.com/v1/themes/user
    * [Example request](https://accountsettings.roblox.com/docs#!/ThemeConfiguration/get_v1_themes_consumerType_consumerId)
* accountinformation
  * https://accountinformation.roblox.com/v1/gender
    * [Example request](https://accountinformation.roblox.com/docs#!/AccountInformation/get_v1_gender)
  * https://accountinformation.roblox.com/v1/phone
    * [Example request](https://accountinformation.roblox.com/docs#!/PhoneInformation/get_v1_phone)
  * https://accountinformation.roblox.com/v1/promotion-channels
    * [Example request](https://accountinformation.roblox.com/docs#!/PromotionChannel/get_v1_promotion_channels)
  * https://accountinformation.roblox.com/v1/birthdate
    * [Example request](https://accountinformation.roblox.com/docs#!/AccountInformation/get_v1_birthdate)
  * https://accountinformation.roblox.com/v1/description
    * [Example request](https://accountinformation.roblox.com/docs#!/AccountInformation/get_v1_description)
* notifications
  * http://notifications.roblox.com/v2/notifications/get-settings
    * [Example request](http://notifications.roblox.com/docs#!/Notifications/get_v2_notifications_get_settings)
</details>

<details><summary>Get information about a user's page</summary>

* https://www.roblox.com/users/profile/profileheader-json?userId=306209
</details>

<details><summary>Get games from a user's profile</summary>
 
* https://www.roblox.com/users/profile/playergames-json?userId=306209
</details>

<details><summary>Get a user's presence</summary>

* http://api.roblox.com/users/306209/onlinestatus
</details>

<details><summary>Get if a user has a copy of an asset</summary>
 
* http://api.roblox.com/ownership/hasasset?userId=306209&assetId=1818
  * [Example request](https://api.roblox.com/docs)
</details>

<details><summary>Get if a user can manage an asset</summary>
 
* http://api.roblox.com/users/306209/canmanage/1818
  * [Example request](https://api.roblox.com/docs)
</details>


<details><summary>Get game badges that a user has obtained</summary>
 
* www
  * https://www.roblox.com/users/profile/playerassets-json?assetTypeId=21&userId=306209
* badges
  * https://badges.roblox.com/v1/users/306209/badges
    * [Example request](https://badges.roblox.com/docs#!/Badges/get_v1_users_userId_badges)
</details>

<details><summary>Get all assets that a user has favorited by assetTypeId</summary>
 
* https://www.roblox.com/user/favorites/places
* https://www.roblox.com/users/favorites/list-json?assetTypeId=9&userId=306209
</details>

<details><summary>Get when a user obtained a game badge</summary>

* https://badges.roblox.com/v1/users/306209/badges/awarded-dates?badgeIds=31717745
  * [Example request](https://badges.roblox.com/docs#!/BadgeAwards/get_v1_users_userId_badges_awarded_dates)
</details>

<details><summary>Get roblox badges that a user has obtained</summary>
 
* https://accountinformation.roblox.com/v1/users/306209/roblox-badges
  * [Example request](https://accountinformation.roblox.com/docs#!/RobloxBadges/get_v1_users_userId_roblox_badges)
</details>

<details><summary>Get the collections of a user</summary>

* https://www.roblox.com/users/profile/robloxcollections-json?userId=306209
</details>

<details><summary>Get the inventory of a user by assetTypeId</summary>

* www
  * https://www.roblox.com/users/inventory/list-json?assetTypeId=8&userId=306209
* inventory
  * https://inventory.roblox.com/v2/users/306209/inventory?assetTypes=8
    * [Example request](https://inventory.roblox.com/docs#!/Inventory/get_v2_users_userId_inventory)
</details>

<details><summary>Get the premium subscription of a user</summary>
 
 * https://premiumfeatures.roblox.com/v1/users/306209/subscriptions
 * https://premiumfeatures.roblox.com/v1/users/306209/validate-membership
   * [Example request](https://premiumfeatures.roblox.com/docs#!/PremiumFeaturesUsers/get_v1_users_userId_validate_membership)
</details>

<details><summary>Get the authenticated user's friend requests</summary>
 
* https://friends.roblox.com/v1/my/friends/requests
  * [Example request](https://friends.roblox.com/docs#!/Friends/get_v1_my_friends_requests)
</details>

<details><summary>Get a user's friends</summary>

* api
  * https://api.roblox.com/users/306209/friends
    * [Example request](https://api.roblox.com/docs)
* friends
  * https://friends.roblox.com/v1/users/306209/friends
    * [Example request](https://friends.roblox.com/docs#!/Friends/get_v1_users_userId_friends)
</details>

<details><summary>Get the users that the authenticated user has blocked</summary>
 
* https://api.roblox.com/userblock/getblockedusers?page=1
</details>

<details><summary>Get the number of friends a user has</summary>
 
* api
  * https://api.roblox.com/user/get-friendship-count?userId=306209
* friends
  * https://friends.roblox.com/v1/my/friends/count
    * [Example request](https://friends.roblox.com/docs#!/Friends/get_v1_my_friends_count)
  * https://friends.roblox.com/v1/users/306209/friends/count
    * [Example request](https://friends.roblox.com/docs#!/Friends/get_v1_users_userId_friends_count)
</details>

<details><summary>Get a user's following</summary>

* https://friends.roblox.com/v1/users/306209/followings
  * [Example request](https://friends.roblox.com/docs#!/Friends/get_v1_users_targetUserId_followings)
</details>

<details><summary>Get a user's followers</summary>

* https://friends.roblox.com/v1/users/306209/followers
  * [Example request](https://friends.roblox.com/docs#!/Friends/get_v1_users_targetUserId_followers)
</details>

<details><summary>Get a user's groups</summary>

* api
  * https://api.roblox.com/users/306209/groups
    * Most likely a proxy to the **groups/v0** version
    * [Example request](https://api.roblox.com/docs)
* groups
  * https://groups.roblox.com/v0/users/1/groups
</details>

<details><summary>Get groups that the authenticated user can manage</summary>

* https://develop.roblox.com//v1/user/groups/canmanage
  * [Example request](https://develop.roblox.com//docs/#!/User/get_v1_user_groups_canmanage)
</details>

<details><summary>Get games created by a user</summary>
 
* games
  * https://games.roblox.com/v2/users/306209/games
    * [Example request](https://games.roblox.com/docs#!/Games/get_v2_users_userId_games)
* develop
  * https://develop.roblox.com/v1/user/universes
    * [Example request](https://develop.roblox.com/docs#!/User/get_v1_user_universes)
</details>

<details><summary>Get a user's outfits</summary>

* https://avatar.roblox.com/v1/users/306209/outfits
  * [Example request](https://avatar.roblox.com/docs#!/Avatar/get_v1_users_userId_outfits)
</details>

<details><summary>Get the authenticated user's equipped emotes</summary>
 
* https://avatar.roblox.com/v1/emotes
</details>

<details><summary>Get if the authenticated user is a verified creator</summary>
 
* https://develop.roblox.com/v1/user/is-verified-creator

</details>

<details><summary>Get the roles for each group a user is in</summary>
 
* https://groups.roblox.com/v2/users/306209/groups/roles
  * [Example request](https://groups.roblox.com/docs#!/Groups/get_v2_users_userId_groups_roles)
* https://groups.roblox.com/v1/users/306209/groups/roles
  * [Example request](https://groups.roblox.com/docs#!/Membership/get_v1_users_userId_groups_roles)
</details>

<details><summary>Get a user's linked social networks</summary>
 
* https://accountinformation.roblox.com/v1/promotion-channels
* https://accountinformation.roblox.com/v1/users/306209/promotion-channels
</details>

<details><summary>Get the authenticated user's creations by assetType</summary>
 
* https://itemconfiguration.roblox.com/v1/creations/get-assets?assetType=1
  * [Example request](https://itemconfiguration.roblox.com/docs#!/Item/get_v1_creations_get_assets)
</details>

<details><summary>Get the authenticated user's permissions for an asset</summary>
 
* https://develop.roblox.com/v1/packages/assets/highest-permissions?assetIds=1818
* https://develop.roblox.com/v1/packages/assets/1818/permissions
</details>

<details><summary>Get the authenticated user's permission for a universe</summary>
 
* https://develop.roblox.com/v2/universes/13058/permissions
* https://develop.roblox.com/v1/universes/13058/permissions
  * [Example request](https://develop.roblox.com/docs#!/Universes/get_v1_universes_universeId_permissions)
</details>

### Group APIs
<details><summary>Get information about a group</summary>
 
* api
  * https://api.roblox.com/groups/1
    * Most likely a proxy to the **groups/v0** version
    * [Example request](https://api.roblox.com/docs)
* groups
  * https://groups.roblox.com/v0/groups/1
  * https://groups.roblox.com/v2/groups?groupIds=1
    * [Example request](https://groups.roblox.com/docs#!/Groups/get_v2_groups)
  * https://groups.roblox.com/v1/groups/1
    * [Example request](https://groups.roblox.com/docs#!/Groups/get_v1_groups_groupId)
</details>

<details><summary>Get a group's games</summary>
 
* games
  * https://games.roblox.com/v2/groups/1/games
    * [Example request](https://games.roblox.com/docs#!/Games/get_v2_groups_groupId_games)
  * https://games.roblox.com/v2/groups/1/gamesV2
    * [Example request](https://games.roblox.com/docs#!/Games/get_v2_groups_groupId_gamesV2)
    * Differentiates itself from V1 by not allowing Public universes to be accessed
* develop
  * https://develop.roblox.com/v1/groups/1/universes
    * [Example request](https://develop.roblox.com/docs#!/Groups/get_v1_groups_groupId_universes)
</details>

<details><summary>Get a group's rolesets</summary>

* https://groups.roblox.com/v1/groups/1/roles
  * [Example request](https://groups.roblox.com/docs#!/Membership/get_v1_groups_groupId_roles)
</details>

<details><summary>Get users in a group</summary>
 
* https://groups.roblox.com/v1/groups/1/users
  * [Example request](https://groups.roblox.com/docs#!/Membership/get_v1_groups_groupId_users)
</details>

<details><summary>Get users in a roleset of a group</summary>
 
* https://groups.roblox.com/v1/groups/1/roles/231/users
  * [Example request](https://groups.roblox.com/docs#!/Membership/get_v1_groups_groupId_roles_roleSetId_users)
</details>

<details><summary>Get the settings of a group</summary>

* https://groups.roblox.com/v1/groups/1/settings
  * [Example request](https://groups.roblox.com/docs#!/Groups/get_v1_groups_groupId_settings)
</details>

<details><summary>Get a group's wall posts</summary>
 
* https://groups.roblox.com/v1/groups/1/wall/posts
  * [Example request](https://groups.roblox.com/docs#!/Wall/get_v1_groups_groupId_wall_posts)
* https://groups.roblox.com/v2/groups/1/wall/posts
  * [Example request](https://groups.roblox.com/docs#!/Wall/get_v2_groups_groupId_wall_posts)
</details>

<details><summary>Get a group's social links</summary>
 
* https://groups.roblox.com/v1/groups/1/social-links
  * [Example request](https://groups.roblox.com/docs#!/SocialLinks/get_v1_groups_groupId_social_links)
</details>

<details><summary>Get a group's allies</summary>
 
* api
  * https://api.roblox.com/groups/1/allies
    * Most likely a proxy to the **groups/v0** version
    * [Example request](https://api.roblox.com/docs)
* groups
  * https://groups.roblox.com/v0/groups/1/relationships?relationshipType=ally
</details>

<details><summary>Get a group's enemies</summary>
 
* api
  * https://api.roblox.com/groups/1/enemies
    * Most likely a proxy to the **groups/v0** version
    * [Example request](https://api.roblox.com/docs)
* groups
  * https://groups.roblox.com/v0/groups/1/relationships?relationshipType=enemy
</details>

<details><summary>Get a group's funds</summary>
 
* https://economy.roblox.com/v1/groups/1/currency
  * [Example request](https://economy.roblox.com/docs#!/Currency/get_v1_groups_groupId_currency)
</details>

<details><summary>Get a group's creations by assetType</summary>
 
* https://itemconfiguration.roblox.com/v1/creations/get-assets?assetType=1&groupId=1
  * [Example request](https://itemconfiguration.roblox.com/docs#!/Item/get_v1_creations_get_assets)
</details>

### Marketplace APIs
### Search APis
<details><summary>Search assets in the library</summary>
 
* https://search.roblox.com/catalog/json?Category=Decals&SortType=1&Keyword=Bruh
</details>

<details><summary>Search assets in the toolbox</summary>
 
* apis
  * https://apis.roblox.com/toolbox-service/v1/Models
    * Used by the in-game Toolbox, use may be limited and could be removed at any time.
* www
  * https://www.roblox.com/IDE/Toolbox/Items?category=FreeModels&keyword=Yes
* develop
  * https://develop.roblox.com/v1/toolbox/items?category=FreeModels&keyword=Yes
    * [Example request](https://develop.roblox.com/docs#!/Toolbox2014/get_v1_toolbox_items)
</details>

<details><summary>Search users</summary>

* www
  * https://www.roblox.com/search/users/results?keyword=vCaffy
* users
  * https://users.roblox.com/v1/users/search?keyword=vCaffy
    * [Example request](https://users.roblox.com/docs#!/UserSearch/get_v1_users_search)
</details>

<details><summary>Search groups</summary>
 
* https://groups.roblox.com/v1/groups/search?keyword=Roblox
  * [Example request](https://groups.roblox.com/docs#!/GroupSearch/get_v1_groups_search)
* https://groups.roblox.com/v1/groups/search/lookup?groupName=Roblox
  * [Example request](https://groups.roblox.com/docs#!/GroupSearch/get_v1_groups_search_lookup)
</details>

<details><summary>Search avatar shop items</summary>
 
* https://catalog.roblox.com/v1/search/items?Category=3&MaxPrice=1000
  * [Example request](https://developer.roblox.com/en-us/articles/Catalog-API)
</details>

<details><summary>Search avatar shop items with details</summary>

* https://catalog.roblox.com/v1/search/items/details?Category=3&MaxPrice=1000
  * [Example request](https://developer.roblox.com/en-us/articles/Catalog-API)
</details>

#### Asset APIs
<details><summary>Get information about an asset</summary>

* https://api.roblox.com/marketplace/productinfo?assetId=1818
  * [Example request](https://api.roblox.com/docs)
</details>

<details><summary>Get the file of an asset</summary>

* https://assetdelivery.roblox.com/v1/asset?id=1818
  * [Example request](https://assetdelivery.roblox.com/docs#!/AssetFetch/get_v1_asset)
  * Also accepts `userAssetId` in place of `id`
</details>

<details><summary>Get the file of a specific version of an asset</summary>
 
* https://assetdelivery.roblox.com/v1/asset?id=1818&version=1
  * [Example request](https://assetdelivery.roblox.com/docs#!/AssetFetch/get_v1_asset)
  * Also accepts `userAssetId` in place of` id`
</details>

<details><summary>Get all versions of an asset</summary>
 
* api
  * https://api.roblox.com/assets/1818/versions
    * [Example request](https://api.roblox.com/docs)
  * https://api.roblox.com/v2/assets/1818/versions
    * [Example request](https://api.roblox.com/docs)
* develop
  * https://develop.roblox.com/v1/assets/1818/saved-versions
</details>

<details><summary>Get the current assetVersionId of an asset</summary>
 
* https://www.roblox.com/studio/plugins/info?assetId=1818
  * The `assetVersionId` value is hidden in the HTML source as an input
</details>

<details><summary>Get if an asset's type is an animation</summary>
 
* https://www.roblox.com/studio/animations/validateId?animationId=4751204380
</details>

#### Product APis
*Note that Product IDs and Asset IDs are completely different*
<details><summary>Get information about a product</summary>

* api
  * https://api.roblox.com/marketplace/productdetails?productId=31
* economy
  * https://economy.roblox.com/v1/products/31
</details>

<details><summary>Get if the authenticated user can purchase a product</summary>

* https://economy.roblox.com/v1/products/31?showPurchasable=true
</details>

<details><summary>Get premium features products</summary>
 
* https://premiumfeatures.roblox.com/v1/products
</details>

<details><summary>Get premium features products by typeName</summary>
 
* https://premiumfeatures.roblox.com/v1/products?typeName=Subscription
</details>

#### Game Pass APIs
<details><summary>Get information about a game pass</summary>
 
* http://api.roblox.com/marketplace/game-pass-product-info?gamePassId=11
  * [Example request](https://api.roblox.com/docs)
</details>

#### Badge APIs
<details><summary>Get information about a badge</summary>
 
* https://badges.roblox.com/v1/badges/2124450213
  * [Example request](https://badges.roblox.com/docs#!/Badges/get_v1_badges_badgeId)
</details>

### Image APIs
<!--
<details><summary>Get the resized version of a thumbnail</summary>

pls add i forgot how it works
https://thumbnailsresizer.roblox.com/docs#!/Resize/get_v1_resize_hash_width_height_type_format_filterType
</details>
-->
<details><summary>Get the media for a universe</summary>

* www
  * https://www.roblox.com/thumbnail/place-thumbnails?placeId=1818 (JSON)
* games
  * https://games.roblox.com/v2/games/13058/media (JSON)
    * [Example request](https://games.roblox.com/docs#!/Games/get_v2_games_universeId_media)
* thumbnails
  * https://thumbnails.roblox.com/v1/games/multiget/thumbnails?universeIds=13058&size=768x432&format=Png (JSON)
    * [Example request](https://thumbnails.roblox.com/docs#!/Games/get_v1_games_multiget_thumbnails)
</details>

<details><summary>Get the icon of a universe</summary>
 
* https://thumbnails.roblox.com/v1/games/icons?universeIds=13058&size=512x512&format=Png (JSON)
  * [Example request]https://thumbnails.roblox.com/docs#!/Games/get_v1_games_icons)
</details>

<details><summary>Get the icon of a universe for every supported language</summary>
 
* https://gameinternationalization.roblox.com/v1/game-icon/games/13058
</details>

<details><summary>Get the avatar thumbnail of a user</summary>

* www
  * https://www.roblox.com/avatar-thumbnails?params=[{userId:306209}] (JSON)
  * https://www.roblox.com/avatar-thumbnail/json?userId=306209&height=420&width=420 (SJON)
  * https://www.roblox.com/avatar-thumbnail/image?userId=306209&height=420&width=420 (IMAGE)
  * https://www.roblox.com/Thumbs/Avatar.ashx?username=vCaffy (IMAGE)
     * Also accepts `usserId` in place of `username`
* thumbnails
  * https://thumbnails.roblox.com/v1/users/avatar?userIds=306209&size=420x420&format=Png (JSON)
    * [Example request](https://thumbnails.roblox.com/docs#!/Avatar/get_v1_users_avatar)
</detaILs>

<details><summary>Get 3d avatar information of a user</summary>
 
* www
  * https://www.roblox.com/avatar-thumbnail-3d/json?userId=306209 (JSON)
* thumbnails
  * https://thumbnails.roblox.com/v1/users/avatar-3d?userId=306209 (JSON)
    * [Example request](https://thumbnails.roblox.com/docs#!/Avatar/get_v1_users_avatar_3d)
</details>

<details><summary>Get the avatar headshot thumbnail of a user</summary>
 
* www
  * https://www.roblox.com/thumbnail/avatar-headshot?userId=306209 (JSON)
  * https://www.roblox.com/headshot-thumbnail/json?userId=306209&width=420&height=420 (JSON)
  * https://www.roblox.com/headshot-thumbnail/image?userId=306209&width=420&height=420 (IMAGE)
  * https://www.roblox.com/avatar-thumbnails?params=[{userId:306209}] (JSON)
* thumbnails
  * https://thumbnails.roblox.com/v1/users/avatar-headshot?userIds=306209&size=420x420&format=Png
    * [Example request](https://thumbnails.roblox.com/docs#!/Avatar/get_v1_users_avatar_headshot)
</details>

<details><summary>Get the bust thumbnail of a user</summary>
 
* www
  * https://www.roblox.com/bust-thumbnail/json?userId=306209&width=420&height=420 (JSON)
  * https://www.roblox.com/bust-thumbnail/image?userId=306209&width=420&height=420 (IMAGE)
* thumbnails
  * https://thumbnails.roblox.com/v1/users/avatar-bust?userIds=306209&size=75x75&format=Png (JSON)
    * [Example request](https://thumbnails.roblox.com/docs#!/Avatar/get_v1_users_avatar_bust)
</details>

<details><summary>Get the thumbnail of a user outfit</summary>
 
* www
  * https://www.roblox.com/outfit-thumbnail/image?userOutfitId=2111&width=420&height=420&format=png (IMAGE)
* thumbnails
   * https://thumbnails.roblox.com/v1/users/outfits?userOutfitIds=2111&size=420x420&format=Png (JSON)
     * [Example request](https://thumbnails.roblox.com/docs#!/Outfits/get_v1_users_outfits)
</details>

<details><summary>Get the icon of a group</summary>
 
* www
  * https://www.roblox.com/group-thumbnails?params=[{groupId:1}] (JSON)
* thumbnails
  * https://thumbnails.roblox.com/v1/groups/icons?groupIds=1&size=420x420&format=Png (JSON)
    * [Example request](https://thumbnails.roblox.com/docs#!/GroupEmblem/get_v1_groups_icons)
</details>

<details><summary>Get the thumbnail of an asset</summary>
 
* www
  * https://www.roblox.com/item-thumbnails?params=[{assetId:1818}] (JSON)
  * https://www.roblox.com/Thumbs/RawAsset.ashx?assetId=1818&imageFormat=png&width=420&height=420 (TEXT)
  * https://www.roblox.com/asset-thumbnail/image?assetId=1818&height=420&width=420 (IMAGE)
  * https://www.roblox.com/asset-thumbnail/json?assetId=1818&height=420&width=420 (JSON)
  * https://www.roblox.com/Game/Tools/ThumbnailAsset.ashx?aid=1818&fmt=png&wd=420&ht=420 (IMAGE)
    * Also accepts `assetVersionId` in place of `aid`
  * https://www.roblox.com/Thumbs/Asset.asmx/RequestThumbnail_v2?assetId=1818&thumbnailFormatId=296&overrideModeration=true (JSON)
    * Also accepts `assetVersionId` in place of `assetId`
  * https://www.roblox.com/Thumbs/Asset.ashx?width=420&height=420&assetId=1818 (IMAGE)
    * Also accepts `assetVersionId` in place of `assetId`
* thumbnails
  * https://thumbnails.roblox.com/v1/assets?assetIds=1818&size=420x420&format=Png (JSON)
    * [Example request](https://thumbnails.roblox.com/docs#!/Assets/get_v1_assets)
</summary>

<details<summary>Get 3d thumbnail information of an asset</summary>

* www
  * https://www.roblox.com/asset-thumbnail-3d/json?assetId=1818 (JSON)
* thumbnails
  * https://thumbnails.roblox.com/v1/assets-thumbnail-3d?assetId=1818 (JSON)
    * [Example request](https://thumbnails.roblox.com/docs#!/Assets/get_v1_assets_thumbnail_3d)
</details>

<details><summary>Get the thumbnail of a bundle</summary>

* https://thumbnails.roblox.com/v1/bundles/thumbnails?bundleIds=1&size=420x420&format=Png (JSON)
  * [Example request](https://thumbnails.roblox.com/docs#!/Bundles/get_v1_bundles_thumbnails)
</details>

<details><summary>Get the thumbnail of a game pass</summary>
 
* https://thumbnails.roblox.com/v1/game-passes?gamePassIds=11&size=150x150&format=Png (JSON)
  * [Example request](https://thumbnails.roblox.com/docs#!/GamePasses/get_v1_game_passes)
</details>

<details><summary>Get the thumbnail of a developer product</summary>
 
* https://thumbnails.roblox.com/v1/developer-products/icons?developerProductIds=31&size=420x420&format=Png (JSON)
  * [Example request](https://thumbnails.roblox.com/docs#!/DeveloperProducts/get_v1_developer_products_icons)
</details>

<details><summary>Get the thumbnail of a badge</summary>
 
* https://thumbnails.roblox.com/v1/badges/icons?badgeIds=2124450213&size=150x150&format=Png
  * [Example request](https://thumbnails.roblox.com/docs#!/Badges/get_v1_badges_icons)
</details>

## Clients
### Windows
* [Roblox Studio](http://setup.roblox.com/RobloxStudioLauncherBeta.exe)
  * [Roblox Studio - qq](https://setup.rbxcdn.qq.com/RobloxStudioLauncherBetaCJV.exe)
  * [Roblox Studio - sitetest1](http://setup.sitetest1.robloxlabs.com/RobloxStudioLauncherBeta.exe)
  * [Roblox Studio - sitetest2](http://setup.sitetest2.robloxlabs.com/RobloxStudioLauncherBeta.exe)
  * [Roblox Studio - sitetest3](http://setup.sitetest3.robloxlabs.com/RobloxStudioLauncherBeta.exe)
  * [Roblox Studio - gametest1](http://setup.gametest1.robloxlabs.com/RobloxStudioLauncherBeta.exe)
  * [Roblox Studio - gametest2](http://setup.gametest2.robloxlabs.com/RobloxStudioLauncherBeta.exe)
* [Roblox](http://setup.roblox.com/Roblox.exe)
  * [Roblox - sitetest1](http://setup.sitetest1.robloxlabs.com/Roblox.exe)
  * [Roblox - sitetest2](http://setup.sitetest2.robloxlabs.com/Roblox.exe)
  * [Roblox - sitetest3](http://setup.sitetest3.robloxlabs.com/Roblox.exe)
  * [Roblox - gametest1](http://setup.gametest1.robloxlabs.com/Roblox.exe)
  * [Roblox - gametest2](http://setup.gametest2.robloxlabs.com/Roblox.exe)
### macOS
* [Roblox Studio](http://setup.roblox.com/mac/RobloxStudio.dmg)
* [Roblox](http://setup.roblox.com/mac/Roblox.dmg)
