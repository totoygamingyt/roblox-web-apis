forked from [matthewdean/roblox-web-apis](https://github.com/matthewdean/roblox-web-apis)<br />

## Table of Contents
* [Roblox API Subdomains](#roblox-api-subdomains)
* [oAuth2 APIs](#oauth2-apis)
* [Roblox Web APIs](#web-apis)
  * [Universe APIs](#universe-apis)
  * [Place APIs](#place-apis)
  * [User APIs](#user-apis)
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
*Earlier in 2020, Roblox implemented oAuth2 into the Creator Dashboard, and now has been used on **2 applications**. It's unsure if Roblox developers will be able to take advantage of it in the future.*
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
* Examples
  * [Visual Auth (Creator Dashboard)](https://www.roblox.com/permission-request?client_id=e3a58e71-5993-4070-a0e1-9c757f6b8748&scope=openId%20profile&response_type=code&redirect_uri=https://create.roblox.com/home)
  * [Visual Auth (BevyLabs)](https://www.roblox.com/permission-request?client_id=b03b1542-931c-4f68-a5c3-3311eeba9ac2&scope=openId%20profile&response_type=code&redirect_uri=https://events.rbx.com/accounts/oidc/callback/)
  * [Direct Auth (Creator Dashboard)](https://apis.roblox.com/application-authorization/v1/authorize?client_id=e3a58e71-5993-4070-a0e1-9c757f6b8748&scope=openId%20profile&response_type=code&redirect_uri=https://create.roblox.com/home)
  * [Direct Auth (BevyLabs)](https://apis.roblox.com/application-authorization/v1/authorize?client_id=b03b1542-931c-4f68-a5c3-3311eeba9ac2&scope=openId%20profile&response_type=code&redirect_uri=https://events.rbx.com/accounts/oidc/callback/)
  * [Client Info (Creator Dashboard)](https://apis.roblox.com/application-authorization/v1/clients/e3a58e71-5993-4070-a0e1-9c757f6b8748)
  * [Client Info (BevyLabs)](https://apis.roblox.com/application-authorization/v1/clients/b03b1542-931c-4f68-a5c3-3311eeba9ac2)
* Other Information
  * Roblox's oAuth2 codes are around 1604 characters long
  

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
</details>

<details><summary>Get aliases of a universe</summary>
 
* https://api.roblox.com/universes/get-aliases?universeId=13058&page=1
</details>

<details><summary>Get symbolic links of a universe</summary>

* https://develop.roblox.com/v1/universes/13058/symbolic-links
</details>

<details><summary>Get if cloud editing is enabled on a universe</summary>
 
* https://api.roblox.com/universes/13058/cloudeditenabled
</details>

<details><summary>Get badges of a universe</summary>
 
* https://badges.roblox.com/v1/universes/13058/badges
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

* users
  * https://users.roblox.com/v1/users/authenticated
    * [Example request](https://users.roblox.com/docs#!/Users/get_v1_users_authenticated)
* assetgame
  * https://assetgame.roblox.com/Game/GetCurrentUser.ashx
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

<details><summary>Get gaemes from a user's profile</summary>
 
* https://www.roblox.com/users/profile/playergames-json?userId=306209
</details>

<details><summary>Get a user's presence</summary>

* http://api.roblox.com/users/306209/onlinestatus
</details>

<details><summary>Get game badges that a user has obtained</summary>
 
* www
  * https://www.roblox.com/users/profile/playerassets-json?assetTypeId=21&userId=306209
* badges
  * https://badges.roblox.com/v1/users/306209/badges
    * [Example request](https://badges.roblox.com/docs#!/Badges/get_v1_users_userId_badges)
  * https://badges.roblox.com/v1/users/306209/badges
    * [Example request](https://badges.roblox.com/docs#!/BadgeAwards/get_v1_users_userId_badges_awarded_dates)
</details>

<details><summary>Get all assets of an asset type that a user has favorited</summary>
* https://www.roblox.com/user/favorites/places
* https://www.roblox.com/users/favorites/list-json?assetTypeId=9&userId=306209
</details>

<details><summary>Get when a user obtained a game badger</summary>

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

<details><summary>Get the inventory of an asset type of a user</summary>

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

<details><summary>Get the number of friends a user has</summary>
 
* api
  * https://api.roblox.com/user/get-friendship-count?userId=306209
* friends
  * https://friends.roblox.com/v1/my/friends/count
    * [Example request](https://friends.roblox.com/docs#!/Friends/get_v1_my_friends_count)
  * https://friends.roblox.com/v1/users/306209/friends/count
    * [Example request](https://friends.roblox.com/docs#!/Friends/get_v1_users_userId_friends_count)

<details><summary>Get a user's following</summary>

* https://friends.roblox.com/v1/users/306209/followings
  * [Example request](https://friends.roblox.com/docs#!/Friends/get_v1_users_targetUserId_followings)
</details>

<details><summary>Get a user's followers</summary>

* https://friends.roblox.com/v1/users/306209/followers
  * [Example request](https://friends.roblox.com/docs#!/Friends/get_v1_users_targetUserId_followers)
</details>

<details><summary>Get a user's groups</summary>

* https://api.roblox.com/users/306209/groups
</details>

<details><summary>Get games created by a user</summary>

* https://games.roblox.com/v2/users/306209/games
  * [Example request](https://games.roblox.com/docs#!/Games/get_v2_users_userId_games)
</details>

<details><summary>Get a user's ouutfits</summary>

* https://avatar.roblox.com/v1/users/306209/outfits
  * [Example request](https://avatar.roblox.com/docs#!/Avatar/get_v1_users_userId_outfits)
</details>

<details><summary>Get the authenticated user's equipped emotes</summary>
 
* https://avatar.roblox.com/v1/emotes
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
